[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285977&assignment_repo_type=AssignmentRepo)
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

SCREENSHOTS ARE ON THE IMAGES FOLDER

    Developer Environment Setup Documentation
1. Operating System: Windows 11
Download and Installation
1.	Visit the Windows 11 download page: Windows 11 Download
2.	Follow the instructions on the website to download the Windows 11 Installation Assistant.
3.	Run the Windows 11 Installation Assistant and follow the on-screen instructions to complete the installation.
4.	Restart your computer as prompted to finalize the installation.
2. Install a Text Editor or Integrated Development Environment (IDE): Visual Studio Code
Download and Installation
1.	Visit the Visual Studio Code download page: Visual Studio Code Download
2.	Select the appropriate version for Windows and download the installer.
3.	Run the installer and follow the on-screen instructions to complete the installation.
4.	Launch Visual Studio Code and configure your preferred settings.
3. Set Up Version Control System: Git and GitHub
Install Git
1.	Visit the Git download page: Git Download
2.	Download the appropriate version for Windows.
3.	Run the installer and follow the on-screen instructions, ensuring to select the options to add Git to your PATH.
4.	Verify the installation by opening a command prompt and running:
git --version
Configure Git
1.	Open a command prompt and configure your Git username and email:
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
Create a GitHub Account
1.	Visit the GitHub website: GitHub
2.	Sign up for a new account and follow the on-screen instructions to complete the registration.
Initialize a Git Repository
1.	Create a new directory for your project and navigate into it:
mkdir my_project
cd my_project
2.	Initialize a new Git repository:
git init
3.	Create a README file and make your first commit:
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
4. Install Necessary Programming Languages and Runtimes: Python
Download and Installation
1.	Visit the Python download page: Python Download
2.	Download the latest version for Windows.
3.	Run the installer and ensure to check the option to add Python to your PATH. Follow the on-screen instructions to complete the installation.
4.	Verify the installation by opening a command prompt and running:
python --version
5. Install Package Managers: pip
Verify pip Installation
1.	pip is included with Python installations. Verify its presence by running:
pip --version
2.	If pip is not installed, you can install it manually:
python -m ensurepip --upgrade
6. Configure a Database: MySQL
Download and Installation
1.	Visit the MySQL download page: MySQL Download
2.	Download the MySQL Installer and run it.
3.	Follow the on-screen instructions to install MySQL, choosing the server and any necessary tools.
4.	Set up the MySQL root password and configure the server as needed.
5.	Verify the installation by opening a command prompt and running:
mysql --version
7. Set Up Development Environments and Virtualization (Optional)
Consider Virtualization Tools
1.	If needed, consider installing Docker for containerization: Docker Download
2.	Follow the instructions on the Docker website to install and set up Docker on Windows.
3.	Alternatively, consider using virtual machines with tools like VirtualBox or VMware.
8. Explore Extensions and Plugins for Visual Studio Code
Recommended Extensions
1.	Python Extension for Visual Studio Code.
2.	GitLens for enhanced Git capabilities.
3.	Prettier for code formatting.
4.	ESLint for JavaScript/TypeScript linting.
Installation
1.	Open Visual Studio Code and navigate to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
2.	Search for and install the recommended extensions.
9. Document Your Setup
Create a Comprehensive Document
markdown
# Developer Environment Setup Documentation

## 1. Operating System: Windows 11

### Download and Installation
...

## 2. Install a Text Editor or Integrated Development Environment (IDE): Visual Studio Code

### Download and Installation
...

## 3. Set Up Version Control System: Git and GitHub

### Install Git
...

### Configure Git
...

### Create a GitHub Account
...

### Initialize a Git Repository
...

## 4. Install Necessary Programming Languages and Runtimes: Python

### Download and Installation
...

## 5. Install Package Managers: pip

### Verify pip Installation
...

## 6. Configure a Database: MySQL

### Download and Installation
...

## 7. Set Up Development Environments and Virtualization (Optional)

### Consider Virtualization Tools
...

## 8. Explore Extensions and Plugins for Visual Studio Code

### Recommended Extensions
...

### Installation
...

## 9. Document Your Setup

### Create a Comprehensive Document
...

10. GitHub Repository
git remote add origin https://github.com/kariukikelvin/Gitplp.git
git branch -M main
git push -u origin main
11. Reflection on Challenges
Challenges and Solutions
•	Challenge: Difficulty in installing dependencies.
o	Solution: Consulted official documentation and community forums for troubleshooting steps.
•	Challenge: Configuring MySQL server.
o	Solution: Followed detailed installation guides and utilized MySQL Workbench for easier management.
•	Challenge: Setting up Git and GitHub.
o	Solution: Utilized GitHub's tutorial for initial setup and configuration.



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
