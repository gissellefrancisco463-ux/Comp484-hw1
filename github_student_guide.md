# Student Guide: How to Submit Your Assignment Using GitHub Desktop

Follow these steps exactly to link your local project files to GitHub and submit your work.

---

## Phase 1: Tag Your Current Workspace

Before creating anything new, we need to mark your current working folder so it does not get confused with your final submission folder.

1. **Close VS Code:** Go to the top menu of VS Code, select **File** > **Close Folder**, and then close the code editor completely.
2. **Open Your File Browser:**
   - **Windows:** Open **File Explorer** and find your assignment folder.
   - **Mac:** Open **Finder** and find your assignment folder.
3. **Rename the Folder:** Right-click your assignment folder, select **Rename**, and add **`-OLD`** to the end of the name (for example: `comp484-hw1-OLD`).

---

## Phase 2: Create a Blank Repository on GitHub

1. Open your web browser and go to [GitHub.com](https://github.com).
2. In the top-right corner, click the **`+`** icon and select **New repository**.
3. **Repository Name:** Name it exactly as required by your instructor (e.g., `comp484-hw1`).
4. **Visibility:** Set it to **Public**.
5. **CRITICAL STEP:** Leave **all** initialization checkboxes **unchecked** (Do NOT check _Add a README_, _Add .gitignore_, or _Choose a license_). Your repository must be completely blank.
6. Click the green **Create repository** button.

---

## Phase 3: Create your Official Tracked Folder

1. Open the **GitHub Desktop** app.
2. In the top menu bar, click **File** > **Clone Repository...** (or press `Ctrl + Shift + O` on Windows / `Cmd + Shift + O` on Mac).
3. Click the **GitHub.com** tab.
4. Select your newly created repository from the list.
5. **Local Path:** Click **Choose...** and select the **exact same directory** where your `-OLD` folder currently lives.
   - _Note for Mac Users:_ If prompted for permission to access your folders, click **OK** or **Allow**.
6. Click **Clone**. This creates a brand new, clean folder right next to your old one. It is perfectly synced with the cloud.

---

## Phase 4: Copy, Paste, and Sync Your Code

1. Open your file browser (**File Explorer** or **Finder**) and open your **`-OLD`** folder.
2. Select **all the files and folders inside it** and copy them:
   - **Windows:** Press `Ctrl + A` to select all, then `Ctrl + C` to copy.
   - **Mac:** Press `Cmd + A` to select all, then `Cmd + C` to copy.
3. Go back one level, open your **new folder** (the one without `-OLD`), and paste the files inside (`Ctrl + V` on Windows / `Cmd + V` on Mac).
4. Open **GitHub Desktop**. You will instantly see all your code files appear in the left-hand **Changes** tab.
5. At the bottom-left corner, type `Initial Submission` in the **Summary (required)** box.
6. Click the blue **Commit to main** (or **Commit to master**) button.
7. Click the blue **Publish repository** (or **Push origin**) button at the top of the window.

---

## Phase 5: Verify and Clean Up

Before deleting anything, we will run a final test to ensure your code is completely safe.

1. **The Web Check:** Go to your browser, refresh your GitHub repository page, and verify that you can see your files sitting online.
2. **Open the Correct Folder:** Open **VS Code**, go to **File** > **Open Folder**, and open your **new folder** (the one without `-OLD` in the name).
3. **The Live Sync Test:** Make a tiny change in VS Code (like adding a blank line or a comment to a file) and save it. Look at GitHub Desktop. If that change pops up in the app, you are officially working out of the correct directory!
4. **Trash the Old Folder:** Open your file browser, right-click the folder ending in **`-OLD`**, and select **Delete** (Windows) or **Move to Trash** (Mac).
