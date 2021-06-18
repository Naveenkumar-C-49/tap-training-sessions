# Morining Session

## Version control:

	* allow us to store multiple version of system file in the remote repo
maintain snapshot of your changes

## Distributed version control system - we use

* have the entire copy of code in their local system
* commit,update -> local repo
* push,pull or clone -> remote repo
* workflow -> pull -> update -> commit -> push or merge

> Example : Gitlab,Github(first used for linux) - Microsoft, Bit Bucket - Atlasian code commit - AWS amazon

## Github -exe
	install git by go to github-scm.com
	for checking type 'git --version' in cmd prompt
	if not working means - please use git bash

## Github web login
	create account- using invite email
	enter a name,byju's mail id, password
	download backup codes
	enable 2FA
	check for organization or contact administrator

## Add config in git
	add name, email
	git --config --global user.name ''
	git --config --global user.email ''
	to check git --config --list
	check by - git --config --list

## Create workspace
	create workspace - tap-workspace
	create folder - tap-application
	type git init	
	to check in git-bash - type ls -ltra

## Add readme.txt file, modify and commit it
	to add file to staging area - git add --all, git add <list>OO
	to check status - git status
	to commit - git commit -m '  '
	to check log - git log
## Demo
	echo "# tap-application" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/Naveenkumar-C-49/tap-application.git
	git push -u origin main - use it in power shell or comand prompt if git bash struck
	use chrome for authenticate git authenticate manager
## Modified README and Add LICENSE file
	git init
	git add --all
	git commit -m "Modified README and Add LICENSE"
	git push

## Modified README file with Example Code
	git init
	git add --all
	git commit -m "Modified README file with Example Code"
	git push

# Afternoon Session

## Git collabration - Fork
	Go to the Common Repo you have to fork and collabrate
	Click the Fork option in top right corner
	You got the repository in your repositories tab
	Add a new file if you want
	Commit the changes with valid message
	Note that: you have a pop up above repo that 'you commit ahead of main repository'
	click Contribute and new pull request
	Add comments and create pull request
	Wait for reviewer to review and commit the changes to main repo

## Git collabration - Branch
	Go to the Common Repo you have to create branch by typing the name
	You got the branch below main
	Add a new file if you want or update it
	Commit the changes with valid message
	Note that: you have a pop up above repo that 'you commit ahead of main repository'
	click Contribute and new pull request
	Add comments and create pull request
	Wait for reviewer to review and commit the changes to main repo

> Note : After branching, if you want to fork check for upstreams
 
## Git collabration using VS code
	
	Download VSCode
	Do Git clone of the `git clone https://github.com/ByjusTAP/tap-collaboration.git` repository 
	Open the repository in the VsCode
	Switch the branch to your own branch
	Make modification of the files
	Go to source control and commit/push the changes


	
		





