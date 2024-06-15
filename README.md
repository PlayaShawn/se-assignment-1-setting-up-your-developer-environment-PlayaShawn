[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15260690&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
Developer Environment Setup Documentation
This document outlines the step-by-step process for setting up a developer environment with Windows 11, Visual Studio Code, Git, Python, and MySQL. Follow each step carefully to ensure a smooth setup.

1. Choosing Your Operating System (OS)
     After having installed the most suitable operating system(Download and Install Windows 10/11 by visiting the Windows 10/11 Download Page.)
    
2. Install a Text Editor or Integrated Development Environment (IDE)
   Download and Install Visual Studio Code
     (Visit the Visual Studio Code Download Page and select the appropriate version for Windows and download the installer Run the installer and follow the on-screen instructions to complete the installation.
3. Set Up Version Control System
     Install Git by visiting the Git download page and download the appropriate version for Windows.
     Run the installer and follow the on-screen instructions to install.
        NB:select the options to integrate Git with the command line and Windows Explorer context menu.
    
     Configure Git by openning Git Bash as an administrator(access permissions) which was installed with Git
     Configure your username and email
     Confirm the configuration
     
    
     Visit GitHub to Sign in/Sign up for an account and initialize a Git repository.
      create a new folder for your project and open it in Visual Studio Code.
      Open a terminal in Visual Studio Code (Ctrl + ).
       git init
       Create a README file
     make the first commit:
        Add and commit the README file:
          git add README.md
          git commit -m "Initial commit"
          ![alt text](Commit.png)
4. Install Necessary Programming Languages and Runtimes
     Install Python.Visit the Python Download Page and Download the latest version for Windows.
     Run the installer and make sure to check the box "Add Python to PATH" while following the on-screen instructions to complete the installation.
     Verify Python Installation.Open a terminal in Visual Studio Code:
     ![alt text](PythonVer.png)

5. Install Package Managers
     Install pip (Python).Pip is installed by default with Python. 
     Verify the installation:
     ![alt text](PipVersion.png)

6. Configure a Database (MySQL)
     Download and Install MySQL.(Visit the MySQL Installer page and download the MySQL Installer for Windows.)
     Run the installer and follow the on-screen instructions to install MySQL.
     During installation, configure the root password and note it down for future use.
     Verify MySQL Installation
     Open MySQL Workbench (installed with MySQL)/Can be installed seperately.
     Connect to the local MySQL server using the root account and password.

7. Set Up Development Environments and Virtualization (Optional)
     Install Docker(.Visit the Docker Desktop Download page and download the Docker Desktop for Windows.)
     Run the installer and follow the on-screen instructions.
     After installation, open Docker Desktop to verify that it is running.

8. Explore Extensions and Plugins
     Visual Studio Code Extensions
      Open Visual Studio Code.
      Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.(Ctrl + Shift + X)
      install the following recommended extensions:Python, GitLens, MySQL, Docker, Prettier - Code formatter
