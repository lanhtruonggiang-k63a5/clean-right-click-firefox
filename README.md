# clean-right-click-firefox
remove those unwanted option when rightclick

# how to ???
1.Enable the Stylesheet Switch

    Open Firefox and type about:config in the address bar.

    Click "Accept the Risk and Continue."

    Search for: toolkit.legacyUserProfileCustomizations.stylesheets

    (maybe need to change to boolean ?? )

    Double-click it (or click the toggle button) to set it to true.

2.The Setup
    
    Open about:config and set toolkit.legacyUserProfileCustomizations.stylesheets to true.
    
    Go to about:support. Find Profile Folder and click Open Folder.

    (maybe can't find the cause you using (or used to) multi profiles?? 
        -> NUKE OPTION !!! : search profiles.ini whole PC. 
        -> Inside Profiles/One-of-these-are-default-profile/
    
    Create a new folder named chrome inside the profile folder.

    Inside chrome, create a text file named userChrome.css.

    Paste file content 

3.The Final Step: Restart
    
    Close Firefox completely.
    Open it again.
