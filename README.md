# MGG-HTML-CSS
A respository for material for the September 2017 intro to HTML/CSS/Github event

To set up git on your computer, see Github's instructions here: https://help.github.com/articles/set-up-git/

To set up a copy of these files on your own GitHib account, the easiest way to do this is to:

* Download the files by clicking on Clone or Download then Download Zip
* Create a repo in your own GitHub account: Click on the + by your profile picture, and then click on Create New Repository
  * Give it a name and a URL
  * Check the box next to Initialize this repository with a README
* Copy the URL on the next screen (It will be in the format https://github.com/GemHill/test.git )
  * Go to a terminal, type `cd Desktop` to move to your computer's desktop (or  `cd Documents`, or another folder)
  * Type in `git clone <URL you copied>`
This will set up a folder for your repository on your computer
* Copy and paste the files for your site into the new folder (this can be done however you normally move files)
* In your terminal, type `git status`
This should show you a list of files in red. This is expected
* Type `git add .`
  * You may see a message asking you to write a commit message. Write a message describing what you've added (or committed) to the repo. 'Initial commit' is fine here. This will add your files to the git respository
* Make changes to the files on your computer, and save as you would normally
* In the terminal, make sure you're in the new directory `cd <repository name>`, then try git status
 * You should see a message about there being some changes not staged for commit.
* Type `git add <filename>` or `git add .` to add all files
 * You can type `git status` again here, which will tell you that there are changes to commit
* Type `git commit -m "describe your change here"`
 * You can type `git status` again here, which will tell you to push your changes
* Type `git push` 
 * You may be asked to enter your GitHub undername and password here
* Type `git status`, you should see the following message 
> On branch master
> Your branch is up-to-date with 'origin/master'.
> nothing to commit, working directory clean
