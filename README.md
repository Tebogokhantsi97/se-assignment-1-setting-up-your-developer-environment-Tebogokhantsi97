[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15298698&assignment_repo_type=AssignmentRepo)
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
DOCUMENTATION OF MY ANSWERS 

OPERATING SYSTEMS 

My Machine came with a pre-installed window 11. The latest version of Microsoft's Windows operating system, offering a modern interface, enhanced performance, and improved security features which allowed me to go to the next steps. 

        2. IDE INSTALLATION: To download and install Visual Studio Code (VS Code) I used the    the following steps 

I visited the official Visual Studio Code Download Page Visual Studio Code download page.  

Selected the version of Visual Studio Code suitable for my operating system: 

For Windows, click on the "Windows" button. 

Once the installer is downloaded, run it to begin the installation process. 

For Windows: 

Locate the downloaded .exe file (usually in your Downloads folder) and double-click it to run the installer. 

 

Follow the on-screen instructions: 

Accept the license agreement. 

Choose the installation location (the default is usually fine). 

Select additional tasks such as creating a desktop icon, adding to the PATH (important for command-line use), and enabling file associations. 

Click "Install" to proceed, and then click "Finish" once the installation is complete. 

 

After installation, launch Visual Studio Code 

On Windows, you can find it in the Start menu under "Visual Studio Code". 

  Customize vs code to suit your development needs: 

Extensions: Click on the Extensions icon in the Activity Bar on the side of the window, and search for extensions relevant to your programming languages and tools (e.g., Python, JavaScript, C++, etc.). 

 

3. To set up a version control system with Git and GitHub  

Visit the web link https://github.com  to Download Git for Windows 

Clicked download button to download the installer 

Run the Installer: 

Run the downloaded .exe file as an administrator 

Follow the on-screen instructions. The default settings are usually fine (don’t change anything), but make sure to choose the options to add Git to your PATH and to use Git from the command line and third-party software. 

Complete the installation ,you should see the Git version installed. 

4. Download and Install Python 

Visit the Python Official Website – go to Python.org.  

Download the Latest Version: Click on the "Download Python" button. The site should automatically detect your operating system and provide the appropriate installer (e.g., Python 3.12.4 in my case). 

Once the download is complete open fine in the machine - 

 

Note: Run the installer- Locate the downloaded installer (usually in your Downloads folder) and run it. 

Make sure to check the box that says "Add Python to PATH" before clicking "Install Now". 

Follow the installation prompts to complete the setup. 

 

To Verify Installation - Open Command Prompt and type: 

On Git bash: python –version 

 

You should be able see the installed Python version. 

 

To Install pip (Python Package Installer) in the machine 

Ensure pip is Installed: 

       Note: pip is usually installed by default with Python. You can check by running 

pip --version              

 

 

My pip was already installed in my laptop as it depicted on the above picture. 

 

Install Necessary Python Packages 

Determine Required Packages  (e.g, Django) - Identify the Python packages required for your project. These are often listed in a requirements.txt file. 

I used - (pip install -r requirements.txt) 

Set Up a Virtual Environment - Activate the virtual environment on windows: 

 

 Myenv\Scripts\activate 

 

7. To download and install MySQL database on my Windows system machine 

Visited the MySQL Download Page: 

Go to the MySQL Installer download page for version 5.7. 

Download the Installer - Click on the "Download" button for the "Windows (x86, 32-bit), MSI Installer" (MySQL Installer 5.7). 

You will be redirected to the MySQL download page. 

Choose between the "Web Community" version (smaller initial download) and the "Full" version (includes all components). For most users, the "Web Community" version is sufficient. 

Click on the download link to start downloading the installer. 

 

To Install MySQL Run the Installer: 

Locate the downloaded installer file (usually in your Downloads folder) and double-click it to run the installer. 

Choose Setup Type: 

The MySQL Installer will launch. Select a setup type. For most users, "Developer Default" is a good choice as it includes MySQL Server, MySQL Workbench, and other useful tools. 

Click "Next" to proceed. 

Check Requirements: 

The installer will check for any required software. If any dependencies are missing, the installer will prompt you to install them. 

Click "Execute" to install any required software and then click "Next" to proceed. 

Select Products and Features: 

You can review the selected products and features. click "Next" to continue. 

Click "Execute" to begin the installation of the selected products. 

Apply Configuration: 

After installation, the configuration process will start. Click "Next" to begin the configuration. 

Configure MySQL Server 

Type and Networking: 

Select "Standalone MySQL Server / Classic MySQL Replication". 

Leave the default settings for TCP/IP and port 3306 unless you have specific requirements. 

Click "Next". 

Authentication Method: 

Choose "Use Strong Password Encryption for Authentication (Password that you won’t forget *****)". 

Click "Next". 

Accounts and Roles: 

Set a strong password for the root account. 

Optionally, you can create additional user accounts by clicking "Add User". 

Click "Next". 

 Windows Service: 

Choose to run MySQL as a Windows Service and optionally set it to start at system startup. 

You can leave the default service name as "MySQL57". 

Click "Next". 

Apply Configuration: 

Review your configuration settings. 

Click "Execute" to apply the configuration. 

Once the configuration is complete, click "Finish". 

 Verify MySQL Installation 

Open MySQL Workbench: 

If MySQL Workbench was installed, open it from the Start menu or desktop shortcut. 

Connect to the MySQL Server: 

In MySQL Workbench, click on the "Local instance MySQL" connection. 

Enter the root password you set during the installation. 

Click "OK" to connect. 

To Verify the Connection: 

If you can connect successfully, the installation is complete. 

 Command-Line Usage 

Open Command Prompt: 

Open Command Prompt from the Start menu. 

Connect to MySQL Server: 

Type the following command and press Enter: 

bash 

Copy code 

mysql -u root -p 
 

Enter the root password when prompted. 

Verify MySQL Version: 

After logging in, you can verify the MySQL server version by typing: 

sql 

Copy code 

SELECT VERSION (); 
 

You should see the version of MySQL you installed.