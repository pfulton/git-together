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
git remote add origin https://github.com/xxx-username-xxx/xxx-reponame-xxx.git 
// you might have to try the ssh approach 
git remote add origin git@github.com:xxx-username-xxx/xxx-reponame-xxx.git 
git push -u origin master          
</pre>
<h3>Common git commands</h3>
<pre>
// copies repository to your local drive          
git clone git@github.com:xxx-username-xxx/xxx-reponame-xxx.git   
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
<h1>Other Helper Guides</h1>
<ul>
	<li><a href="https://github.com/pfulton/git-together/blob/sagerworking/docs/linux.md">Common Linux Commands</a></li>
	<li><a href="https://github.com/pfulton/git-together/blob/sagerworking/docs/vi.md">vi Text Editor - Cheat Sheet</a></li>
</ul>
