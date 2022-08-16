# feat: Github Day 1 commands 

1. make a repository 
If you want to make a new repository, 
look above the right side of Github hompage. 
There is a '+' button, if you click that, there are drop-downs 
and you can find a 'new repository'
Just click it.
After you click that, there will be a screen with insert informations.
Name, explanation and you have to check the README file. 
I don't know why but teacher insists to click it.

2. Copy the repository
If you finish process no.1, you have a repository in Github successfully.
AND we have to clone that. 
ACTIVATE Gitbash, go to the directory that you want to copy the repository.
you can go with these codes "cd Documents/ dev/ "
If you want a new directory enter "mkdir (directory name)"
After you enter the wanted directory, there is a code toggle on the Github repository.
You click the code, there are drop-downs with name "clone" literally.
And there is a icon looks like a two squares with hugging. 
Click it then your repository's address will be copied. 
AND we can go to the next step.

3. Cloning the repository
Right after you finish the process no.2, 
you have to back on Gitbash, and 
enter this phrase "git clone (repository address)"
then you could see in your finder that repository clone is made. 

4. Making a file to record on. 
After you did process no.3, you have to make a file to write on! 
Enter this pharse "touch (file name).file format"
I made a markdown file to write these so i type "touch 220816-commands.md"

5. Open the file and write!
If you make a file, and you can begin to write!
open the file with this code "vi 220816-commands.md"
If you have no error until now, 
you will see the weird screen with "~" these things.
if you see that, you are doing right till now so be proud of yourself :)
When you're enter the first this screen it is in 'normal mode'
AND you can enter the so-called insert mode with press 'i'
If you press i, there popped up the string "-- INSERT --"
And your file is ready to write down. 

6. Save and Get out of insert screen
If you write enough or you think it is finished, 
you have to save it and get out from that screen.
Press 'ESC' and you enter to 'normal mode'
there will be no "-- INSERT --" string anymore.
AND press shift + :, wq and press enter.

7. check the git status
After you finish process no.6
you can see the initial screen when you activate gitbash first.
If you write or change sth on file, i think you want to check it
type the code "git status', 
then if you did right, you can see the phrase "nothing added to commit but untracked files present (use "git add" to track)"

8. ADD and COMMIT file! 
If you finish the process no.7,
you enter the code "git add filename.fileformat"
and you have to check the status again with code "git status"
you could see the comment "Changes to be committed" 
SO you type the code "git commit", you could see the comment "1 file changed, 1 insertion etc"

9. Push! Push!
IF YOU FINISH THE ALL PROCESS ABOVE, you have to push to the github.
Before that if you want to check the comments that you wrote. 
Please type the code "cat filename.fileformat" 
you could see the all strings you wrote.
Back on the main theme, if you type the code "git push origin main", 
you can push the file context on Github! 
And ALL PEOPLE CAN SEE THAT YOU WROTE LOL!!!
