# Installing and Using GitHub Desktop

### Follow the instructions below for installing and using GitHub Desktop

1. [Click here to install GitHub Desktop](http://desktop.github.com)

2. Ater installing, bring up GitHub desktop on your local computer

3. Click on **Clone a Repository**

4.  In the window that opens, enter the following:

    + **URL:** 1010Robotics/2017-2018-1010_  (Replace "_" with your team letter, "A" or "B" or "C" or etc....

    + Select **local path** (a folder on your computer) where you want to clone the files.

    + Click on **CLONE**

5.  **NOTE:** Before working on any of the files in this folder:

    + In GitHub Desktop...**FIRST** click on **Fetch origin** (this syncs your local folder with the contents of your team repository on GitHub.com)

6. Then go ahead and modify the contents of your local folder (add/delete/modify the files as needed)

7. Any changes to the files on your local folder will show up (after a few seconds) in GitHub Desktop. 

8. To **PUSH** the changes back to your team repository on GitHub.com...

    + In GitHub Desktop....in the lower left corner, enter a **clear explanation** of the changes you made.

    + Click on the blue button **Commit to master**

    + Click on **Push Origin** in the top bar.

The additions/deletions/modification on your local computer will now be synced with your team repo on GitHub.com.


# FAQs

## "Installation has Failed" Error

If you get the error **Installation has failed.**  *There was an error while installing the application. Check the setup log for more information and contact the author.*

Your setup log file will probably contain something like this:  

          *System.ComponentModel.Win32Exception: The specified executable is not a valid application for this OS platform*

It means that yours is a 32-bit OS, but the current version of GitHub Desktop only supports 64-bit OS installations. You may want to consider getting a computer with a 64-bit OS.

More details are provided in the following thread that discusses supporting 32-bit OS in the future:

https://github.com/desktop/desktop/issues/1214





