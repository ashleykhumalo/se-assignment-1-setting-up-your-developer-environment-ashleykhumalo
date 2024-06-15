[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272126&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Windows 11 came pre-installed in the computer so there is no additional installation that is necessary.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


   The steps to installing Visual studio Code follows:

   -Firstly went to Visual Studio Code official website.
   -Clicked on the appropriate operating system which is windows 11 and downloaded Visual Studio Code.
   -Located the downloaded file and installed the file with the name ('VSCodeSetup-x64-<version.exe>').
   -Followed the installation prompts which was accepting the licence agreement, choosing the installation location, selecting additional paths which was optional but it was recommended, clicked the install button and after it was done installing I clicked finish to launch Visual Studio Code.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Steps

  - Went to Git's official website on the browser and downloaded the installer.
  - Followed the installation instructions to install Git.

  Steps to Configuration of Git

  - Opened Git and ran it under adminstration.
  - typed the following to configure (git config --global user.name "my name typed here").
  - Moreover, (git config --global user.email "my email address typed here")

Steps to creating Github account:

- Opened Github official website and followed the instructions to sign in by typing the required details such as username, email address and setting up my password.

Initializing Git repository steps

In Gitbash typed the following:

-mkdir myproject 'clicked enter'
-cd myproject 'clicked enter'
-git init 'clicked enter'

Making of the Commit:

-echo "# MyProjects" >> README.md 'clicked enter'
-git add README.md 'clicked enter'
-git commit -m "initial commit" 'clicked enter'

Pushing project to Github steps:

-git remote add origin add origin https://github.com/myusername/myproject.git 'clicked enter'
-git push -u origin master 'clicked enter'

After these processes Git was successfully installed and configured.Github account was created and the Initial project repository was created and pushed to Github.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Installing Python

  - Opened the Python official webite on the browser.
  - Went to the downloads on the website and located Python download button for windows clicked to downloaded one for x64 bit computer as my computer is x64bit.
  - Followed the installation instructions and ensured that pythod is added to the path.
  - To add python to the path opened environment variables on the computer, clicked path and clicked edit and added the the python address that I copied after installation of the file in the program files inside users.
  - Opened Gitbash and typed the following to check if python is successfully installed " typed - python --version " and found the latest version of python installed.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Installation of package managers in Gitbash, typed the following:

   - pip --version found pip installed

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Steps taken
   step 1

   - Opened the MySQL official website on the browser and opened MySQL Community download page.
   - Selected my operating system which is Windows 11 and downloaded the MySQL installer

   Step 2

   - Atfer the MySQL was downloaded I located the file and double clicked the installer file to run it.
   - Got options to choose a setup and the options were Developer default and Server only, etc.
   - Selected the developer default as it versatile since it has more options such as (MySQL Server, MySQL Shell, MySQL Workbench, MySQL Router, and connectors for various programming languages.)
   - Chose the setup because it is recommended for developers who wants a comprehensive setup with all the tools needed for developing and testing.
   - Installed the required software and this software is Visual Studio and it was prompted by the installer.

   Step 3: Configuration

   - On the Type and Networking part I selected the configuration type (I typically left the default as it was already correct with 'Development Computer' selected).
   - On Authentication Method and I had to choose the authentication method. The default "Use Strong Password Encryption" which is recommended is what I selected.
   - On Accounts and Roles I had to set up a root password and I created an additional user accounts as it is a requirement.
   - On Windows Service decided to run MySQL as a windows service and instead of putting any other name I left it with the default name.

   Step 4: Initial Configuration

- On my computer with the operating system windows 11 it the running of the MySQL server ran automatically because I sat it to run as a service.
- Opened Command Prompt for logging into the server using the root account and prompted (mysql -u root -p) and entered the root password I configured during installation.
- Created a new database for my application by prompting (CREATE DATABASE your_database_name;).
- I then created a new user by typing the (CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON your_database_name.* TO 'username'@'localhost';
FLUSH PRIVILEGES;)and then granting the new user access to the new application.

Step 5: Verification

- Checked the services panel and it was verified.
- I connected to the server to run a test query by prompting (SHOW DATABASES;) in the terminal.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.  

   - I did not install the optional part at the moment.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   - Opened Visual Studio Code and located the extensions button and then I searched and installed essential extensions such as python, dart, matplotlib, prettier, and code runner.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    - Completed documentation of the setup with step by step instructions.
     
     Challenges faced
     -  The issue I faced was with Python path configuration, the python installer did not add python to the system path automatically hence I had to add it manually and I did this by copying the address of the installed file and I located environment variables. Selected path and selected edit and add and pasted the address I had copied earlier.
      

      Overall experience during setup

      Setting up the development environment gave me a hands-on exprience on how life as a developer is and hands-on practice with software development essentials configurations and tools. This process improved my critical thinking and problem solving skills as it required troubleshooting various issues which I encountered. 

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
