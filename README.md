# MGG-HTML-CSS

# Contents

1. [Set up Github pages for the first time](https://github.com/GemHill/HTMLCSS#set-up-github-pages-for-the-first-time)
2. [Edit files in an existing repo](https://github.com/GemHill/HTMLCSS/blob/master/README.md#edit-files-in-an-existing-repo)
3. [Resources, troubleshooting, and FAQs](https://github.com/GemHill/HTMLCSS#resources-and-tips)


## Set up Github pages for the first time
** You only have to do this once per repo, if you have a owrking site for your repo, you can [skip to the next section](https://github.com/GemHill/HTMLCSS/blob/master/README.md#edit-files-in-an-exisitng-repo)
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
* Go to your Github repo, and click on the Settings tab
* Scroll down to the 'Github pages' section, select master branch from the dropdown, click save
* Your site will be available at https://username.github.io/repositoryname (change username to your gitbug username and repositoryname to the name of your github repo

## Edit files in an existing repo
### Through github

If you are the owner of the github repo, then you can edit directly through Github
* In your repo, click on the file you wish to edit
* Click the pencil icon near the top right hand corner 
* You can then edit the file straight in github
* When you're done, scroll down, keep the 'Commit directly to the master branch' selected
* Click Commit changes

### Through the command line

If you want to edit the files on your computer and push them to git using the command line, you can do so
* Edit the files on your computer as you would any other file
* Open terminal and type `cd Desktop/HTMLCSS/yourfoldername` or `cd Downloads/HTMLCSS/yourfoldername` (or CD whereyourfolderis)
* Type `git status` and press enter. You should see a message about changes not staged for commit
* Type `git add .` and press enter
* Type `git commit -m "commit message here"` and press enter
  * Examples of git commit messages are `git commit -m "Added links"` or `git commit -m "Fixed typo"`
* Type `git push` and press enter
* Your changes should be live on the site

## Resources, troubleshooting, and FAQs

### Resources
* More ressources can be found in the resouce file, which can be viewed on Github
* Github has decent documentation [here](https://guides.github.com/) and google is your friend
* [Codecademy](https://www.codecademy.com/) also has git and html/css/other language resources to extend your site further

### Tips
* If you want to add another page, make another file with the extension .html (contact.html for example). Open notepad or notepad++ or sublime and create a new file, saving it as filename.html. 
   * Copy everything in [this file](https://gist.github.com/GemHill/beb4e8b802880541800b2fc9786a793e) at the top of your new page, and then put the rest of the copy in as you wish between the `<body>` and `</body>` tags
   * See the index.html file in this repo to see how to add links to pages 

### FAQs

_My changes aren't showing up!?_
* Try waiting a minute or two - it takes a while for github to catch up sometimes. Or open the page in a private window/incognito (Ususally File > New > Private/Incognito in your browser)
* Check your html has all the closing tags (`</p>` or `</h1>` for example), and your css has all the closing curly brackets ( } after every property)

_Git is doing a weird thing/nothing at all_
* If you get an error message, google that message. Someone else will have had the same issue, promise
* `Git status` as often as you want. IT will tell you want git is doing, and what you need to do


