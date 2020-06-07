# Commands for CMD interfase (Terminal)

| Command | Explanation |
|  ---    |     ---     |
|    cd   |  allow us to move around local machine files \ change directory.| 


**cd ./** \- current directory.
**cd ../** \- go to previouse in tree of file system directory. 

**Example:**
before 'cd ../'
-Previouse Directory
	-Current Directory <-- cd we here
after 'cd ../'
-Previouse Directory <-- now we here
	-Current Directory

| Command | Explanation |
|  ---    |     ---     |
|    ls   |  allow to view all files in current directory.| 


# Version Control GitHub clone

To start - create a (GitHub)[https://github.com] account. GitHub - is just a web site with allow as to store git repositories on the internet. It's give you
and people all around the world access to git repositories that you can look at repositories that other people have created and
contribute to them or use them and such that you can work on your own projects, push them to GitHub so that your collaborators or 
other people on the internet can also see and use and work on those projects as well.
The first thing what we will to do is we will create an repository. So in the upper right of GitHub(GH) screen we have the plus button
and we can go to the new repository. This takes us to the page where we can create a brand new repository. You can name the repository 
however you want and click "Create Repository". Now GH create for us repostiory on it's servers and provide a link to new created 
repositry. So for now our repostiory not at our PC but it's a moment thing to fix. 

The first step in git is ***git clone <repository url>*** command. This command download a copy of the repositry to local machine. To do 
so we will put HTTPS link provided by GH in command ***git clone https://github.com/nameOfYourRepository.git*** and clone repositry to 
our local machine. As you already guess we work with git in terminal or CMD. But all manipulation described here was made in terminal.

Main things what git allow you to do:
-Keep track of changes to code;
-Synchronizes code between different people;
-Test changes to code without losing the original;
-Reverting back old version of code;

Don't be surprosed that repository which is cloned and brand new created is empty. So in terminal you will see only empty folder with an 
repository name.



