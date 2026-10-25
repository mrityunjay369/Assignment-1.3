Assignment 1.3 — Terminal & Developer Workflow

Aim

To create and manage a project folder structure using terminal commands.

Procedure

1. Opened the terminal.
2. Created a folder named "web-development-practice".
3. Created "week-1", "week-2", and "week-3" folders inside it.
4. Created an "index.html" file inside each folder.
5. Practiced navigating, renaming, and deleting folders using terminal commands.
6. Opened the project folder in Visual Studio Code using the terminal.

Terminal Commands

1. Create the Project Structure

mkdir web-development-practice
cd web-development-practice
mkdir week-1 week-2 week-3

2. Create index.html Files

Windows (Command Prompt):

type nul > week-1\index.html
type nul > week-2\index.html
type nul > week-3\index.html

Linux/macOS (Terminal):

touch week-1/index.html
touch week-2/index.html
touch week-3/index.html

3. Navigate Between Folders

cd week-1
cd ..
cd week-2
cd ..

4. Rename a Folder

Windows (Command Prompt):

ren week-3 week-3-renamed
ren week-3-renamed week-3

Linux/macOS:

mv week-3 week-3-renamed
mv week-3-renamed week-3

5. Delete a Folder

Windows (Command Prompt):

mkdir test-folder
rmdir test-folder

Linux/macOS:

mkdir test-folder
rmdir test-folder

6. Open the Project in VS Code

cd ..
code web-development-practice

If the terminal is already inside "web-development-practice", simply run:

code .

7. Verify the Folder Structure

Windows:

tree /F

Linux/macOS:

find . -print

Expected Output

The following folder structure should be created:

web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html

The terminal should display the folder structure, and the project should open successfully in Visual Studio Code.

Observations

1. The "mkdir" command creates new directories.
2. The "cd" command changes the current directory.
3. The "type nul" or "touch" command creates empty files.
4. The "ren" or "mv" command renames folders.
5. The "rmdir" command removes an empty directory.
6. The "tree /F" or "find" command displays the project structure.
7. The "code ." command opens the current project folder in Visual Studio Code.

Result

The project folder structure was created successfully using terminal commands. Navigation, folder renaming, directory deletion, and opening the project in Visual Studio Code were practiced.

Submission

Attach a screenshot of the terminal showing the final folder structure and include the terminal commands used to create and manage the project.
