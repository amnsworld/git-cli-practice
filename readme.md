1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
	Ans: case 1:  git status
		case 2: by typing ( ls -a ) command. If the directory contain .git folder then its a git repository. 

2.  Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
	Ans:  git add hello-world.txt
		 git commit -m “hello-world.txt file is committed”

3. Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.
	Ans:  git diff readme.md
