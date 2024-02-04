Create a new folder on your local machine and name it .
Open a terminal or  and navigate to the folder you just 
Initialize the folder as a Git repository by running the command git init. This will create a hidden .git folder that stores the history of your project.
Create a new file named README.md inside the folder and write some content for it. You can use any text editor or IDE to do this. For example to use vs code write code file path
Project as the first line of the file.
Add the README.md file to the staging area by running the command git add README.md. This will tell Git that you want to track the changes of this file.
Commit the changes to the local repository by running the command git commit -m "Add README.md file". This will create a snapshot of the current state of your project and attach a message describing what you did. The message should be descriptive and concise if your message to long preferd use editor inested -m just write commit and your defult editor will open auto this is more practical in real world project note: i prefer using vs code insted vim I find it kinda confusing

Create a new repository on GitHub . You can choose any name, description, and visibility for your repository. For example, you can name it any no thing and make it public.
Copy the URL of your GitHub repository from the web browser. For example, https://github.com/username/my-project.git.
Link your local repository to the remote repository by running the command git remote add origin -_-. Replace -_- with the URL you just copied. This will tell Git where to push and pull your changes from.
Push your changes to the remote repository by running the command git push -u origin main. This will upload your local commits to the GitHub server and set the main branch as the default branch for future pushes.