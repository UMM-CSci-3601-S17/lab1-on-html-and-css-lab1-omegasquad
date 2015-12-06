### Committing changes to your project
As your are working on your project, you will need to periodically commit changes that you have made.
Committing effectively means you are creating a local save of your current progress/project. Each commit records changes since the last commit, and the chain of commits represents the history of changes to your project!

> Protip: Frequent commits make everyone happy. Good commit messages keep your coworkers from silently cursing your name

- To commit changes from within a WebStorm project, go to "VCS" (Version Control Systems) and select "Commit Changes."

> Protip: The shortcut for committing is Ctrl + K

- Please **Carefully review the list of changes** that WebStorm will present you with.

> Protip: Select a changed file and use the "details" dropdown to view a detailed description of what was changed in that file

-  Write a **MEANingful** commit message when prompted.
-  Click "commit" (Not "commit and push", or "create patch" !)
- When adding, deleting, or renaming files in your project, you will have to do a couple special things. If you are unsure what to do here, please talk to Professor KK, or one of the lab assistants.

### Pulling in changes from GitHub
Before doing work on your project, or sending your committed changes up to GitHub, you will need to make sure your local copy of the project
is up-to-date with the copy that GitHub has. This is **Very Important** as others on your team may have sent changes of their own to GitHub since you started working.

> Protip: You should do this whenever starting work on the project or before adding your commits to GitHub

- To pull repository changes from GitHub to your local project, click "VCS" at the top of WebStorm.
- Open the "Git" sub-menu.
- Click the "Pull" button.
- Review the "branch" and "remote" fields.
  - Check that the remote is the URL of your repository on GitHub.
  - Check that the branch is correct. At this time, it should just be "master".
- We'll ignore the other pieces of this for now... At this time, hit "Pull".

> Protip: Make sure to commit local changes before pulling to ensure Git is happy.

> Protip: Get into a habit of **ALWAYS** pulling changes before Pushing (see below).

### Pushing your commits to GitHub
When you are done working or you want others to be able to see your changes, you will want to push your commits to GitHub.
This adds them to the ever-growing chain of commits for the repository on GitHub.

> Protip: Make sure you are certain of the commits you want to push to GitHub. Removing parts of a repository's history is a pain, and should be avoided at all costs.

- Once you hav some commits ready to push, click "VCS" at the top of WebStorm.
- Open the "Git" sub-menu.
- Click the "Push" button.

> Protip: The shortcut for pushing is Ctrl + Shift + K

- Review the list of commits that will be pushed.
  - You can view changes in a commit using the "Show Diff" (ctrl + D) icon in the upper-right corner.
- Once you are certain of your changes/commits, hit the "Push" button.

### Merging
If for some reason you come across this, see Professor KK or a lab assistant.