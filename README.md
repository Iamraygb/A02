# A02
This is for Ray's IS 117 Fall 2026 Assignment
Git, Webstorm, and GitHub tutorial assignment

## GIT, GitHub, and Webstorm Tutorial
At this point, I already had a GitHub account so I did not need to do that for this tutorial

### Installing Git
To Install Git. I hit the windows key and searched "Git for Windows" Upon clicking the first option I saw, which was the gut-scm.com page
I clicked on the link and it brought me to the download page. I then hit download the windows installer.
Once downloaded, I hit Run it. I lef the installation options at default, continued through the installer and finished installations.
I took a step to confirm whether the Git actually worked by openning my command prompt on windows and typing git --version. Doing this reported to me the version of git I was running.
This proved to me that my git was opeerational.
### Installing Webstorm
To install webstorm, I searched for JetBrains Webstorm download on Google, which led me to the official JetBrains website.
I hit install JetStorm for Windows. I went through the installation process, and then opened the .exe file

### Making a Repository
In my GitHub account, I clicked the plus icon ont he upper right side, and then hit new repository. 
I named the repository A02 as requested by the assignment. I set the repository to public, and I set the option README file to ON. I did not bother about gitignore. I clicked Create Repository

### Cloning a Repository
In my new A02 repository page, I hot the green code button, and selected HTTPS; it was already selected. I then copied the repository URL.
I then proceeded to the webstorm Welcome Screen to which there was a button that said, clone repository. I pasted the GitHub URL I had copied earlier. When looking a the directory field I noticed it had made my online github repository local.
I hit clone. I clicked on that button, and it eventually gave me the option to log into my GitHub account for authorization.
I logged into my github account and gave webstorm authorization.
### Making Changes
 I made my first edit to the README.md by switching from the preview mode to the edit mode where I added the heading # A02, added markdown text: Git, Webstorm, and GitHub tutorial assignment.
I saved this by hitting Ctrl + S
### Committing Changes
In webstorm, I looked for the commit section by hitting the main dropdown then clicking on commit. This was on the top left of the screen.
For proceeding with commit, I needed to leave a commit message, so I wrote "Task: Create README.md"
Then I hit commit.
### Pushing Changes to GitHub
After doing this, in the Webstorm I hit push, I then notived my recent commit listed
I went back on my Github online account and noticed its history had updated. The commit message seemed to have annotated some checkpoint.

## Glossary

-**Branch**:
A separate line of development inside the same project. Right now I am in the same branch the ony one I've used. But if I created another branch, I could experiment  with changes, without affecting the original branch
-**Clone**:
Cloninig is what you do when I took A02 repository form GitHub anf brought  a connected copy onto my computer using webstorm. It doesn't just download thr files, Git also helped remember where the onlien repository came from.
-**Commit**:
A commit is a recorded checkpoint in your project's history. 
-**FETCH**:
Fetch, means asking GitHub are there any changes online that U don't have locally?" Git downloads information about those changes, but it does not automatically combine them with my files
-**GIT**:
Git is the version control system running on my computer. I had installed it earlier for this assignment. It tracks changes, creates commits, manages branches, merges, work, and communicates with remote repositories
-**Github**:
GitHub is the online service where the git repository is hosted. My A02 page on GitHub is the online version
-**Merge**:
Merging happesn when Git connects my online line of work wiht my local one. I actually experienced this, when Webstorm  tol me my push was rejected because GitHub had changes that I didn't have locally, I clicked Merge
-**Merge Conflict**:
A Merge conflict happens when Git cannot safely decide whihc twwo versions of the same content shoudl be combined. Git might stop you and ask you which version should remain
-**Push**:
Push sends commits form my local GitHub on my computer to the remote repository

-**Pull**:
Pull brings changes from the remote GitHub repository down to the local and then integrates it into my current work
-**Remote**:
A remote is a Gut repository located somewhere other than my local computer, usually on a service like GitHub
-**Repository**:
A repository is like a folder. It is the project being tracked by Git, including fils, and change history.
## References
- Git. "Git for Windows." https://git-scm.com/download/win
- JetBrains. "Download WebStorm." https://www.jetbrains.com/webstorm/download/
- GitHub. "GitHub." https://github.com/