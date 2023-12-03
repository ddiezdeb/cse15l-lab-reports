Below is a list of command (step by step ) I used to clone the repository from github, use vim to correct a file, and 
then add, commit and push my changes back to github.

`ssh cs15lfa23pl@ieng6.ucsd.edu`  This command takes me to the ieng server

`git clone git@github.com:ddiezdeb/lab7.git` This command clones the repositiory onto the server

`cd lab7` This changes the current directory to the lab7 directory

`ls` I used this to see what files are within the labt directory

`vim List<tab>.java` The tab command autocompleted the name of the file and vim opened it up in the terminal in a format that I could edit.

`<Shift-G><up arrow><up arrow><up arrow><up arrow><up arrow><up arrow>` to navigate to the  appropriate line where shift-G takes me to the bottom of the file and I then move up 6 lines.

` e r 2` I replaced the last character of the first word on that line with 2. Where e takes me to the end of the next word r is to replace the last character of that word and 2 was the character I replaced it with.

`:wq<enter>` This command writes and quits, saving changes that I made to the file and exiting ack to the terminal

`git add .<enter>` This adds files I made to the branch

`git commit -m “fixed ListExamples.java”<enter>` This commits the changes and -m is the message you will see in the 
repository describing the changes made.

`git push<enter>` Finally I push it back to the repository so that all of the changes I made on the terminal are now saved to the repository on github.
