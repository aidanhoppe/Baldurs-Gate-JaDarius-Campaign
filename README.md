# Using Github Desktop for Baldur's Gate 3 saves

This guide will walk you through the steps to sync a BG3 campaign between multiple players using GitHub Desktop.

## Steps

### Initial Setup

1. Open GitHub Desktop on your computer. (https://desktop.github.com/)

2. Sign in to your GitHub account if you haven't already.

3. Navigate to "C:\Users\\{USER}\AppData\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public\Savegames" and cast a Ctrl+c + Ctrl+v on the "Story" folder. Once Story-Copy finishes creation, delete Story (yes).

4. In Github Desktop, click on "File" and select "Clone Repository", then select the "URL" tab.

5. Enter the URL (https://github.com/aidanhoppe/Baldurs-Gate-JaDarius-Campaign) of the repository you want to clone.

6. For local path, set it to "C:\Users\\{USER}\AppData\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public\Savegames\Story". Where {USER} is replaced with the user on your computer. May need to change C -> D or whatever the name of your drive.

   - 1. Or, Press "Choose" for local path and type "%appdata%" then Enter. Then navigate back to AppData and then Local->Larian Studios\\...\Story, as above. Highlight the "Story" folder or create it if it does not exist and press "Select Folder". THEN, modify Local path so it ends in \Story NOT Baldurs-Gate-JaDarius-Campaign. Delete everything after \Story

7. Click on the "Clone" button to start the cloning process.

8. Once the cloning process is complete, you can open your "Story-Copy" folder and copy-paste the files in to the new "Story" folder. Once Story contains the files from Story-Copy, delete Story-Copy.

9. Now you can open your Baldur's Gate and play the select the save.

### Normal Use

1. Before hosting gameplay, be sure to use "Fetch" on the top bar to ensure you are up to date. Then, if you can "Pull", do so to retrieve the latest game files.

2. After hosting gameplay, commit the changes with a brief summary using the blue button (bottom left).

3. Use the top bar's "Push" to push the changes to the remote repository. Now the remote files are synced with the updated save.

That's it! You have successfully committed and pushed the new save files to the remote repository using GitHub Desktop. Your changes are now available to others who have access to the repository.

For more information, refer to the [GitHub Desktop documentation](https://docs.github.com/en/desktop).
