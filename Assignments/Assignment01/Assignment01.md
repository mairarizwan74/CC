Assignment 01
Git, Gitea, GitHub, Git LFS, and GitHub Pages
Student Name: Maira Rizwan
GitHub Username: mairarizwan74
Course: Cloud Computing
Assignment Number: 01
Deadline: 10 October 2026
The objective of this assignment is to learn how to install and use Gitea on an Ubuntu server, create and manage Git repositories, push a repository to both Gitea and GitHub, track large files using Git Large File Storage (Git LFS), and publish a personal portfolio using GitHub Pages.

Required Working Environments
Task	Environment
**Task 1: Gitea installation and Git operations	Ubuntu server and web browser
Task 2: GitHub repository and remote configuration	Ubuntu server and web browser
Task 3: Git LFS setup and large-file upload	Ubuntu server
Task 4: Portfolio and GitHub Pages	Web browser and local computer**
Final submission	Existing public GitHub repository named CC
Task 1: Install Gitea and Push a Repository
Objective

To install and run Gitea on an Ubuntu server, create a local Git repository, and push the repository to Gitea.

Procedure
Connect to the assigned Ubuntu server.
Update the Ubuntu package index.
Install Docker Engine and curl.
Install the Docker Compose plug-in.
Start Docker and configure the required user permissions.
Verify Git, Docker, and Docker Compose installations.
Clone the instructor-provided Gitea setup repository.
Start Gitea and PostgreSQL using the existing compose.yaml.
Verify that both containers are running.
Check the Gitea HTTP response and access Gitea through a web browser.
Complete the Gitea installation and create an administrator account.
Create an empty public repository named Assignment01.
Create a local Git repository on the Ubuntu server.
Create a README.md containing the student's full name and registration number.
Commit the README and configure the Gitea remote.
Generate a Gitea personal access token and authenticate securely.
Push the main branch to Gitea.
Verify the public repository and rendered README.
Required Screenshots
task1_gitea_running.png — Gitea and PostgreSQL running successfully.
task1_gitea_push.png — Successful push of the initial repository to Gitea.
task1_gitea_repository.png — Public Gitea repository displaying the README.
Result

To be completed after successfully installing Gitea, pushing the repository, and capturing the required screenshots.

Task 2: Push the Same Repository to GitHub
Objective

To connect the same local Git repository to GitHub and push the main branch to a second remote.

Procedure
Create an empty public GitHub repository named Assignment01.
Open the same local repository used in Task 1 on the Ubuntu server.
Add GitHub as the second remote named github.
Use git remote -v to verify the Gitea and GitHub remotes.
Ensure that remote URLs do not contain passwords or access tokens.
Push the main branch to GitHub using git push -u github main.
Open the GitHub repository in a web browser.
Verify the repository owner, repository name, public visibility, and README.
Required Screenshots
task2_remotes.png — Both Git remotes and their fetch and push URLs.
task2_github_push.png — Successful push to GitHub.
task2_github_repository.png — Public GitHub repository displaying the README.
Result

To be completed after successfully pushing the same local repository to GitHub and capturing the required screenshots.

Task 3: Track Three Large Files with Git LFS
Objective

To configure Git Large File Storage, track three .bin files larger than 100 MiB, and upload them to GitHub.

Procedure
Open the local Assignment01 repository on the Ubuntu server.
Initialize Git LFS using git lfs install.
Verify the installed Git LFS version.
Configure Git LFS to track .bin files using git lfs track "*.bin".
Verify the tracking rule in .gitattributes.
Create three files named large-file-1.bin, large-file-2.bin, and large-file-3.bin.
Set their sizes to 101 MiB, 102 MiB, and 103 MiB respectively.
Stage .gitattributes and the three large files.
Verify LFS tracking using git lfs ls-files --size.
Commit the changes.
Push the main branch to GitHub.
Verify that the LFS objects upload successfully.
Required Screenshots
task3_lfs_setup.png — Git LFS initialization, version, and .gitattributes rule.
task3_lfs_files.png — All three files and their sizes.
task3_lfs_push.png — Successful Git LFS object upload and Git push.
Result

To be completed after verifying that all three large files are tracked by Git LFS and successfully uploaded to GitHub.

Task 4: Create a Portfolio Using GitHub Pages
Objective

To create a personal portfolio or CV using HTML and CSS and publish it using GitHub Pages.

Procedure
Create a new public GitHub repository named mairarizwan74.github.io.
Create an index.html file containing the portfolio content.
Create a styles.css file to style the portfolio.
Include the required About Me, Education, Skills, and Projects sections.
Commit and push the files to the main branch.
Verify that both files are present in the public GitHub repository.
Open the repository settings.
Navigate to Settings → Pages.
Select Deploy from a branch.
Select the main branch and / (root) folder.
Save the settings and wait for successful deployment.
Open https://mairarizwan74.github.io/ and verify that the portfolio loads correctly.
Required Screenshots
task4_pages_repository.png — Portfolio repository showing index.html and styles.css.
task4_pages_deployment.png — GitHub Pages deployment status and website URL.
task4_portfolio_live.png — Published portfolio displaying the website URL and portfolio content.
Result

To be completed after successfully publishing the portfolio and verifying that the live website is accessible.

Assignment Summary

This assignment covers the practical use of Git, Gitea, GitHub, Git LFS, and GitHub Pages. It requires the creation of a Git repository on an Ubuntu server, configuration of multiple Git remotes, secure authentication, tracking and uploading large files, and publication of a static portfolio website.

The final submission must include the Markdown file, Word solution, PDF solution, and all twelve required screenshots inside the existing public CC repository.

Final Submission Checklist

Assignment01.md is present.

Assignment01_Solution.docx is present and opens correctly.

Assignment01_Solution.pdf is present and matches the Word solution.

The screenshots directory contains all twelve required screenshots.

Gitea and PostgreSQL have been started successfully.

The public Gitea Assignment01 repository has been verified.

The public GitHub Assignment01 repository has been verified.

Both Git remotes have been configured correctly.

Three files larger than 100 MiB have been tracked with Git LFS.

The LFS objects have been uploaded successfully.

The portfolio repository is public.

GitHub Pages deployment has succeeded.

The live portfolio URL works.

No screenshot exposes passwords, tokens, or private keys.

The complete assignment directory has been pushed to CC.

The required links have been submitted on Google Classroom.

Academic Integrity

All practical work and screenshots must be produced by the submitting student. The student should understand and be able to explain the commands, configuration, repository setup, LFS upload, and GitHub Pages deployment.

Note: Update the procedure and result sections to reflect the work actually completed. Add your registration number to the README and solution document before final submission.
