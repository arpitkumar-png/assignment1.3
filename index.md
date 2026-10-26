You can follow these commands in your terminal (macOS/Linux Terminal or Windows Git Bash/PowerShell) to set up your project structure, practice navigation, and prepare your submission record.

Step-by-Step Terminal Commands
Open your terminal and run the following commands one by one (or copy-paste them):

Bash
# 1. Create the main project folder
mkdir web-development-practice

# 2. Navigate into the new folder
cd web-development-practice

# 3. Create the week folders inside it
mkdir week-1 week-2 week-3

# 4. Create an index.html file inside each week folder
touch week-1/index.html week-2/index.html week-3/index.html

# 5. Open the project folder directly in VS Code
code .
Note for Windows PowerShell users: If you are using Windows PowerShell instead of Git Bash, step 4 can be done using:
New-Item week-1/index.html, week-2/index.html, week-3/index.html -ItemType File

Practice Guide: Navigation, Renaming & Deleting (Step 5)
To fulfill the requirement of practicing terminal manipulation, here are the commands you should try out and understand:

Navigating (cd - Change Directory):

cd week-1 → Moves you inside the week-1 folder.

cd .. → Moves you back up to the parent folder (web-development-practice).

Renaming (mv - Move/Rename):

mv week-1 week-one → Renames the folder week-1 to week-one. (Change it back using mv week-one week-1 so your submission matches the structure!)

Deleting (rm - Remove):

To practice deleting a file: rm week-1/index.html (then recreate it with touch week-1/index.html).

To delete an empty directory: rmdir folder-name.

Submission Record
You can copy the block below to use as your record of terminal commands for your assignment submission:

Plaintext
Project Setup Command History:
1. mkdir web-development-practice
2. cd web-development-practice
3. mkdir week-1 week-2 week-3
4. touch week-1/index.html week-2/index.html week-3/index.html
5. code .
For your screenshot:

Make sure VS Code is open to your web-development-practice folder (using code .).

Expand the sidebar in VS Code to clearly show week-1, week-2, and week-3 with their respective index.html files.

Take a screenshot of your screen showing both your terminal and VS Code side-by-side.