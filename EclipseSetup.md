These steps will guide you through getting eclipse and connecting to the example
repository.

1. [Download Eclipse installer.](https://www.eclipse.org/downloads/download.php?file=/oomph/epp/oxygen/R/eclipse-inst-win64.exe)

2. When it is done downloading, run it.

3. Select *Eclipse IDE for Java Developers*.

4. Click *Install*. It will take a while to finish.

5. Once it is done, click *launch*.

6. You will be prompted to select a workspace folder. This is where all your 
files and settings for programming will be stored. The default folder is okay.

7. Once you have selected a workspace folder, you will be greeted with the 
Eclipse welcome screen, which contains some links to projects and tutorials 
related to Eclipse. You can skip this and click the *workbench* button in the 
top-right.

8. You will be presented with the Java perspective of Eclipse. On the right-hand
side, you can click the X on the *Task List* view, since this will not be
necessary for our project.

9. It is time to install some plugins to allow us to code the robot. Under the
*Help* menu, click *Install New Software*, near the bottom. The name is slightly
confusing in that this allows you to install extensions and plugins for Eclipse,
but does not allow installation of seperate programs. 

10. When the *Install* window appears, paste the WPILib update site URL
[http://first.wpi.edu/FRC/roborio/release/eclipse/](http://first.wpi.edu/FRC/roborio/release/eclipse/)
into the box that says *type or select a site* and press enter.

11. Eclipse will retrieve a list of plugins available from the site. Once this 
is complete, one category should show up on the list, *WPILib Robot Development*.
Click the arrow next to this to expand that category.

12. Select the check box next to *Robot Java Development*, and then click *Next*
and then *Next* again.

13. Agree to the license agreement without reading it and click *Finish*.

14. It might give you a security warning asking whether or not you trust the 
author(s) of the plugin. Click *Install anyway* to continue installing the 
plugin.

15. Once the plugin is installed, you will be asked if you want to restart 
Eclipse. Click *Restart Now*.

16. Once Eclipse has restarted, you will see the welcome screen again. (This
will keep happening until you load up a project to edit.) Again, click the 
*Workbench* button.

17. Now it is time to connect to the club's Git repository on GitLab. To do
this, click *File > Import*.

18. In the popup that appears, expand the *Git* category and click *Projects
from Git*. Click *Next*.

19. Select *Clone URI*. This means that Eclipse will ask you for the URI (or the
URL in our case) of a Git repository, and will use it to connect to that
repository. Click *Next*.

20. You will be presented with several fields that need to be filled in. For the
URI, put [https://gitlab.com/frc-5669/test-project.git](https://gitlab.com/frc-5669/test-project.git).
This is the URL for a test project where we can get to know Java and Git before
writing the code for the robot. By entering this URL, the *Host*, *Repository
path*, and *Protocol* fields should be automatically filled in.

21. Enter your username (not your email) and password that you used when signing
up for GitLab and press *Next* four times (wait for each screen to finish
loading before pressing *Next* again) and then press *Finish*.

22. The project will appear in the *Package Explorer* view on the left hand side
of the screen. Click the arrow next to it to view the files inside of it. From
there, click the arrow next to the *src* folder (an abbreviation for Source
Code) and then the arrow next to the *edu.boscotech.frc* package. You will see
one file inside, *Main.java*. Double-click to open it, but do not edit it yet.

23. To make sure that your edits do not conflict with other people's edits and
vice versa, you will create a 'branch' where you can make edits to the code
without interfering with other branches. To do this, right click the project
in the *Package Explorer* view, and click *Team* > *Switch To* > *New Branch...*

24. For the branch name, pick something unique and descriptive. Since we are
creating one branch for each programmer, you can just use your name. Click
*Finish* after choosing your name.

25. You will notice that the project name, in square brackets, has the name of
the Git repository it is connected to as well as the name of the branch you are
currently on. It might look something like *Test Project [test-project 
your-name]*. Now you can make some changes to the *Main.java* file!

26. Once you have made some changes, make sure to save the file by pressing
ctrl+s. If you ever have unsaved changes, an asterick will appear next to the
file name. Once you press ctrl+s, this should go away.

27. Now it's time to *commit* and *push* your changes. When you save a file with 
ctrl+s, it only saves the changes to your computer. To update the files in the
repository, you must describe your changes with a *commit* and then *push* the
commit to the repository. To do this, right-click your project and select *Team* 
\> *Commit...*. A view will appear called *Git Staging*. It might be in an 
awkward spot, so feel free to drag it by the title tab to a different section of 
the user interface.

28. On the left of the view, you can see which files have been changed and need
to be committed. On the right hand side of the view, you can write a message
describing the changes you made. It is good practice to make this descriptive 
and not something vague like 'I made changes'. It is also good to put a brief
description of what you did on the first line, leave the second line blank, and
write any extra details on the following lines.

29. Once you have written a description of the changes you made, press *Commit
and Push...*. Since you had previously created a new branch, a popup might
appear with advanced settings for your newly created branch. You can ignore this
and press *Next*. It will ask you for your GitLab username and password again to
finish creating your branch.

30. Once the branch setup is finished, you will be shown a list of commits that
will be pushed to the repository. Click *Finish*. It will ask you for your
GitLab username and password again, to push your commits to the repository.

31. Once the push has finished, a popup will show up informing you of the 
results. As long as none of the items in the list (there is usually only one)
has the word 'error' in it, it worked fine, and you can click *OK* to close the
popup.

32. You can now make more changes and commit them again in the same way. You
will only have to enter your username and password once now, since previously
the creation of the new branch required seperate setup and an additional login.
