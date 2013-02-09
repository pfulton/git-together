git-together
============

Let's all learn Git together!


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