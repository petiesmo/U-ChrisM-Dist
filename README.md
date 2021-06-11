# U-ChrisM-Dist
 TinifyAPI program to share

 Executable (.exe) runs a small dashboard with the following buttons:
 -> RUN
 -> RUN MANUAL
 -> SETUP
 -> QUIT
 Status bar at the bottom

 The program is initially 'Paused' (as indicated in the status bar)
 On your first run, click 'SETUP' to:
 1. Add your API Key
 2. Test your API Key
 3. Add/Remove folders to be monitored
 4. Define a unique file tag for the Tinified file (Default: '_sm')
 5. Adjust settings as necessary (Include Subfolders; Delete original file)
 6. 'CANCEL' will discard your changes and return to the main window
 7. 'APPLY CHANGES' takes you back to the main window 
 8. (Note: Apply Changes will be inactive if there is not at least one folder defined AND at least one File Type selected)

 Anytime you go to SETUP, the main program loop gets paused.  You will need to hit 'RUN' to resume.
 
 'RUN' Monitors for the creation of new files in the folders defined during Setup (or copy-paste into the folder).
 'RUN MANUAL' will launch a Folder selection popup.
 - Upon picking your folder, the program will loop through all applicable files inside that folder (no recursion/subfolders)

Originator for Questions/Support: @petiesmo (Github)

 
