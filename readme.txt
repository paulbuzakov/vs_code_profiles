1. Create new folder for new VSCode profile
2. In the new folder create 2 folders: "data" and "extensions"
3. Move settings.json file in folder [NEW_FOLDER]/data/User

4. Create *.lnk file with additional arguments:

"C:\Users\Paul Buzakov\AppData\Local\Programs\Microsoft VS Code\Code.exe"
    --user-data-dir e:/code_profiles/js/data
    --extensions-dir e:/code_profiles/js/extensions