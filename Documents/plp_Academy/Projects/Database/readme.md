# First time setup (if you haven't configured Git before)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Initialize your repository (if not already initialized)
cd your-assignment-directory
git init

# Add your files
git add .

# Commit your changes with a meaningful message
git commit -m "Complete assignment submission"

# Add the GitHub Classroom repository as remote
# The URL will be provided when you accept the assignment
git remote add origin https://github.com/your-classroom-org/assignment-repo-name.git

# Push your code to GitHub
git push -u origin main

# If your default branch is 'master' instead of 'main', use:
# git push -u origin master

# If you need to update your submission later:
git add .
git commit -m "Update assignment with changes"
git push

# If you want to check the status of your files
git status

# If you want to see what changes you've made
git diff

# If you need to pull any updates from the repository
git pull origin main