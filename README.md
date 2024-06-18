[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284406&assignment_repo_type=AssignmentRepo)
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

1. How to install Windows 11:
Prerequisites:

   Backup your data: Before installing Windows 11, make sure to backup your important files and data to an external hard drive or cloud storage.
   Check system requirements: Ensure your PC meets the minimum system requirements for Windows 11, which include:
   9 GB of free disk space
   64-bit processor
   UEFI firmware
   Secure Boot support
   Trusted Platform Module (TPM) 2.0
   Download the installation media: You can download the Windows 11 installation    media from the official Microsoft website or use a bootable USB drive.

   Step 1: Prepare your PC

Disable Secure Boot: Enter your PC’s BIOS settings and disable Secure Boot.
Set your PC to boot from USB: Set your PC to boot from the USB drive containing the Windows 11 installation media.
   Step 2: Boot from the installation media

Insert the USB drive: Insert the USB drive containing the Windows 11 installation media into your PC.
Restart your PC: Restart your PC and enter the BIOS settings again.
Set the USB drive as the first boot device: Set the USB drive as the first boot device.
Save changes and exit: Save the changes and exit the BIOS settings.
   Step 3: Start the installation process

Boot from the USB drive: Your PC will now boot from the USB drive.
Select your language and other preferences: Select your language, time and currency format, and other preferences.
Accept the license agreement: Accept the license agreement and terms of service.
Choose the installation type: Choose the installation type: “Custom” or “Upgrade”. If you’re upgrading from Windows 10, choose “Upgrade”. If you’re installing on a new hard drive, choose “Custom”.
   Step 4: Install Windows 11

Install Windows 11: The installation process will begin. This may take some time.
Follow the prompts: Follow the prompts to install Windows 11, including setting up your account and configuring your network settings.
   Step 5: Activate Windows 11

Activate Windows 11: Once the installation is complete, you’ll need to activate Windows 11. You can do this by connecting to the internet and following the prompts.
   Step 6: Install drivers and updates

Install drivers: Install any necessary drivers for your hardware.
Install updates: Install any available updates for Windows 11.

Tips and Variations:

   Clean install: If you want to perform a clean install of Windows 11, you can do so by selecting the “Custom” installation type and formatting your hard drive.
   Upgrade from Windows 10: If you’re upgrading from Windows 10, you can do so by selecting the “Upgrade” installation type.
   Install on a new hard drive: If you’re installing Windows 11 on a new hard drive, you’ll need to format the drive and install Windows 11 from scratch.

2. How to install VScode IDE on Windows:
   Download the ZIP package: Go to the VSCode download page and download the ZIP package for your operating system.
   Extract the ZIP package: Extract the ZIP package to a directory of your choice.
   Launch VSCode: Run the code executable in the extracted directory to launch VSCode.

3. Installing Git and initializing it:
   To install Git, you can follow the installation instructions for your operating system:

   For Windows: Download and install Git from the official website, then follow the prompts to complete the installation.
   Once installed, you can verify that Git is working by opening a terminal window and typing git --version. This should display the version of Git that you just installed.

   To initialize a new Git repository, navigate to the directory where you want to create your repository using the terminal. Then, run the following command:
   git init
   This will create a new directory called .git in your current directory, which will contain all the necessary files for Git to track changes.
   
   Next, you can add your files to the repository by running the following command:
   git add .
   This will stage all the files in your current directory for the next commit.

   Finally, you can commit your changes by running the following command:
   git commit -m "Initial commit"
   This will create a new commit with the specified message.

   You can also initialize a Git repository from an existing project by cloning it from a remote repository. To do this, navigate to the directory where you want to clone the repository and run the following command:
   git clone <repository-url>
   Replace <repository-url> with the URL of the remote repository you want to clone.
   Once you have cloned the repository, you can navigate to the directory and run git init to initialize a new local repository.

4. Installing Python:
Step 1: Download the Installer
   Go to the official Python website (www.python.org) and click on the “Download” button.
   Select the latest version of Python (currently Python 3.9.1) and choose the “Windows x86-64 executable installer” for a 64-bit system.
   Click on the “Download” button to begin the download process.
Step 2: Run the Installer
   Once the download is complete, open the executable file and click on “Run” to start the installation process.
   If you want to save the installation file in a different location, click on “Customize installation” and select the desired location.
Step 3: Follow the Installation Prompts
   The installation wizard will guide you through the installation process. Follow the prompts to complete the installation.
   Make sure to select the option to add Python to your system’s PATH during the installation process.
Step 4: Verify the Installation
   Once the installation is complete, open a command prompt or terminal window and type python --version to verify that Python has been installed correctly.

5. Installing pip using a Python script:
   Download the get-pip.py script from the official Python website.
   Open the terminal and navigate to the directory where you downloaded the script.
   Run the command: python get-pip.py
   Follow the prompts to complete the installation.

6. How to configure and install MySQL Database:
   Download the MySQL Installer: Visit the MySQL download page and download the MySQL Installer for Windows.
   Run the Installer: Double-click on the downloaded file to run the installer.
   Choose the Setup Type: Select the “Custom” setup type to customize the installation.
   Select the Products: Choose the products you want to install, such as MySQL Server, MySQL Workbench, and MySQL Shell.
   Configure the Installation: Choose the installation location, set the root password, and configure the database.
   Finish the Installation: Click “Finish” to complete the installation.

Configuring MySQL:
   After installation, you need to configure MySQL to secure your database. Follow these steps:
   i. Set the Root Password: Run the command mysql_secure_installation to set the root password and secure your database.
   ii. Create a New User: Create a new user account with a strong password to use for database access.
   iii. Grant Privileges: Grant the new user the necessary privileges to access and modify the database.
   iv. Create a Database: Create a new database and grant the new user access to it.

7. Setting up a development environment:
   Create a new project: Create a new project directory and initialize a new Git repository using git init.
   Install dependencies: Install the necessary dependencies for your project using npm or yarn.
   Create a package.json file: Create a package.json file that lists your project’s dependencies and scripts.
   Create a README.md file: Create a README.md file that provides information about your project.

To set up Docker, follow these steps:
   Step 1: Sign up for Docker Hub
   Sign in to Docker Hub and create a new account if you don’t already have one.
   On the Repositories page, select Create repository.
   Step 2: Install Docker
   Go to the Docker website and download the Docker file for your operating system (Windows, macOS, or Linux).
   Follow the installation instructions to install Docker on your machine.
   Step 3: Enable Hardware Virtualization
   For Windows, enable hardware virtualization in BIOS settings.
   For more information, see Virtualization.
   Step 4: Install Docker Desktop (for Windows)
   Download and install Docker Desktop for Windows.
   Follow the installation instructions to set up Docker Desktop.
   Step 5: Create a Dockerfile
   A Dockerfile is a text file that contains instructions for building a Docker image.
   Create a new file named Dockerfile in your project directory.
   Write the necessary instructions and commands in the Dockerfile to build your image.
   Step 6: Build and Run a Docker Image
   Use the docker build command to build your Docker image from the Dockerfile.
   Use the docker run command to run your Docker image.
   Step 7: Use Docker Compose
   Docker Compose is a tool for defining and running multi-container Docker applications.
   Create a docker-compose.yml file in your project directory to define your application’s services.
   Use the docker-compose up command to start your application.
   Step 8: Manage Docker Containers
   Use the docker ps command to list all running containers.
   Use the docker stop and docker rm commands to stop and remove containers.
   Use the docker exec command to execute commands inside a running container.

9. Extensions and plugins:
   To get started, you can use the official VSCode marketplace to find and install extensions: Head to the official VSCode marketplace to find extensions for VSCode, as there’s a huge collection of recommended extensions to browse.
   Check reviews, ratings, and downloads: Before installation, check the stats to see if it’s worth installing and read comments to look for issues or limitations.
   Search for extensions: Use the search bar to find specific extensions or browse through categories like “Web Development”, “Productivity”, or “Debugging”.
   Read descriptions and details: Read the descriptions and details of each extension to understand what it does and what it’s used for.
   Read reviews and ratings: Check the reviews and ratings from other users to get an idea of how well an extension works and what issues they may have experienced.
   Install extensions: Once you’ve found an extension you’re interested in, click the “Install” button to install it.
   Manage extensions: You can manage your installed extensions by going to the Extensions view in the left vertical menu and clicking on the “Extensions” tab.

Additionally, you can also explore extensions by category, such as:
   Web Development: Extensions for web development, such as HTML, CSS, and JavaScript.
   Productivity: Extensions for increasing productivity, such as code completion, debugging, and code refactoring.
   Debugging: Extensions for debugging, such as debugging tools, error analysis, and performance monitoring.
   Data Science: Extensions for data science, such as data visualization, machine learning, and big data analysis.

Challenges encountered during Developer environment setup:
1. Unfamiliarity with technical jargon used during some of the processes, for example git init used to initialize a repository on Git.
2. Downloading wrong installation media or Zip files for the softwares.

Solutions:
1. Utilize the internet to assist in some of the installation and configuration processes, for example ChatGPT OpenAI.
2. Read through the software documentation of the softwares to understand the setting up processes.
3. Check system requirements for specific softwares before downloading to ensure that your machine is compatible with the software.
4. Update the softwares regularly to ensure that they are up to date.