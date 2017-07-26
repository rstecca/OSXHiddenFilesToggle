OSXHiddenFilesToggle
====================

Small applet to add an icon to Finder's toolbar that allows to quickly show or hide hidden files.

INSTALL
====================

Download the app and store it in a meaningful location (I use an ~/Actions folder). The app should never be moved unless you want to repeat the procedure.
While holding command, drag and drop the OSXHiddenFiles onto Finder's toolbar.

USE
====================

Click on the icon in Finder's toolbar. A dialog will show up. Select HIDE or SHOW. If you are changing, Finder will automatically restart.

DEVELOP
====================

If you wish to change the code you can do in two ways:
1. Simply open the .app with Automator
2. Create a new Automator application, add one "Get Specified Finder Items" node at the top, add a "Run AppleScript" and paste the code you'll find in the src folder in the script area.

rstecca
