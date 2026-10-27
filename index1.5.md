Step 1: Create a New Public Repository on GitHub
Log in to your GitHub account.

In the top-right corner, click the + icon and select New repository.

Name your repository (e.g., web-development-practice).

Select Public.

Important: Leave the options to Add a README file, Add .gitignore, and Choose a license unchecked (since you already have a local Git repository with files).

Click Create repository.

Step 2: Connect Your Local Repository to GitHub
Open your terminal and navigate to your local project folder (e.g., web-development-practice).

Copy the remote URL from your newly created GitHub repository page. It will look like [https://github.com/your-username/web-development-practice.git](https://github.com/your-username/web-development-practice.git).

Link your local repository to GitHub by running:

Bash
git remote add origin https://github.com/your-username/web-development-practice.git
Ensure your main branch is named main:

Bash
git branch -M main
Step 3: Push Your Files to GitHub
Push your local commits up to GitHub for the first time using:

Bash
git push -u origin main
(If prompted, log in with your GitHub credentials or Personal Access Token).

Step 4: Add a New File and Push the Second Commit
To satisfy requirement #5 (adding a new file and making a second push):

Create a new file in your project folder named README.md.

Add a short description inside it:

Markdown
# Web Development Practice
This repository contains my web development coursework and exercises.
Stage, commit, and push this new file:

Bash
git add README.md
git commit -m "docs: add README.md file"
git push origin main
Step 5: Verify on GitHub
Refresh your repository page on GitHub.

Verify that your files (index.html, README.md, etc.) are visible.

Click on the Commits tab (near the top left, showing something like "X commits") to confirm your commit history is recorded properly.

Submission
Copy the URL of your public GitHub repository from your browser address bar (e.g., [https://github.com/your-username/web-development-practice](https://github.com/your-username/web-development-practice)) and submit that link as your assignment!