# Git Together

Let's all learn Git together!

Git is sometimes difficult to understand, especially if you're not in a team setting. So, let's use this repository to play around with Git and learn by doing!

You really can't do anything "wrong". Clone it, change files, change parts of files, delete files, add files, rename files, whatever! Hopefully, we'll all learn something by playing with this project.

It's probably best to start here: [Set Up Git](https://help.github.com/articles/set-up-git)

* Twitter: [@patrickfulton](http://twitter.com/patrickfulton) & [@joshsager](http://twitter.com/joshsager)

<h2>Here are some quick tips:</h2>
<h3>Creating a New Repository Via the Command Line</h3>
<pre>
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/joshsager/WebStartingFiles.git
// you might have to try the ssh approach 
git remote add origin git@github.com:joshsager/WebStartingFiles.git
git push -u origin master          
</pre>
<h3>Common git commands</h3>
<pre>
// copies repository to your local drive          
git clone git@github.com:joshsager/WebStartingFiles.git   
// reports the status of your local repo    
git status
// adds all changed files to the working directory
git add -A 
// commits to the staging area
git commit -m "your message"
// pushes to the repository on github
git push
// shows the log of changes
git log
// Removes a file from staging
git reset         
</pre>
<h3>Common Linux commands</h3>
<pre>
// creates a file
touch index.html
// creates a directory
mkdir css
// Changes to inside a directory
cd css
// Changes to go up a directory
cd ../
// Copies the contents of the file to the clipboard
clip index.html
// Copies the directory and all of its contents to another folder
cp -r css/stuff css/newstuff
// Hard delete and will not prompt you
rm -f index.html
</pre>
<h3>Tips for Writing Commit Messages</h3>
[Here's a useful note on writing commit messages, and in what tense you should write them](http://stackoverflow.com/questions/3580013/should-i-use-past-or-present-tense-in-git-commit-messages)