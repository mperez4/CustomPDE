#Customize your Processing Development Environment

This tutorial will show you how to customize your Processing IDE by changing the background color, tab colors, default banner, etc etc.

======
##Package Contents

Most executable applications in Mac OS X are organized in a folder called `contents`. Developer information, Resources, Plug-ins and dependent files are stored in there for the app to run properly. In this tutorial, we will be editing the design content only! YOU ARE AT YOUR OWN RISK IF YOU CHANGE ANYTHING ELSE. 
For this example, I am using Processing 2.1 and we will be editing the Processing JAVA mode only, though the same applies for Javascript mode, found under in your `Documents/Processing/modes` folder.<br />
<br />
The first thing we need to do is navigate to the Processing package contents. Right click on your Processing.App and click on `Show Package Contents`.
This will take us to the brains of Processing, where all the juices are stored.

![Alt image](images/OpenpackageContents.jpg)
Once we open the Package Contents, we can see the way in which Processing is organized internally. We can find all the images and text files in which the IDE is designed with. We will begin to change the physical appearence of Processing, primarily the colors of the IDE.  Open the file `theme.txt` found under `Contents/Java/lib/`. I use TextEdit to edit the file, though you can use whatever editor you want. 
![Alt image](images/layout.png)
This theme.txt file contains all the colors used to make the default IDE, and we can simply change those colors by pasting in our preferences.