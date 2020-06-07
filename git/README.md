# Commands for CMD interfase (Terminal)

| Command | Explanation |
|  ---    |     ---     |
|    cd   |  allow us to move around local machine files \ change directory.| 


**cd ./** \- current directory.

**cd ../** \- go to previouse in the tree of file system directory. 

**Example:**

before 'cd ../'

-Previouse Directory

-Current Directory <-- cd we here

after 'cd ../'

-Previouse Directory <-- now we here

-Current Directory

| Command | Explanation |
|  ---    |     ---     |
|    ls   |  allow to view all files in current directory. Mean list all files| 


# Version Control GitHub clone

To start - create a [GitHub](https://github.com) account. GitHub - is just a web site with allow as to store git repositories on the internet. It's give you
and people all around the world access to git repositories that you can look at repositories that other people have created and
contribute to them or use them and such that you can work on your own projects, push them to GitHub so that your collaborators or 
other people on the internet can also see and use and work on those projects as well.
The first thing what we will to do is we will create an repository. So in the upper right of GitHub(GH) screen we have the plus button
and we can go to the new repository. This takes us to the page where we can create a brand new repository. You can name the repository 
however you want and click "Create Repository". Now GH create for us repostiory on it's servers and provide a link to new created 
repositry. So for now our repostiory not at our PC but it's a moment thing to fix. 

The first step in git is ***git clone <repository url>*** command. This command download a copy of the repositry to local machine. To do 
so we will put HTTPS link provided by GH in command ***git clone https ://github.com/nameOfYourRepository.git*** and clone repositry to 
our local machine. As you already guess we work with git in terminal or CMD. But all manipulation described here was made in terminal.

Main things what git allow you to do:
-Keep track of changes to code;
-Synchronizes code between different people;
-Test changes to code without losing the original;
-Reverting back old version of code;

Don't be surprosed that repository which is cloned and brand new created is empty. So in terminal you will see only empty folder with an 
repository name.

# Prepare local repository before push

To push file to our brand new created and cloned repository we need to relocate to our cloned repository using command "cd".
```bash
cd ./nameOfYourRepository
```
And then let's create a html file "hello.html". To do so open vim. Press key button 'I' - which mean insert mode. Write the next code:
```html
<!DOCTYPE html>
<html>
	<head>
		<title> My Webpage! </title>
	</head>
	<body>
		Hello world!
	</body>
</html>
```
Save file by pressing next algorithm of actions:
1. Press 'Esc'.
2. Press ':'.
3. Write wq letters which mean w - for write and q - quit. First save all putted in text and second exit the vim text editor.
   
Now we have hello.html in our local machine. We need to inform git to include files in next commit. To do so we need use a command
**git add** - this command alow to add one or all files and folders. To add our one file we will write in command line:
```bash
git add hello.html
```
To add all files and folders in current place we can list names of files we want to add to our next commit or just put the dot:
```bash
git add .
```
OR
```bash
git add hello.html OtherNameOfFile.c
```
Next step is to use commit. It just fancy way of saying take a snapshot or the repository in the current moment in our local machine
and save it. And it will work in the next way:
```bash
git commit -m "Any message with help tp understand what changes applied to this snapshot. To find it later."
```
This command followed with flag: "-m" - this flag for message and it's required. And we have "" quatation marks that nested some 
English message describing what it is that I've hanged in this commit, describtion that's happened in this change that makes a 
difference from previouse verion of this code. It will help to return to best working version of your project.
You need to know that git add . and git commit -m "text here" are doing snaps in your local machine repository. You didn't share your
work with server. So if anything crucial will happened with your HDD or SDD and you didn't push all changes to server. All your 
work with files will be lost. So don't hesitate to push changes to your server repository GH.


| Command | Explanation |
|  ---    |     ---     |
| git status  |  simple command that just tells you what's currently going on in your repository. |
Use this command to refresh your memory if your forget whether you have made new commit since the last time you checked from GH e.t.c.

# How to push all our changes to GH repository

| Command | Explanation |
|  ---    |     ---     |
| git push  | send all commits to GH server in linked repository. |
This command allow to push all our commits (snaps) from local computer to repository. Now our GH repository will have a content.





