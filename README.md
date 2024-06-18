[![Review Assignment Due Date(https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15242586&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):

   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   1. **Visited the Windows 11 Download Page:**
      - I went to [Windows 11 Download](https://www.microsoft.com/software-download/windows11).

   2. **Downloaded Windows 11:**
      - I clicked on "Download Now" and saved the Media Creation Tool (MediaCreationToolW11.exe) to my computer.

   3. **Ran the Installation Tool:**
      - I double-clicked on MediaCreationToolW11.exe to start it and accepted the License terms.

   4. **Created Installation Media:**
      - I selected "Create installation media for another PC."
      - I chose the language, edition, and architecture (64-bit or 32-bit) for Windows 11.
      - I decided to use a USB flash drive.

   5. **Followed On-Screen Instructions:**
      - I inserted a USB flash drive (at least 8GB) and followed the prompts to create the installation media.
      - I restarted my computer and booted from the USB drive for a fresh install.
      - I followed the on-screen instructions to complete the installation.

2. Install a Text Editor  or Integrated Development Environment (IDE):

   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   ### Downloaded and Installed Visual Studio Code

   1. **Visited the Visual Studio Code Download Page:**
      - I went to [Visual Studio Code Download](https://code.visualstudio.com/Download).

   2. **Downloaded Visual Studio Code:**
      - I selected my OS (Windows) and downloaded the installer (VSCodeUserSetup.exe).

   3. **Ran the Installation Wizard:**
      - I double-clicked on the downloaded installer to run it.

   4. **Followed Installation Prompts:**
      - I chose where I wanted to install Visual Studio Code.
      - I selected additional tasks like adding it to PATH.
      - I clicked "Next" and then "Install."

   5. **Opened Visual Studio Code:**
      - I launched Visual Studio Code from my desktop.

3. Set Up Version Control System:

   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
### Installed Git

   1. **Downloaded Git:**
      - I went to [Git Download](https://git-scm.com/) and downloaded the installer for Windows.

   2. **Ran the Git Installer:**
      - I double-clicked on the installer to run it and accepted the default settings, making sure "Use Git from the command line and also from 3rd-party software" was selected.

   3. **Configured Git:**
      - I opened Command Prompt and set my Git username:
      ```sh 
      git config --global user.name "ERisuna"
      ```
      - I set my Git email address:
      ```sh
      git config --global user.email "crshikwambani@gmail.com"
       ```

4. Install Necessary Programming Languages and Runtimes:

  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
### Installed Python

   1. **Downloaded Python:**
      - I visited [Python Download](https://www.python.org/downloads/) and downloaded the latest version for Windows.

   2. **Ran the Python Installer:**
      - I double-clicked on the downloaded installer to run it.

   3. **Configured Python Installation:**
      - I checked the box that says "Add Python to PATH."
      - I clicked "Install Now" and followed the prompts.

   4. **Verified Python Installation:**
      - I opened Command Prompt and typed:
      ```sh
      python 3.4 version
      ```                       
      - I confirmed that Python was correctly installed and the version number was displayed.

5. Install Package Managers:

   If applicable, install package managers like pip (Python).
   ### Installed pip

   - Since pip is included with Python installations from Python 3.4 onwards, I checked by typing:
   ```sh pip 3.4 version
- Pip was already installed, so no further action was needed.

6. Configure a Database (MySQL):

   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   ### Downloaded and Installed MySQL

   1. **Visited the MySQL Download Page:**
      - I went to [MySQL Download](https://dev.mysql.com/downloads/mysql/).

   2. **Downloaded MySQL Installer:**
      - I chose the appropriate installer for Windows.

   3. **Ran the MySQL Installer:**
      - I double-clicked on the installer to run it.

   4. **Selected Installation Type:**
      - I chose "Custom" to select specific components.

   5. **Installed MySQL Server:**
      - I selected MySQL Server and MySQL Workbench from the list of available products.

   6. **Configured MySQL:**
      - I followed the installation prompts to set up MySQL Server, set a root password, and configured server settings.

7. Set Up Development Environments and Virtualization (Optional):

   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   ### Installed Docker (Optional)

   1. **Visited the Docker Download Page:**
      - I went to [Docker Download](https://www.docker.com/products/docker-desktop).

   2. **Downloaded Docker Desktop:**
      - I chose the Docker Desktop installer for Windows.

   3. **Ran the Docker Installer:**

   4. **Verified Docker Installation:**
      - I opened Command Prompt and typed:
        ```sh
      docker --version
     ```
 - I confirmed that Docker was correctly installed and the version number was displayed.

8. Explore Extensions and Plugins:
   
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   ### Installed Visual Studio Code Extensions

   1. **Opened Visual Studio Code:**
      - I launched Visual Studio Code.

   2. **Installed Extensions:**
      - I clicked on the Extensions icon on the side (or pressed `Ctrl+Shift+X`).
      - I searched for and installed useful extensions like:
      - **Python**: For Python development.
      - **GitLens**: Enhances Git capabilities.
      - **Prettier**: Code formatter.
      - **ESLint**: For JavaScript linting.
      - **Flutter**: For Flutter development.
      - **Dart**: For Dart language support.

   3. **Installed Extensions:**
      - I clicked "Install" next to each extension.

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
