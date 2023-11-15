Below is a list of command (step by step ) I used to clone the repository from github, use vim to correct a file, and 
then add, commit and push my changes back to github.
```
git clone git@github.com:ddiezdeb/lab7.git
cd lab7
ls
vim list<tab>.java
<Command-G><up arrow><up arrow><up arrow><up arrow><up arrow><up arrow>
 e r 2
:wq<enter>
git add .<enter>
git commit -m “fixed ListExamples.java”<enter>
git push<enter>
```
