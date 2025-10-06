# warmup-first-repo

Firstly I learned about 366pi.tech in which their core mission is to help businesses achieve sustained growth by integrating technology with sustainability, a concept they refer to as "digital sustainability" and there were 3 key takeaways
•	Through SharePoint services 366pi have enabled customers with selective process transformation through web parts development for functionality enhancement, intelligent content management, real-time business intelligence, and seamless collaboration.
•	Focus on Sustainability: A major and unique aspect of 366pi's work is its emphasis on sustainability. They have developed a proprietary framework called the "Digital Sustainability Alignment Model" (D-SAM) to help companies integrate sustainability and technology for growth.
•	Blockchain Consulting and Development: Blockchain consulting service is helping businesses identify specific problem areas where blockchain could be leveraged as well as incorporate blockchain as a part of the digital transformation journey. Optimize enterprise business case through custom built solutions.
Secondly I learned about Flocard.It is a digital business card app that goes beyond just networking - it's an ecosystem that supports sustainable development goals, climate action, and sustainability.3 key takeaways from FloCard app are:
•	Better Planet Together Initiative: FloCard has a campaign called #BetterPlanetTogether, which encourages users to contribute to a greener future.
•	For Businesses, it is designed to maximize ecological and carbon capture impacts, aligning directly with your net zero goals
•	Sustainability Dashboard: The platform offers a business dashboard with advanced analytics and reporting to help companies track and manage their environmental footprint.


Git's Core Concepts: The Basics
Git operates on a three-stage model: the working directory, the staging area (or index), and the local repository.

Staging: Before you commit a change, you must add it to the staging area. The git add command is used to select specific file changes to be included in the next commit. This gives you granular control over what you want to save. For example, you can make several changes but only stage and commit one of them.

Commits: A commit is a snapshot of the files in your staging area at a specific point in time. The git commit command creates a new commit in your local repository's history. Each commit has a unique identifier (a hash) and a message that describes the changes. Think of a commit as a "save point" in your project's history.

Push and Pull: These commands are used to interact with a remote repository (a version of your project hosted on a server, like GitHub or GitLab).

Push: The git push command uploads your local commits to the remote repository, making them available to other collaborators.

Pull: The git pull command fetches changes from the remote repository and merges them into your local branch, bringing your local copy up to date. The pull command is a combination of git fetch (downloads the changes) and git merge (integrates them into your code).

Merge: The git merge command integrates changes from one branch into another. For example, after finishing a new feature on a feature branch, you would merge it into the main or develop branch. If both branches have changes to the same lines of code, a merge conflict may occur, which you must manually resolve.

Common Git Branching Strategies
Branching is a core feature of Git that allows developers to work on new features or bug fixes in isolation from the main codebase. Branching strategies are a set of rules for how to use and manage these branches.

main or master: This is the primary branch. The code on this branch should always be stable and ready for deployment to a production environment.

dev or develop: This branch is for ongoing development. New features are typically merged here first for testing and integration before being merged into the main branch.

feature/*: These are short-lived branches created for a specific feature or task. A descriptive name, like feature/add-user-authentication, is used. Once the feature is complete, the branch is merged into dev and then deleted. This is a key part of most modern workflows, like GitFlow and GitHub Flow.

What Git Solves in Collaborative Development
Before Git, a common problem was developers overwriting each other's code, leading to lost work and frustration. Git's distributed nature and powerful features solve several critical problems in collaborative environments:

Prevents Overwriting Code: Git allows multiple people to work on the same project simultaneously without stepping on each other's toes. Branches create isolated workspaces, and Git's merging capabilities handle integrating those changes.

Provides a Complete History: Every commit creates a detailed record of who made a change, when they made it, and why. This allows teams to review, revert, or compare any past version of the code, making it easy to fix bugs or undo unwanted changes.

Facilitates Code Reviews: Platforms like GitHub and GitLab use Git's branching model to enable pull requests (or merge requests). This process allows developers to discuss and review proposed changes before they are merged into the main codebase, which improves code quality and catches bugs early.

Enables Offline Work: Because every developer has a full copy of the entire repository on their local machine, they can make commits and work on the project even without an internet connection.

Improves Team Communication: The process of committing with descriptive messages and creating pull requests promotes clear communication and provides context for every change, ensuring everyone on the team understands the project's evolution.
