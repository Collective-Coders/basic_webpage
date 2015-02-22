# basic webpage

# installation

Before you can do anything, make sure you have 'git' installed.  To check if git is installed, go into your terminal and type:
    
    git --version

If you see something like:

    git version 1.9.3 (Apple Git-50)
    
then you are good to go.    

### step one: preparing your computer

Before you install this project, you should make a folder for your personal-coding projects.  In the terminal,
navigate to your Documents directory.  There, create a new folder, like so:

```
Macbook:~ Max$ 
Macbook:~ Max$ cd Documents
Macbook:Documents Max$ ls
Orbits    	    School              finances
Work Logs       Personal Projects

Macbook:Documents Max$ 
Macbook:Documents Max$ mkdir Code_Projects
Macbook:Documents Max$ 
Macbook:Documents Max$ ls
Code_Projects		Orbits              School  
finances        Work Logs           Personal Projects	
			
Macbook:Documents Max$ 
```

You can create folders using the Finder as well, but it is GREAT practice to use the terminal when you can.


### step two: downloading this project

Once you have a place for putting your coding projects, the next step is to download this project onto your computer.  Continuing from above:

```
Macbook:Documents Max$ 
Macbook:Documents Max$ cd Code_Projects
Macbook:Code_Projects Max$
Macbook:Code_Projects Max$ ls

Macbook:Code_Projects Max$ git clone https://github.com/Collective-Coders/basic_webpage.git
Cloning into 'basic_webpage'...
remote: Counting objects: 8, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 8 (delta 1), reused 7 (delta 0)
Unpacking objects: 100% (8/8), done.
Checking connectivity... done.

Macbook:Code_Projects Max$ ls
basic_webpage

Macbook:Code_Projects Max$ cd basic_webpage
Macbook:basic_webpage Max$ 
Macbook:basic_webpage Max$ ls
README.md	  index.html	  index.js	  styles.css
```

After going through the commands above (the main one is the 'git clone ...' command) , you should now have a 
copy of this project saved onto your computer.  You are now ready to work on this project, locally.

## 'Pushing' your code on Github

Let's say you just finished writing some new logic for your webpage!  Maybe you just added
logic for a button, or some code to manipulate a canvas object, on screen. There are a few
steps to pushing your code to github.
```
Macbook:basic_webpage Max$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes not staged for commit:

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

Macbook:basic_webpage Max$ git add index.html
Macbook:basic_webpage Max$ git commit -m "changed the sidebar text"
[master 8fd2c1b] changed the sidebar text
 1 file changed, 1 insertion(+), 1 deletion(-)

Macbook:basic_webpage Max$ git push
Counting objects: 6, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 319 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
To https://github.com/Collective-Coders/basic_webpage.git
   5b3acbf..8fd2c1b  master -> master

Macbook:basic_webpage Max$ 
```

I omitted some text above, so your console output WILL look slightly different, but if
you see mostly the same messages, then you are good to go!  If something goes wrong,
read the console output! You can always google an error message to find a solution!

## 'Pulling' the latest code from Github

    Coming soon!

## Extra Stuff

### Some Useful Commands

```
git init                                // use this command when first running git on a folder
git status                              // use this to see which files you'll want to commit
git add                                 // use this command to mark files to be sent to github
git commit -m "enter message here"      // use this command to prepare a group of files to be sent to github
git push                                // use this command to push all commits to github
git pull                                // use this command to pull the latest code from github
```

## Some interesting articles and sites, when you are ready
[The git Manual](http://git-scm.com/doc)

[The BEST way to learn about the html5 canvas](http://diveintohtml5.info/canvas.html)

[CSS Tricks, a great site for learning, well, CSS tricks](http://css-tricks.com/)

## Links to popular frameworks!

[AngularJS](https://angularjs.org/)

[JQuery](http://jquery.com/)
