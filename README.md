# first-project

<-- This is my first project folder. My first personal project learning actual web dev.-->

Update your README.md file inside VS Code to add some text and then save the file. Run git status, and you should see that Git has tracked your changes and says the README.md file has been modified. This means your changes are ready to stage.
Stage the file using git add README.md, commit using git commit -m "update README.md", and then push to the remote using git push.
Refresh your browser on GitHub, and you should now see the updates you made to your README.md file showing on GitHub!



Set up a repo on GitHub
Once you're comfortable with the starter files, it's time to set up a Git repo and push it to GitHub. You'll do this in the same way as outlined in the previous step of this learning path:

Open the terminal (you can do this within VS Code by selecting the View menu and then Open Terminal).

Type git init to initialize a git repo.

Stage the files in the folder with git add .

Commit the files with git commit -m "Initial commit"

Create an empty repo on GitHub, giving it a meaningful name.

Copy the commands from the “…or push an existing repository from the command line” section on GitHub, which will look something like this:

git remote add origin <link to your repo>
git branch -M main
git push -u origin main
Paste those commands in your terminal on your laptop.

Congratulations, you've set up your project with Git and GitHub! You should see the project files if you return to your GitHub repo and refresh the page. As you work through your project, make sure you track the changes:

git add <file or folder name> to stage files and folders
git commit -m "Commit message" to commit the staged files
git push to push the commit to GitHub