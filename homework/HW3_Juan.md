# Homework Three

Fill out this worksheet (it can be opened in a plain text editor, like TextEdit [Mac] or TextWrangler [Mac] or Notepad [Windows]. Commit and push it to your copy of the course repo. I will pull your copies Friday at 5, and try to have comments for you by next class period, when we will discuss them. 

Feel free to work in groups, and discuss the assignments as needed. However, I do expect you to turn in your own copy, with answers in your own words. Feel free to try the commands in the answers - you don't have to do this from memory.

1. Matching: On LONI, when I log in, I am located in my _b_. I should store my data in the _a_ system, 
which has a 60 day storage limit. I should run computations in the _a_, and not in the _b_.

	a. /work/  
	b. user home

2. If I wanted to view the files in my home directory, but I am located in my work directory, I would use:  
	a. ls  
	b. ls -F  <<< but we have to add the name of the home directory  
	c. ls ~/

3. In your own words, what does the correct command in question two do?

List the files in the current directory sorted in aplhabetical order 

4. In what order do we use the following commands: git push, git add, git commit? In your own words, what does this series of commands do? 

First add to make the interface pay attention to the file in question, then commit to actually make the 
changes to the file we're interested in doing something to and, finally push to make a push request to merge 
our file with the origin.

5. This series of commands will not work. Can you spot the issue? Tell me what goes wrong here, and why.

```
mkdir my_project
cd my_project
mkdir data output scripts
nano readme
git add readme
git commit -m "adding my readme file!"
git push
```
What goes wrong is that the my_project directory has not been initialized as a .git repository and the add, 
commit & push commands wont be recognized by the git push program
