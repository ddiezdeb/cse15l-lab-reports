Below is a list of command (step by step ) I used to clone the repository from github, use vim to correct a file, and 
then add, commit and push my changes back to github.

`ssh cs15lfa23pl@ieng6.ucsd.edu`  This command takes me to the ieng server

`git clone git@github.com:ddiezdeb/lab7.git` This command clones the repositiory onto the server

`cd lab7` This changes the current directory to the lab7 directory

`ls` I used this to see what files are within the labt directory

<img width="569" alt="Screenshot 2023-12-03 at 3 01 13 PM" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/165d8f15-1009-4928-b315-3fc5a5707380">

 Here is a picture of the point in the terminal before pressing `<tab>`

`vim List<tab>` The tab command autocompleted the name of the file as far as possible without guessing which of the List*.java files I wanted to open.

<img width="563" alt="lab4pic2" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/e1b388ee-4e95-4f77-ae52-c36b9b1e91b4"> 

Here is a photo of what the terminal looked like after typing `vim List<tab>`


<img width="567" alt="Screenshot 2023-12-03 at 3 04 51 PM" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/d50c9abc-c119-47b6-8ec9-6e38475b0981">

I completed the line by typing .java in order to take me to the appropriate file.


Then vim opened it up in the terminal in a format that I could edit since vim is a text editor.
<img width="570" alt="lab4pic3" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/00e5b84b-34af-4625-a23b-c595c41575e1">

`<Shift-G><up arrow><up arrow><up arrow><up arrow><up arrow><up arrow>` to navigate to the  appropriate line where shift-G takes me to the bottom of the file and I then move up 6 lines.

` e r 2` I replaced the last character of the first word on that line with 2. Where e takes me to the end of the next word r is to replace the last character of that word and 2 was the character I replaced it with.
<img width="561" alt="Lab4pic4" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/8740a204-ea36-410c-9260-1b09aa71af33">

`:wq<enter>` This command writes and quits, saving changes that I made to the file and exiting back to the terminal
<img width="574" alt="Screenshot 2023-12-03 at 3 09 07 PM" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/06c620d9-1669-408d-a605-f08e731ccfc1">

`git add .<enter>` This adds files I made to the branch

`git commit -m “fixed ListExamples.java”<enter>` This commits the changes and -m indicates that the next field between quotes is the message you will see in the repository describing the changes made.

`git push<enter>` Finally I push it back to the repository so that all of the changes I made on the terminal are now saved to the repository on github.

<img width="559" alt="Screenshot 2023-12-03 at 3 12 38 PM" src="https://github.com/ddiezdeb/cse15l-lab-reports/assets/147003235/d1a09cc2-a10e-4c1e-8b27-ce57364ecf12">



