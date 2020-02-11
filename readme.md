1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.

Ans: case 1:  git status
		case 2: by typing ( ls -a ) command. If the directory contain .git folder then its a git repository. 

2.  Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
	
Ans:  git add hello-world.txt
		 git commit -m “hello-world.txt file is committed”

3. Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.

Ans:  git diff readme.md

4. Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.
	
Ans: git show abc123

5. Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.
	Ans:  git log --oneline -n 3	

6. Assuming that you are currently within a Git repository, write the command (or commands) that will check to see if the remote repository contains any new commits.
	Ans:  git fetch — to get data from remote
		git status — to compare local data with fetched remote data