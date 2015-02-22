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

# Pulling from github
