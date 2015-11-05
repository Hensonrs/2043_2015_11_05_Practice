Notes for starting git in 2043

Step 1, get an on-line git account.
Your user name for reference: hensonr@student.swosu.edu (email) hensonr(name)

Step 2, Use a machine that has git installed

Step 3, get to the command prompt and get started

cmd 1: Get to your folder.

Use *dir* to find out what is in the directory.
...
C:\Users\LAB>dir
 Volume in drive C is OS
 Volume Serial Number is EAF3-627D

 Directory of C:\Users\LAB

06/21/2012  01:13 PM    <DIR>          .
06/21/2012  01:13 PM    <DIR>          ..
05/14/2015  08:10 AM    <DIR>          Contacts
11/05/2015  08:12 AM    <DIR>          Desktop
05/14/2015  08:10 AM    <DIR>          Documents
05/14/2015  08:10 AM    <DIR>          Downloads
05/14/2015  08:10 AM    <DIR>          Favorites
05/14/2015  08:10 AM    <DIR>          Links
05/14/2015  08:10 AM    <DIR>          Music
05/14/2015  08:10 AM    <DIR>          Pictures
05/14/2015  08:10 AM    <DIR>          Saved Games
05/14/2015  08:10 AM    <DIR>          Searches
05/14/2015  08:10 AM    <DIR>          Videos
               0 File(s)              0 bytes
              13 Dir(s)  410,612,035,584 bytes free
...
Change directory to the Desktop using *cd* and your file name
...
C:\Users\LAB>cd Desktop

C:\Users\LAB\Desktop>dir
 Volume in drive C is OS
 Volume Serial Number is EAF3-627D

 Directory of C:\Users\LAB\Desktop

11/05/2015  08:12 AM    <DIR>          .
11/05/2015  08:12 AM    <DIR>          ..
11/05/2015  08:11 AM    <DIR>          2043gitPractice
06/21/2012  02:16 PM             1,553 Report Problems-ITS.lnk
               1 File(s)          1,553 bytes
               3 Dir(s)  410,612,035,584 bytes free

C:\Users\LAB\Desktop>cd 2043gitPractice

C:\Users\LAB\Desktop\2043gitPractice>
Big Idea 2: Set up you git folder.
1. Go to github.command
2. Sign in 
3. Create a new repository
4. Name the new repository
5. Provide a meaningful description in the repository.
	Use Who? What? When? Where? Why?
Step 6: Do not select the button to initialize the folder with a readme file
Step 7: Follow the instructions on github for:
	…or create a new repository on the command line

echo # 2043_2015_11_05_Practice >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Hensonrs/2043_2015_11_05_Practice.git
git push -u origin master

Copy one line at a time into the command prompt
After, I will copy the command prompt

C:\Users\LAB\Desktop\2043gitPractice>echo # 2043_2015_11_05_Practice >> README.m
d

C:\Users\LAB\Desktop\2043gitPractice>dir
 Volume in drive C is OS
 Volume Serial Number is EAF3-627D

 Directory of C:\Users\LAB\Desktop\2043gitPractice

11/05/2015  08:42 AM    <DIR>          .
11/05/2015  08:42 AM    <DIR>          ..
11/05/2015  08:42 AM                29 README.md
               1 File(s)             29 bytes
               2 Dir(s)  410,615,791,616 bytes free

C:\Users\LAB\Desktop\2043gitPractice>git init
Initialized empty Git repository in C:/Users/LAB/Desktop/2043gitPractice/.git/

C:\Users\LAB\Desktop\2043gitPractice>git add README.md

C:\Users\LAB\Desktop\2043gitPractice>git add .

C:\Users\LAB\Desktop\2043gitPractice>git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB@STF126C-PC.(none)')

C:\Users\LAB\Desktop\2043gitPractice>git config user.name "hensonr@student.swosu
.edu

C:\Users\LAB\Desktop\2043gitPractice>git config user.name "hensonrs"

C:\Users\LAB\Desktop\2043gitPractice>git config user.email "hensonr@student.swos
u.edu

C:\Users\LAB\Desktop\2043gitPractice>git commit -m "first commit"
[master (root-commit) fc6457d] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\LAB\Desktop\2043gitPractice>git commit -m "first commit"
On branch master
Untracked files:
        GettingStartedWithGithub.md

nothing added to commit but untracked files present

C:\Users\LAB\Desktop\2043gitPractice>git config user.name "hensonrs"

C:\Users\LAB\Desktop\2043gitPractice>git config user.email "hensonr@student.swos
u.edu

C:\Users\LAB\Desktop\2043gitPractice>git commit -m "first commit"
On branch master
Untracked files:
        GettingStartedWithGithub.md

nothing added to commit but untracked files present

C:\Users\LAB\Desktop\2043gitPractice>git remote add origin https://github.com/He
nsonrs/2043_2015_11_05_Practice.git

C:\Users\LAB\Desktop\2043gitPractice>git push -u origin master
Username for 'https://github.com': hensonrs
Password for 'https://hensonrs@github.com':
Counting objects: 3, done.
Writing objects: 100% (3/3), 240 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/Hensonrs/2043_2015_11_05_Practice.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

C:\Users\LAB\Desktop\2043gitPractice>


	
