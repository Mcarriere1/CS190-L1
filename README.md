# Lab 01
For this lab we will continue to explore basic command line operations. Like the in-class exercise we will be focusing command line arguments and options. The goal is to get you more familiar with the basics of using the terminal before we get into more complex examples later in the course.

# Part 1 `git`
`git` is a fundamental tool for software development. It allows developers to track changes made to the code in (hopefully) small chunks called diffs. While VSCode does have a graphic user interface for dong this as well as many other git GUI programs existing. The most common way to use git is through the command line. Git and version control are giant topics that we won't be able to cover anything but the absolute basics. For this lab we will focus on tracking new files, creating commit messages, and pushing files to a remote repository. 

## Tasks:
1. Create a new non-empty text file, it can have any content in it.
2. Execute the git command to add the new file to the list tracked changes
3. Commit the new file and add a commit message using the short option
4. Push the changes to your remote repository

Use the following website to help you find which commands to use, or google it!   
https://git-scm.com/docs

# Part 2 Compresing files with `tar` and `zip`
Sometimes we need to move or send very large files. To reduce the file size of what we are trying to move or send we can compress these files into a single compressed file called an archive. Tar by default uses the gzip compression algorithm where zip uses the aptly named Zip compression algorithm.

## Tasks:
1. Use tar to compress your text file that you created in Part 1.
2. Extract/Decompress the tar, check that the content in the text file is the name.
3. Use zip to compress your text file from Part 1.
4. Unzip the the zip archive and examine the text file again.

The size of the text file is probably not big enough to compare the compressed archives. I encourage you to try to make a very large text file and play around with the different compression options with tar but this is not required for this lab. 

# Part 3 `time`
The time program allows you to use figure out how long it took a specific program to run.

## Tasks:
1. Use the `time` command to run program.sh with an argument of 100
2. Use the `time` command to run the program.sh with an argument of 10000

What is the difference in time between task 1 and task 2?  
**[YOUR ANSWER HERE]**

# Part 4 `diff`
When working with log files or any other text files we may want to compare two different text files to see what has changed between them. For example if you run a program twice with different arguments we may want to find out what is different between each programs outputs. Please refer to the following link for details on how to read the `diff` commands output.

https://people.eecs.berkeley.edu/~bh/v2ch2/diff.html

## Tasks
1. Use the diff command to compare file_a.txt and file_b.txt

Which lines and/or characters are different between these files?
**[YOUR ANSWER HERE]**

# Part 5 `head`/`tail` `more`/`less`
Sometimes we use the terminal to view very large text files such as system logs. Printing these large text files to the terminal usually forces portions to get cut off due to the buffer size of terminal emulator. While you could increase the buffer size to fit the entire file, this is not a great solution. We can use programs like head/tail to view the top or bottom of the files then scroll up from there. more and less do similar things, more allows forward navigation and minimal backwards navigation, while less allows for both forward and backwards navigation. 
## Tasks
1. Use head to view the top few lines of the very_large_text_file.txt
2. Use tail to view the bottom few lines of the very_large_text_file.txt
3. Use more or less to explore the same file

# Deliverables
Commit and Push all files modified or created during this lab. It is especially important to push the log file found in the command_logs. If you do this over multiple days push all of the command log files. This is how I verify that you have run the commands asked.

Make sure to answer all questions asked as part of this README, look for the **[YOUR ANSWER HERE]** text.
