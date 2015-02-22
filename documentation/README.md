### Some Useful Commands

```
git init                                // use this command when first running git on a folder
git status                              // use this to see which files you'll want to commit
git add                                 // use this command to mark files to be sent to github
git commit -m "enter message here"      // use this command to prepare a group of files to be sent to github
git push                                // use this command to push all commits to github
git pull                                // use this command to pull the latest code from github
```

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



## 'Pulling' code from Github

Pulling code from github is as easy as entering a single command! However, with that
single command you can erase all of the changes you have made to your code!  Because
of this, I'm going to hold off on writing this part of the document until further notice.

## Some interesting articles and sites, when you are ready
[The git Manual](http://git-scm.com/doc)

[The BEST way to learn about the html5 canvas](http://diveintohtml5.info/canvas.html)

[CSS Tricks, a great site for learning, well, CSS tricks](http://css-tricks.com/)

## Links to popular frameworks!

[AngularJS](https://angularjs.org/)

[JQuery](http://jquery.com/)
