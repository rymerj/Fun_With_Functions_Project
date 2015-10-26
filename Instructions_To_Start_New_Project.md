# STarting a project in eclipse

1. Open Eclipse

2. Select workspace. (use your flash drive)
: File > Workspace > other 
: Browse ; select folder you want to keep projects in > Click Ok >Click ok
: E:\Comp Science- workspace

3. Create new project folder.
:File > New > Java Project
:Name the file, use default run enviroment, and then finish.

4.Create your new class for your project.
:with your project selected,
: File > New > Class
: Name your project, and use public static void main option.
:Click finish.

#start a local repository

1. Open comand prompt
: Start > Search fo "cmd" > press enter

2. Change drives to my flash drive useing our drive letter and colon "E:".

E:\>

**NOTE: cls can be used to clear the command prompt**

3. Navigate to folder you just created.

E:\>**cd "Comp Science- workspace"**

E:\**Comp Science- workspace>cd Fun_With_Functions_Project**

E:\Comp Science- workspace\Fun_With_Functions_Project>git init**
Initialized empty Git repository in E:/Comp Science- workspace/Fun_With_Function
s_Project/.git/

E:\Comp Science- workspace\Fun_With_Functions_Project>**git add .

E:\Comp Science- workspace\Fun_With_Functions_Project>**git commit -m "first commi
t"**

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'LAB@STF126G-PC.(none)')

E:\Comp Science- workspace\Fun_With_Functions_Project>**git config user.name "Joe
Rymer"**

E:\Comp Science- workspace\Fun_With_Functions_Project>**git config user.email "rym
erj@student.swosu.edu"**

E:\Comp Science- workspace\Fun_With_Functions_Project>**git commit -m "first commi
t"**
[master (root-commit) 39d39af] first commit
 4 files changed, 35 insertions(+)
 create mode 100644 .classpath
 create mode 100644 .project
 create mode 100644 bin/Fun_With_Functions.class
 create mode 100644 src/Fun_With_Functions.java

E:\Comp Science- workspace\Fun_With_Functions_Project>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository us
ing

    git remote add <name> <url>

and then push using the remote name

    git push <name>


E:\Comp Science- workspace\Fun_With_Functions_Project>

#Connect with remote repository

1. Open internet browser

2. Connect to "github.com"

3. Add new repository by clicking the green button labeled "New Repository".
: Name the repository the same name as your java project.
: Give a description of the repository.
: Do not intitilize the repository with a read me file
: click the green button labeled "Create Repository"


E:\Comp Science- workspace\Fun_With_Functions_Project>**git remote add origin http
s://github.com/rymerj/Fun_With_Functions_Project.git**

E:\Comp Science- workspace\Fun_With_Functions_Project>**git push -u origin master**
Username for 'https://github.com': rymerj
Password for 'https://rymerj@github.com':
Counting objects: 8, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.14 KiB | 0 bytes/s, done.
Total 8 (delta 0), reused 0 (delta 0)
To https://github.com/rymerj/Fun_With_Functions_Project.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

E:\Comp Science- workspace\Fun_With_Functions_Project>

5. Add, commit, and push


E:\Comp Science- workspace\Fun_With_Functions_Project>git add .

E:\Comp Science- workspace\Fun_With_Functions_Project>git commit -m "added instr
uctions"
[master 2e54188] added instructions
 1 file changed, 117 insertions(+)
 create mode 100644 Start_A_New_Project_Instructions.md.txt

E:\Comp Science- workspace\Fun_With_Functions_Project>git push
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': rymerj
Password for 'https://rymerj@github.com':
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.72 KiB | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/rymerj/Fun_With_Functions_Project.git
   39d39af..2e54188  master -> master

E:\Comp Science- workspace\Fun_With_Functions_Project>