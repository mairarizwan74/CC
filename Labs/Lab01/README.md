Lab 01: GitHub Identity, Student Portal Registration, and Ubuntu Server Installation

Lab Objective

In this lab, you will create and correctly configure your GitHub account, register yourself in the Student Marks Portal, install Ubuntu Server in VMware Workstation Pro, verify your required Linux identity, and connect to the server remotely from Windows.

Important Identity Requirement

Your identity must remain consistent throughout this lab:

Enter your complete actual name in your GitHub profile.

Choose a professional GitHub username related to your actual name.

Use the same GitHub account to sign in to the Student Marks Portal.

Enter your actual registration number, course code, and section in the portal.

Use your exact GitHub username as your Ubuntu username.

Use ubuntu as the Ubuntu server name.

Your Ubuntu terminal prompt must follow this pattern:

<github-username>@ubuntu:~$


For example, if the GitHub username is waqassaleem97, the terminal prompt should be:

waqassaleem97@ubuntu:~$


Required Folder Structure

The README.md file and the instructional images are provided by the instructor. You must create the screenshots directory and prepare your own Lab1_Solution.pdf.

Your completed Lab 01 directory must follow this structure:

CC/
└── Labs/
    └── Lab01/
        ├── README.md
        ├── Lab1_Solution.pdf
        └── screenshots/
            └── (screenshots of your completed tasks)


Follow these rules:

Save every screenshot of your work inside Labs/Lab01/screenshots/.

Use the exact screenshot filenames specified in this README.

Create Lab1_Solution.pdf yourself after completing the lab.

Add your screenshots to Lab1_Solution.pdf in the same order as the tasks.

The Grade Approved Students GitHub Actions workflow checks the screenshots directory, not the images embedded only in the PDF.

Task List

Getting Started

Task 1: Create and Configure Your GitHub Account

Task 2: Register in the Student Marks Portal

Task 3: Download VMware Workstation Pro and Ubuntu Server

Task 4: Create the Ubuntu Server Virtual Machine

Task 5: Choose the Installation Language

Task 6: Configure the Keyboard Layout

Task 7: Choose the Ubuntu Server Installation Type

Task 8: Configure the Network

Task 9: Configure Storage

Task 10: Select the Installation Disk

Task 11: Review the Partitions

Task 12: Confirm the Storage Changes

Task 13: Configure the Ubuntu Profile

Task 14: Complete the Software Installation

Task 15: Reboot and Verify the Ubuntu Identity

Task 16: Find the Ubuntu Server IP Address

Task 17: Connect to Ubuntu Server from Windows

Task 18: Prepare Lab1 Solution PDF

Final Submission Checklist

Getting Started

Create the following directory inside your CC repository:

Labs/Lab01/screenshots/


Save a screenshot showing the created directory structure as lab01_folder_structure.png.

Read the complete task list before beginning the installation.

Task 1: Create and Configure Your GitHub Account

Open GitHub Sign Up and create your personal GitHub account.

Use your own email address and actual identity.

Do not create an account using another student's information.

Choose a professional GitHub username related to your actual name.

Do not use spaces in the GitHub username.

Prefer lowercase letters and numbers because the same username will be used in Ubuntu.

Save a screenshot clearly showing your profile name and GitHub username as github_profile.png.

Open GitHub > Settings > Public profile.

Enter your complete actual name in the Name field.

Save a screenshot showing the completed Name field as github_actual_name.png.

Do not include your password, access token, recovery codes, or other private credentials in any screenshot.

Task 2: Register in the Student Marks Portal

Open the Student Marks Portal.

Save a screenshot of the portal login page as portal_login_page.png.

Select Continue with GitHub and sign in using the GitHub account created in Task 1.

Enter your actual registration number using the format provided by your instructor, for example:

2024-BSE-00


Select the correct course code.

Select your actual section, either A or B.

Review your information and submit the enrollment for approval.

Save a screenshot showing your GitHub profile information inside the portal as portal_github_profile.png.

Save a screenshot of the submitted or pending enrollment as portal_enrollment_submitted.png.

A registration number belongs to only one student. Never enter another student's registration number.

Task 3: Download VMware Workstation Pro and Ubuntu Server

Download and install VMware Workstation Pro on your Windows computer.

If VMware Workstation Pro is already installed, open it and verify that it works.

Save a screenshot showing VMware Workstation Pro running as vmware_workstation.png.

Open the Ubuntu Server download page and download the latest Ubuntu Server LTS ISO.

Save a screenshot showing the downloaded Ubuntu Server ISO filename as ubuntu_server_iso.png.

Confirm that at least 20 GB of free storage is available for the Ubuntu Server virtual machine.

Save a screenshot showing the available storage as available_storage.png.

Task 4: Create the Ubuntu Server Virtual Machine

Open VMware Workstation Pro and select Create a New Virtual Machine.

Save a screenshot of the New Virtual Machine Wizard as vm_creation_wizard.png.

Select Typical (recommended) as the virtual machine configuration.

Save a screenshot showing this selection as vm_typical_configuration.png.

Select Installer disc image file (ISO) and browse to the Ubuntu Server ISO downloaded in Task 3.

Save a screenshot showing the selected Ubuntu ISO path as vm_ubuntu_iso_selected.png.

Allocate at least 20 GB of virtual disk space and complete the virtual machine wizard.

Save a screenshot showing the final virtual machine configuration as vm_configuration_summary.png.

Power on the virtual machine and wait for the Ubuntu Server installer to start.

Save a screenshot of the Ubuntu Server boot screen as ubuntu_installer_boot.png.

Instructional reference

The following image is provided to help you recognize the Ubuntu Server boot screen:

Ubuntu Server boot screen

Task 5: Choose the Installation Language

Use the arrow keys to select the required installation language.

Save a screenshot showing the selected language as ubuntu_language.png.

Press Enter to continue.

Instructional reference

Ubuntu Server language selection

Task 6: Configure the Keyboard Layout

Select the keyboard layout that matches your keyboard.

Save a screenshot showing the selected keyboard layout as ubuntu_keyboard_layout.png.

Select the appropriate keyboard variant.

Save a screenshot showing the selected keyboard variant as ubuntu_keyboard_variant.png.

Select Done to continue.

Instructional references

Ubuntu keyboard layout

Ubuntu keyboard variant

Task 7: Choose the Ubuntu Server Installation Type

Select the normal Ubuntu Server installation option.

Do not select a MAAS installation unless your instructor specifically asks for it.

Save a screenshot showing the selected installation type as ubuntu_installation_type.png.

Continue to the next installer screen.

Instructional reference

Ubuntu Server installation type

Task 8: Configure the Network

Review the network interface detected by the Ubuntu Server installer.

Save a screenshot showing the detected network interface as ubuntu_network_interface.png.

Confirm that the interface has received an IP address automatically through DHCP.

Save a screenshot showing the assigned network address as ubuntu_installer_network.png.

Continue when the network configuration is correct.

Instructional reference

Ubuntu Server network configuration

Task 9: Configure Storage

Select the guided storage option to use the VMware virtual disk.

Save a screenshot showing the selected guided storage option as ubuntu_guided_storage.png.

Review the storage configuration before continuing.

Save a screenshot of the storage configuration as ubuntu_storage_configuration.png.

Use only the VMware virtual disk created for this lab. Selecting or formatting the wrong physical disk can destroy existing data.

Instructional reference

Ubuntu Server storage configuration

Task 10: Select the Installation Disk

Select the virtual disk created for the Ubuntu Server virtual machine.

Save a screenshot showing the selected disk as ubuntu_selected_disk.png.

Check the displayed disk size and make sure it is the correct VMware virtual disk.

Save a screenshot showing the disk name and size as ubuntu_disk_details.png.

Instructional reference

Ubuntu Server disk selection

Task 11: Review the Partitions

Review the partition layout proposed by the Ubuntu Server installer.

Save a screenshot showing the proposed partitions as ubuntu_partition_layout.png.

Confirm that the partitions belong to the VMware virtual disk.

Select Done only after reviewing the complete layout.

Instructional reference

Ubuntu Server partition layout

Task 12: Confirm the Storage Changes

Read the destructive-action warning carefully.

Save a screenshot showing the final warning as ubuntu_storage_warning.png.

Confirm the changes only when you are certain that the VMware virtual disk is selected.

Save a screenshot showing the confirmation selection as ubuntu_storage_confirmed.png.

Instructional reference

Ubuntu Server final storage confirmation

Task 13: Configure the Ubuntu Profile

Complete the Ubuntu profile using the following required values:

Installer field

Required value

Your name

Your complete actual name

Your server's name

ubuntu

Pick a username

Your exact GitHub username

Choose a password

A secure password you can remember

Enter your complete actual name in the Your name field.

Save a screenshot showing the entered name as ubuntu_actual_name.png.

Enter ubuntu in the Your server's name field.

Save a screenshot showing the server name as ubuntu_server_name.png.

Enter your exact GitHub username in the Pick a username field.

Save a screenshot showing the Ubuntu username as ubuntu_username.png.

Choose and confirm a secure password.

Do not expose your password in any screenshot.

Review all profile fields before continuing.

Save a screenshot of the completed profile page as ubuntu_profile_setup.png.

Task 14: Complete the Software Installation

Wait while Ubuntu Server installs the required software.

Save a screenshot showing the installation progress as ubuntu_installation_progress.png.

Do not power off the virtual machine during the installation.

Wait until the installer reports that the installation is complete.

Instructional reference

Ubuntu Server software installation

Task 15: Reboot and Verify the Ubuntu Identity

When the installation completes, select Reboot Now.

Save a screenshot of the installation-complete screen as ubuntu_installation_complete.png.

Disconnect the Ubuntu ISO if VMware asks you to remove the installation media.

Allow the installed Ubuntu Server to start.

Save a screenshot showing the Ubuntu login screen as ubuntu_login_screen.png.

Sign in using the Ubuntu username and password configured in Task 13.

Save a screenshot showing the successful terminal login as ubuntu_terminal_login.png.

Verify that the terminal prompt follows this format:

<github-username>@ubuntu:~$


Save a clear screenshot showing the complete prompt as ubuntu_identity_verified.png.

Instructional reference

Ubuntu Server installation complete

Task 16: Find the Ubuntu Server IP Address

Run the following command inside Ubuntu Server:

ip addr

Save a screenshot showing the command and its output as ubuntu_ip_addr_command.png.

Find the IPv4 address shown after inet for the active network interface.

Do not use 127.0.0.1; it is the loopback address.

Save a screenshot clearly showing the correct IPv4 address as ubuntu_ip_address.png.

Keep your <github-username>@ubuntu prompt visible in the screenshot.

Task 17: Connect to Ubuntu Server from Windows

Keep the Ubuntu Server virtual machine powered on.

Open Command Prompt or PowerShell on Windows.

Run the following SSH command, replacing the placeholders with your Ubuntu username and server IP address:

ssh <github-username>@<ubuntu-server-ip>

Save a screenshot showing the SSH command as windows_ssh_command.png.

Type yes if you are asked to accept the server fingerprint.

Save a screenshot showing the accepted fingerprint as windows_ssh_fingerprint.png.

Enter your Ubuntu password and complete the remote login.

The password will not appear while you type; this is normal.

Do not expose your password in a screenshot.

Save a screenshot showing the successful SSH session as windows_ssh_login.png.

Verify that the remote prompt displays <github-username>@ubuntu.

Save a clear screenshot showing the remote prompt as windows_ssh_identity.png.

If SSH is unavailable, install and start OpenSSH Server inside Ubuntu:

sudo apt update
sudo apt install -y openssh-server
sudo systemctl enable --now ssh

Task 18: Prepare Lab1 Solution PDF

Create a new document and add a title page containing:

Lab number and title

Your complete actual name

Your registration number

Course code

Section

GitHub username

Save a screenshot of the completed title page as solution_title_page.png.

Add headings for Tasks 1 through 17.

Under each heading, insert the screenshots for that task in the same order used in this README.md file.

Add a short caption below every screenshot explaining what it demonstrates.

Check that every screenshot is clear and readable.

Export the completed document using this exact filename:

Lab1_Solution.pdf


Save a screenshot showing the exported PDF as lab1_solution_pdf.png.

Place the PDF at:

Labs/Lab01/Lab1_Solution.pdf


Keep all original screenshots inside Labs/Lab01/screenshots/ for automatic grading.

Screenshot Rules

Every screenshot must be created from your own work.

Save every screenshot inside Labs/Lab01/screenshots/.

Use the exact filename written after each step.

Screenshots must be clear and readable.

Show the relevant window, command, output, or identity information.

Do not crop out the terminal prompt when it is required.

Do not edit a screenshot to add, remove, or replace evidence.

Do not copy or reuse another student's screenshots.

Do not expose passwords, access tokens, recovery codes, or private keys.

The instructional images inside images/install-ubuntu-server/ are examples and must not be submitted as your own evidence.

Missing, unclear, incorrectly named, misplaced, edited, or copied evidence may receive zero marks for the affected task.

Final Submission Checklist

README.md remains inside Labs/Lab01/.

The instructor-provided images/install-ubuntu-server/ directory remains unchanged.

Lab1_Solution.pdf was created by me and placed inside Labs/Lab01/.

Every original evidence screenshot is inside Labs/Lab01/screenshots/.

My GitHub profile contains my complete actual name.

My GitHub username is professional and suitable as an Ubuntu username.

I used the same GitHub account for the Student Marks Portal.

I entered my correct registration number, course code, and section.

Ubuntu Server was installed inside VMware Workstation Pro.

My Ubuntu username exactly matches my GitHub username.

My Ubuntu server name is ubuntu.

My local terminal prompt shows <github-username>@ubuntu.

I identified the correct Ubuntu Server IPv4 address.

I successfully connected to Ubuntu Server from Windows using SSH.

My remote SSH prompt shows <github-username>@ubuntu.

Every screenshot uses the exact required filename.
