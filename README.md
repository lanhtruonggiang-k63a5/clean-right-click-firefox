# clean-right-click-firefox
remove those unwanted option when rightclick
# how to ???
>1. Enable the Stylesheet Switch

    Open Firefox and type about:config in the address bar.

    Click "Accept the Risk and Continue."

    Search for: toolkit.legacyUserProfileCustomizations.stylesheets

    Double-click it (or click the toggle button) to set it to true.

2.The Setup:

    Open about:config and set toolkit.legacyUserProfileCustomizations.stylesheets to true.

    Go to about:support. Find Profile Folder and click Open Folder.

    Create a new folder named chrome.

    Inside chrome, create a text file named userChrome.css.

    Paste file content 

3. The Final Step: Restart

Firefox only reads the userChrome.css file when it launches.

    Close Firefox completely.

    Open it again.
