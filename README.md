#install git on centos:
	sudo yum install git


#Create repo on git

#connect to :
	git config --global user.email "appasaheb3@gmail.com"
	git config --global user.name "appasaheb3"

#Clone in local system:
	git clone git_repo_link

#Make changes whatever you want in repo directory

#Add one or more files to staging (index):	
	git add <filename>
	
	git add *
	
	git add -A
	
	git add .

#Commit changes to head (but not yet to the remote repository):
	git commit -m "Commit message"

#Send changes to the master branch of your remote repository:	
	git push origin master
	
	local system to remote server:
	git push

#List the files you've changed and those you still need to add or commit:	
	git status


#connect to a remote directory:
	git remote add origin <server>

#Push all tags to remote repository:	
	git push --tags origin
