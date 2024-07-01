[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15301483&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Go on code.visualstudio.com/download and choose windows 10,11 if thats your system and wait for it to download. Once its done go to where saved your download and open the new VS code to install it.when recieving a user control notice and click yes to open the visual studio. 


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Agree to the terms and conditions then click on next and next again and on select Additional Task and tick the four boxes under "other" and next and check to create a desktop Icon. Then next on the next page then install then finish. With the options i was given i chose Development Environment on the welcome screen. 

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

ACTIVITY BAR
It is located on the far left side of the visual studio Code window. It has icons for Explorer, Search, Source Control, and Extensions. It provides quick access to each of them, allowing users to switch between them easily.
SIDE BAR
It is located next to the Activity Bar. It has Explorer, Search, Source Control, and Extensions. It also gives access to more functionalities like debugging, Git integration, and extensions. Users can customize the Side Bar to show or hide specific views based on their preferences.
EDITOR GROUP
 It is in the center area of the visual studio Code window where files and folders are opened for editing. It consists editor panes, each showing a file or a split view of multiple files. Users can move between files and customize the layout of the Editor Group according to their workflow.
STATUS BAR
 It is located at the bottom of the visual studio Code window. It shows information about the project being worked on, file, and editor. It also provides access to language mode selection, indentation settings, line endings, and Git status. Additionally, it shows notifications and errors.

4. Command Pallete:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in visual studio Code allows users to access various commands and features through a search interface.
    It can be accessed by pressing Ctrl+Shift+p. then you can search for commands, settings, and extensions.

Common Tasks Using Command Palette
Opening Files: You can quickly open files by typing their name in the Command Palette.
Changing Themes: Switch between different color themes by searching for "Change Color Theme" in the Command Palette.
Running Tasks: Execute tasks defined in the workspace's configuration, such as building or testing, by searching for "Run Task".
Installing Extensions: Install new extensions by searching for "Extensions: Install Extensions".
Version Control: Access version control commands like committing changes or pushing to a remote repository.
The Command Palette is a versatile tool that allows users to efficiently navigate and control various aspects of VS Code.



5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

    extensions lets the user add languages, debuggers, and tools to their installation to support their development workflow. 
   FINDING EXTENTIONS
     Click on the Extensions view icon in the Activity Bar on the side of the window. use the search bar to find extensions you want to intstall by name.
INSTALLING EXTENSIONS 
when you find the extension, click the "Install" button and it will install.
MANAGING EXTENSIONS
 click on the Extensions view icon and then selecting the "Manage" icon. From there, they can disable, uninstall, or update extensions.

Some essential extensions for web development in VS Code include
 Prettier
 Itelligence
 Code runner

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   

Press Ctrl + ` (backtick) is used to open intergrated terminal on visual studio code
or View menu, then select Terminal.
Once itis open, You can run commands, install packages, and manage your project without leaving the VS Code interface.

ADVANTAGES
Seamless integration
 It is located within the VS Code interface, allowing the user to work without switching between different applications.
Workspace awareness
it automatically starts in the root of your workspace,which makes it easier to run commands specific to your project.
Customization
 the user can customize the its appearance, behavior, and shortcuts to suit their preferences.

Using the integrated terminal can streamline your workflow and improve productivity by keeping everything in one place.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

CREATING A NEW FILE
Click on the Explorer icon in the Activity Bar on the side of the window.
Right-click on the folder where you want to create the file.
Select "New File" and give the file a name.

OPENING AN EXISTING FILE
Click on the "File" menu at the top of the window.
Select "Open..." and go to the file you want to open.

MANAGING FILE AND FOLDERS
RENAME
 Right-click on the file or folder and select "Rename" .
DELETE 
Right-click on the file or folder and select "Delete" .
MOVE
You can drag and drop files and folders within the Explorer to move them to a different location.
Navigating Between Files and Directories

Switching Between Open Files
 Use Ctrl + Tab to cycle through open files.
GO TO FILE
 Press Ctrl + P to open the Quick Open menu, then start typing the name of the file you want to open.
EXPLORER NAVIGATION
 Use the Explorer view to navigate between different files and folders by clicking on them.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   To find settings in VS Code, the user must click on the gear icon in the lower-left corner of the window and select "Settings". they can use the shortcut Ctrl +.
Customizing Settings
CHANGING THE THEME
To change the theme, the user must go to the "Color Theme" section in the settings.
Search for "Color Theme", and then select the theme they prefer.
ADJUSTING FONT SIZE
To adjust the font size, search for "Font Size".
the user can then modify the "Editor: Font Size" setting to the values the user wants.
MODIFYING KEYBINDINGS:
To modify keybindings, search for "Keybindings" in the search bar.
Click on "Edit in settings.json" to customize keybindings using JSON format.
eg.
CHANGING THE THEME
Go to Settings > Color Theme > Select "Dark+ (default dark)".
ADJUSTING FONT SIZE
Search for "Font Size" > Modify "Editor: Font Size" to 16.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?


Click on the debug icon in the Activity Bar on the side of the window, then click on the gear icon to create a launch.json file. This file contains the configuration settings for debugging.
Navigate to the file containing their program, and click in the area just to the left of the line numbers to set breakpoints. These are points in the users code where the debugger will pause execution.
Press F5 or click the green play button in the Debug view to start debugging. This will launch the program in debug mode.

Key Debugging Features in VS Code
BREAKPOINTS 
Set breakpoints to pause the program at specific lines of code.
Watch and Variables: View the values of variables and expressions in real-time as you step through the code.
CALL STACK
 See the path that led to the current point in the code execution.
Step Through Code: Step through the code line by line, or jump to the next breakpoint.
Debug Console: Interact with the program by entering commands and evaluating expressions in the debug console.
CONDITIONAL BREAKPOINTS
 Set breakpoints that only trigger when certain conditions are met.
Exception Handling: Catch and handle exceptions that occur during program execution.



10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Install Git from the official website.
Open VS Code, Open the project folder in VS Code where you want to initialize the Git repository.
Click on the Source Control icon on the side of the window. Then, click "Initialize Repository" to create a new Git repository.fter making changes to your files, go to the Source Control view, stage the changes by clicking the "+" button next to the file(s) you want to commit, enter a commit message, and press Ctrl+Enter to commit the changes then Push Changes to GitHub

REFERENCES
AI(2024), Debugging on vs code,studocu.com

F.Churcville,user interface (UI),https://www.techtarget.com/searchapparchitecture/definition/user-interface-UI

T.Lamb(March 21.2022),Using VS Code & Git,https://www.gitkraken.com/blog/vs-code-git

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

