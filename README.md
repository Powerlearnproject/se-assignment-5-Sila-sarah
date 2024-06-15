[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280601&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   For Windows:
Visit the Visual Studio Code Website:
Open your web browser and go to the Visual Studio Code download page.
Download the Installer:
Click on the "Windows" icon to download the installer for Windows. It will download an .exe file.
Run the Installer:
Once the download is complete, open the .exe file to start the installation process.
Follow the Installation Steps:
Follow the prompts in the installation wizard. You can choose the installation location and additional tasks like creating a desktop icon.
Click "Next" and then "Install" to begin the installation.
Once the installation is complete, click "Finish" to exit the setup.
2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   1. User and Workspace Settings
VS Code provides two types of settings: User settings (global across all projects) and Workspace settings (specific to a project).
Open Settings:
You can open the settings UI by pressing Ctrl + , (or Cmd + , on macOS).
Alternatively, you can open settings in JSON format by searching for Preferences: Open Settings (JSON) in the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
2. Common Settings to Configure
Theme:
Change your editor theme by navigating to File > Preferences > Color Theme (or search Preferences: Color Theme in the Command Palette).
Browse and install themes from the Visual Studio Code Marketplace.
Font Size and Family:
In settings, search for editor.fontSize and set your preferred font size.
For the font family, search for editor.fontFamily.
Line Numbers:
Control the display of line numbers with editor.lineNumbers.
Tab Size:
Adjust tab size by modifying editor.tabSize.
To convert tabs to spaces, enable editor.insertSpaces.
3. Extensions
Extensions add functionality to VS Code.
Install Extensions:
Click on the Extensions icon on the Activity Bar on the side of the window or press Ctrl + Shift + X (or Cmd + Shift + X on macOS).
Browse and install extensions from the marketplace. Popular extensions include:
Prettier (Code Formatter)
ESLint (JavaScript Linting)
Python (Python Support)
C# (C# Support)
Live Server (Local Development Server)
3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
  1 . Activity Bar
The Activity Bar is located on the far left of the VS Code window. It allows you to switch between different views and provides access to various functionalities.
Icons in the Activity Bar:
Explorer: Provides access to the file explorer, where you can browse and manage your project files.
Search: Allows you to search for text within your project files.
Source Control: Integrates with version control systems like Git, enabling you to manage your source control directly within VS Code.
Run and Debug: Offers controls for running and debugging your application.
Extensions: Lets you browse, install, and manage extensions from the VS Code marketplace.
Each icon in the Activity Bar corresponds to a different view, and you can click on these icons to switch between views.

2. Side Bar
The Side Bar is located to the right of the Activity Bar and displays the contents of the selected view.
Explorer View: Shows the file and folder structure of your project.
Search View: Displays search results for text queries within your project.
Source Control View: Provides access to version control features, including staging, committing, and pushing changes.
Run and Debug View: Contains debugging controls and displays running processes, breakpoints, and call stacks.
Extensions View: Lists installed extensions and allows you to search for new extensions to install.
The Side Bar helps you navigate and manage different aspects of your project and development environment.

3. Editor Group
The Editor Group is the central part of the VS Code interface where you write and edit your code.
Tabs: Each open file is represented by a tab at the top of the Editor Group. You can switch between files by clicking on their tabs.
Multiple Editors: You can split the Editor Group to show multiple files side-by-side, either vertically or horizontally. This is useful for comparing files or working on multiple parts of a project simultaneously.
Context Menu: Right-clicking within the Editor Group provides access to common actions like cut, copy, paste, find, replace, and more.
The Editor Group is where the main coding activities occur, with support for syntax highlighting, code completion, linting, and other coding aids.

4. Status Bar
The Status Bar is located at the bottom of the VS Code window and provides information about the current state of the editor and workspace.
Information Display: The Status Bar shows information like the current Git branch, line and column numbers of the cursor position, language mode, encoding, and EOL (end of line) format.
Interactive Elements: Some parts of the Status Bar are interactive, allowing you to click on them to change settings (e.g., change the language mode or switch Git branches).
Extensions: Many extensions add their own indicators to the Status Bar, providing quick access to their features or displaying relevant information.
The Status Bar is a useful tool for monitoring the status of your development environment and making quick changes.
4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The Command Palette in Visual Studio Code (VS Code) is a powerful feature that provides quick access to a wide range of commands and settings. It allows you to perform tasks without having to navigate through menus or remember keyboard shortcuts
Accessing the Command Palette
Shortcut: You can open the Command Palette by pressing Ctrl + Shift + P on Windows and Linux, or Cmd + Shift + P on macOS.
Menu: Alternatively, you can access it via the menu by going to View > Command Palette....
Common Tasks Performed Using the Command Palette
Here are some examples of tasks you can perform using the Command Palette:
Opening Files
Command: File: Open File...
This allows you to quickly open files in your workspace by searching for the file name.
Installing Extensions
Command: Extensions: Install Extensions
Opens the Extensions view where you can browse and install extensions from the marketplace.
Running and Debugging Code
Command: Debug: Start Debugging or Debug: Run Without Debugging
Starts the debugging process or runs your application without the debugger.
Changing the Color Theme
Command: Preferences: Color Theme
Allows you to change the color theme of the editor. You can choose from a list of installed themes.
Formatting Code
Command: Format Document or Format Selection
Automatically formats your code according to the configured formatting rules.
Opening Settings
Command: Preferences: Open Settings or Preferences: Open Settings (JSON)
Opens the settings editor, either in a graphical interface or in JSON format for advanced users.
Using Git Commands
Command: Git: Commit or Git: Push
Perform Git operations like committing changes, pushing to a remote repository, and more.
Snippets
Command: Insert Snippet
Inserts predefined code snippets into your document.
Terminal Operations
Command Terminal: Create New Integrated Terminal
Opens a new integrated terminal instance within VS Code.
Navigating to Symbols
Command: Go to Symbol in File... or Go to Symbol in Workspace...
Quickly navigate to symbols (e.g., functions, variables) within the current file or across the workspace.
Using the Command Palette
When you open the Command Palette, you can start typing to filter through available commands. For example, if you type "format," you will see commands related to formatting code. Selecting a command from the list will execute it immediately.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
    Extensions play a crucial role in Visual Studio Code (VS Code) by enhancing its functionality and customizing the development environment to fit various needs. They add features and capabilities that are not available in the default installation, making VS Code a highly flexible and powerful code editor.
Finding, Installing, and Managing Extensions
Finding Extensions
Users can find extensions in the following ways:
Extensions View: Open the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl + Shift + X (or Cmd + Shift + X on macOS).
Marketplace: Visit the Visual Studio Code Marketplace to browse available extensions online.
Installing Extensions
Through the Extensions View:
Open the Extensions view (Ctrl + Shift + X or Cmd + Shift + X).
Search for the desired extension by name or keyword.
Click the Install button next to the extension's name.
Command Palette:
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type Extensions: Install Extensions and select it.
Search for and install the desired extension from the list.
Managing Extensions
Disable or Enable Extensions:
Open the Extensions view.
Click on the gear icon next to the installed extension and select Disable or Enable.
Uninstall Extensions:
Open the Extensions view.
Click on the gear icon next to the installed extension and select Uninstall.
Update Extensions:
If updates are available, they will be indicated in the Extensions view. Click on the update button to install the latest version.
Essential Extensions for Web Development
ESLint
Description: Integrates ESLint into VS Code, providing real-time linting and error checking for JavaScript and other languages.
Usage: Ensures code quality and consistency by enforcing coding standards.
Prettier - Code Formatter
Description: Automatically formats your code according to a consistent style.
Usage: Helps maintain clean and readable code by formatting it on save or on demand.
Live Server
Description: Launches a local development server with live reload capability for static and dynamic pages.
Usage: Provides a live preview of your web application as you make changes to the code.
Debugger for Chro
Description: Allows you to debug your JavaScript code running in the Chrome browser from within VS Code.
Usage: Provides powerful debugging tools for front-end development.
IntelliSense for CSS class names in HTML
Description: Provides CSS class name completion for the class attribute in HTML.
Usage: Enhances productivity by offering IntelliSense suggestions for CSS classes.
JavaScript (ES6) code snippets
Description: Adds a collection of useful JavaScript snippets for ES6 syntax.
Usage: Speeds up coding by allowing you to quickly insert common JavaScript code patterns.
Path Intellisense
Description: Autocompletes file paths in your code.
Usage: Simplifies the process of linking files and resources in your project.
GitLens — Git supercharged
Description: Enhances the built-in Git capabilities in VS Code with features like blame annotations, code lens, and more.
Usage: Provides advanced Git functionalities for better version control management.
REST Client
Description: Allows you to send HTTP requests and view responses directly within VS Code.
Usage: Useful for testing APIs without leaving the code editor.
Bracket Pair Colorizer
Description: Colors matching brackets to make them easier to identify.
Usage: Improves code readability and helps prevent syntax error

6. Integrated Terminal:
Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   - Opening and Using the Integrated Terminal in VS Code
The integrated terminal in Visual Studio Code (VS Code) allows you to run shell commands and scripts directly within the editor, making it easier to manage your development workflow without switching contexts.
Opening the Integrated Terminal
There are several ways to open the integrated terminal in VS Code:
Keyboard Shortcut:
Press Ctrl + (backtick) on Windows and Linux.
Press Cmd + (backtick) on macOS.
Menu:
Go to View > Terminal from the top menu.
Command Palette:
Open the Command Palette with Ctrl + Shift + P (or Cmd + Shift + P on macOS).
Type Terminal: Create New Integrated Terminal and select it.
Using the Integrated Terminal
Creating a New Terminal:
Click the + icon in the terminal panel or use the Ctrl + Shift + (or Cmd + Shift + on macOS) shortcut.
Switching Between Terminals:
Use the dropdown menu in the terminal panel to switch between multiple open terminals.
Splitting Terminals:
Click the split terminal icon or use the Ctrl + Shift + 5 (or Cmd + Shift + 5 on macOS) shortcut to split the current terminal into multiple panes.
Terminal Settings:
Customize terminal settings by opening the settings (Ctrl + , or Cmd + ,), searching for terminal, and modifying settings like terminal.integrated.shell.windows, terminal.integrated.shell.linux, and terminal.integrated.shell.osx to specify the default shell.
Running Commands:
You can run any command available in your shell, such as npm start, git status, python script.py, etc.
Clearing the Terminal:
Type clear or use the Ctrl + L (or Cmd + K on macOS) shortcut to clear the terminal.
Advantages of Using the Integrated Terminal Compared to an External Terminal
Context Switching:
Reduced Context Switching: The integrated terminal allows you to stay within the VS Code environment, minimizing the need to switch between different applications.
Better Focus: You can write code and run terminal commands without losing focus on your development tasks.
Workspace Integration:
Workspace Context: The integrated terminal opens in the root of your workspace by default, making it easier to run commands that are relative to your project.
Project Environment: Environment variables and settings can be configured specifically for your project, ensuring commands run in the appropriate context.
Accessibility and Customization:
Customizable Shell: Easily switch between different shell environments (e.g., Bash, PowerShell, Command Prompt) from within the terminal.
Custom Themes: Match the terminal appearance with your editor theme for a consistent look and feel.
Multi-Terminal Management:
Multiple Terminals: Open and manage multiple terminal instances within the same window, split them horizontally or vertically, and switch between them easily.
Task Integration: Integrate terminal tasks with VS Code’s task runner for automation of build processes, testing, and other repetitive tasks.
Extension Support:
Enhanced Functionality: Many extensions provide additional features and commands that can be used directly within the integrated terminal, enhancing its capabilities.
Output Integration:
Error Navigation: Easily navigate between errors and output in the terminal and the related code in the editor.
Terminal Links: The integrated terminal can recognize file paths, links, and commands, allowing you to click and navigate directly to them
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
Creating, Opening, and Managing Files and Folders in VS Code
Creating Files and Folders
Using the Explorer View:
Create a New File:
Open te Explorer view by clicking the folder icon in the Activity Bar or pressing Ctrl + Shift + E (or Cmd + Shift + E on macOS).
Click the New File icon (a piece of paper with a plus sign) at the top of the Explorer view or right-click in the Explorer view and select New File.
Enter the desired file name and press Enter.
Create a New Folder:
Open the Explorer view.
Click the New Folder icon (a folder with a plus sign) at the top of the Explorer view or right-click in the Explorer view and select New Folder.
Enter the desired folder name and press Enter.
Using the Command Palette:
Open the Command Palette by pressing Ctrl + Shift + P (or Cmd + Shift + P on macOS).
Type File: New File to create a new file.
Type Explorer: New Folder to create a new folder.
Follow the prompts to name the file or folder.
Opening Files and Folders
Using the Explorer View:
Expand the folders in the Explorer view to navigate to the desired file.
Click on the file to open it in the Editor Group.
Using the Command Palette:
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type File: Open File... to open a file.
Type File: Open Folder... to open a folder.
Follow the prompts to select the file or folder.
Using Keyboard Shortcuts:
Press Ctrl + O (or Cmd + O on macOS) to open the file dialog and select a file.
Press Ctrl + K, Ctrl + O (or Cmd + K, Cmd + O on macOS) to open the folder dialog and select a folder.
Managing Files and Folders
Renaming:
In the Explorer view, right-click the file or folder and select Rename, or select the file or folder and press F2.
Enter the new name and press Enter.
Deleting:
In the Explorer view, right-click the file or folder and select Delete, or select the file or folder and press Delete.
Moving:
Drag and drop the file or folder within the Explorer view to move it to a new location.
Alternatively, cut (Ctrl + X or Cmd + X) and paste (Ctrl + V or Cmd + V) the file or folder in the desired location.
Efficient Navigation Between Files and Directories
Quick Open:
Press Ctrl + P (or Cmd + P on macOS) to open the Quick Open feature.
Start typing the name of the file you want to open. VS Code will show a list of matching files. Select the file from the list to open it.
File Explorer:
Use the Explorer view (Ctrl + Shift + E or Cmd + Shift + E) to navigate the folder structure and open files by clicking on them.
Breadcrumb Navigation:
The breadcrumb navigation at the top of the editor shows the current file's path. Click on any part of the breadcrumb to navigate to that directory or file.
Open Editors:
The Open Editors section at the top of the Explorer view shows all currently open files. Click on any file to switch to it.
Go to Definition:
Right-click on a symbol (like a function or variable) and select Go to Definition, or press F12. This will navigate to the definition of the symbol in the code.
Go to Symbol:
Press Ctrl + Shift + O (or Cmd + Shift + O on macOS) to open the Go to Symbol feature. Type the name of the symbol to navigate to it within the current file.
Go to Line:
Press Ctrl + G (or Cmd + G on macOS) to open the Go to Line feature. Enter the line number to jump to that line in the current file.
Integrated Terminal
Open the integrated terminal (Ctrl + or Cmd + on macOS) and use command-line navigation commands (like cd, ls, or dir) to navigate your project’s directory structure.
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Finding and Customizing Settings in VS Code
Users can find and customize settings in Visual Studio Code (VS Code) through the Settings UI or by directly editing the settings.json file. VS Code settings can be configured at the user level (global settings) or at the workspace level (settings specific to a project).
Accessing Settings
Settings UI:
Open the Settings UI by clicking the gear icon in the lower-left corner of the window and selecting Settings, or by pressing Ctrl + , (or Cmd + , on macOS).
settings.json:
Open the Command Palette with Ctrl + Shift + P (or Cmd + Shift + P on macOS).
Type Preferences: Open Settings (JSON) and select it to open the settings.json file.
Changing the Theme
Using the Settings UI:
Open the Settings UI (Ctrl + , or Cmd + ,).
In the search bar at the top, type color theme.
Click on Color Theme under Preferences to see the list of available themes.
Select the desired theme from the list.
Using the Command Palette:
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type Preferences: Color Theme and select it.
Choose a theme from the list that appears.
Changing the Font Size
Using the Settings UI:
Open the Settings UI (Ctrl + , or Cmd + ,).
In the search bar at the top, type font size.
Adjust the Editor: Font Size setting to the desired value.
Using settings.json:
Open settings.json (Ctrl + Shift + P or Cmd + Shift + P, then type Preferences: Open Settings (JSON)).
Add or modify the following line to set the font size (e.g., to 16):
json
Copy code
"editor.fontSize": 16
Changing Keybindings
Using the Keybindings UI:
Open the Keybindings UI by clicking the gear icon in the lower-left corner and selecting Keyboard Shortcuts, or by pressing Ctrl + K, Ctrl + S (or Cmd + K, Cmd + S on macOS).
In the Keybindings UI, you can search for specific commands and change their keybindings by clicking the pencil icon next to the command and pressing the new key combination.
Using keybindings.json:
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P).
Type Preferences: Open Keyboard Shortcuts (JSON) and select it to open the keybindings.json file.
Add or modify keybinding entries. For example, to change the keybinding for saving a file to Ctrl + Alt + S, add:
json
Copy code
[
  {
    "key": "ctrl+alt+s",
    "command": "workbench.action.files.save"
  }
]
9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   Steps to Set Up and Start Debugging in VS Code
Install Necessary Extensions:

Before starting, ensure you have the appropriate debugger extension installed for your programming language. Examples include:
Node.js: Debugger for Chrome or Node.js Debug
Python: Python extension by Microsoft
Java: Debugger for Java
C++: C/C++ extension
Open Your Project:

Open the folder containing your project files in VS Code. You can do this by clicking File > Open Folder... and selecting your project directory.
Create a Simple Program:

Write a simple program in the language of your choice. For example, create a file named app.js for a Node.js application with the following content:
javascript
Copy code
console.log("Hello, world!");
Open the Debug View:

Click on the Run icon in the Activity Bar on the side of the window, or press Ctrl + Shift + D (or Cmd + Shift + D on macOS) to open the Run and Debug view.
Create a launch.json Configuration:

If you haven't set up debugging before, VS Code will prompt you to create a launch.json file.
Click on Create a launch.json file or the gear icon to configure debugging.
Select the environment (e.g., Node.js, Python) for which you want to create a configuration.
Configure Launch Settings:

VS Code will generate a basic launch.json file with a default configuration. Modify the program attribute to point to the entry point of your application. For example, for a Node.js app:
json
Copy code
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "program": "${workspaceFolder}/app.js"
    }
  ]
}
Set Breakpoints:

Set breakpoints in your code by clicking in the gutter (left margin) next to the line numbers where you want the debugger to pause execution. This allows you to inspect variables and the program's state at that point.
Start Debugging:

Press F5 or click the green play button in the Run and Debug view to start debugging.
The program will run and pause at the breakpoints you've set, allowing you to step through the code, inspect variables, and debug any issues.
Key Debugging Features in VS Code
Breakpoints:

Conditional Breakpoints: Set breakpoints to trigger only when specific conditions are met.
Logpoints: Insert console.log-like messages without stopping execution.
Watch and Variables:

Watch Expressions: Monitor variables and expressions in real-time.
Variables View: Inspect the current values of variables and modify them during debugging.
Call Stack:

View the call stack to understand the sequence of function calls leading to the current point in execution.
Debug Console:

Interact with the running program through the Debug Console, execute commands, and evaluate expressions.
Step Controls:

Step Over (F10): Execute the next line of code.
Step Into (F11): Step into a function call.
Step Out (Shift + F11): Step out of the current function.
Exception Handling:

Exception Breakpoints: Pause execution when exceptions (e.g., errors) are thrown.
Integrated Terminal:

Use the integrated terminal to run commands or scripts related to your debugging session.
Multi-Session Debugging:

Debug multiple sessions simultaneously, useful for microservices or client-server applications.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Integrating Git with Visual Studio Code (VS Code) allows developers to manage version control directly within their development environment. Here’s a step-by-step guide on how to initialize a Git repository, make commits, and push changes to GitHub using VS Code:

Initializing a Repository
Open Your Project in VS Code:

Navigate to your project folder and open it in VS Code (File > Open Folder...).
Open the Source Control View:

Click on the Source Control icon in the Activity Bar on the side of the window (or press Ctrl + Shift + G).
Initialize Git Repository:

Click on the Initialize Repository button (it looks like a checkmark over a swirl) in the Source Control view.
Alternatively, open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P on macOS), type Git: Initialize Repository, and select it.
Select Repository Location:

Choose the root folder of your project to initialize Git. This creates a .git folder in your project directory, which tracks changes and manages version control.
Making Commits
Stage Changes:

In the Source Control view, you'll see a list of changed files. Click the + icon next to each file you want to stage for commit. Staging prepares files to be included in the next commit.
Write Commit Message:

Below the list of staged changes, there is a textbox labeled "Message (press Ctrl+Enter to commit)". Enter a descriptive commit message summarizing the changes made in this commit.
Commit Changes:

Press Ctrl + Enter (or click the checkmark icon) to commit the staged changes with the entered commit message.
Pushing Changes to GitHub
Before pushing changes to GitHub, ensure you have set up a repository on GitHub and have the repository URL available.

Add Remote Repository:
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P on macOS), type Git: Add Remote, and select it.
Enter the URL of your GitHub repository when prompted (e.g., https://github.com/username/repository.git).
Push Commits to GitHub:

After committing your changes locally, click on the ... menu (ellipsis) in the Source Control view header and select Push.
Alternatively, open the Command Palette, type Git: Push, and select it.
VS Code will prompt you to select the remote branch (usually main or master). Press Enter to confirm.
Authenticate (if this isyour first time pushing to GitHub from VS Code on this machine, you may need to authenticate. Follow the prompts in VS Code or your web browser to complete authentication.
Monitor Push Progress:
VS Code will show the progress of the push in the bottom-left corner (status bar) and provide feedback once the push is complete.
Additional Tips:
Branching and Merging: Use the Source Control view to create branches (Git: Create Branch...) and merge changes (Git: Merge Branch...).
Pull Changes: Fetch changes from a remote repository using Git: Pull to update your local branch with changes from GitHub.
Resolve Conflicts: If there are conflicts during a pull or merge operation, VS Code provides tools to help resolve them directly within the editor.
Git History: View the Git history (View > Git History) to see a timeline of commits and changes.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

