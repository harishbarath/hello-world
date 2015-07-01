This file is intended to explore git as a version control system.
Is also intended to play with git commands

Here are a few useful commands to use git
1. Always initialize git first
	git init
2. Create files as required. Every file needs to be added to the repository
	git add *.c <example>
3. Once the files are added, they need to be committed to local repository
	git commit -m "<commit log>"
4. Add the newly created repository to github (which is remote server)
	git remote add origin https://github.com/harishbarath/<repositoryname>.git
5. push the repository to server
	git push -u origin master
