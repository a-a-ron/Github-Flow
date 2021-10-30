# Understanding the GitHub Flow

<img width="1041" alt="Screen Shot 2021-10-30 at 4 49 45 PM" src="https://user-images.githubusercontent.com/6351798/139560548-772d637a-394f-4382-936c-319995e12d43.png">


## What is the GitHub Flow?

The GitHub flow is a lightweight branch-based workflow that supports teams and projects were deployments are made regularly. Since the GitHub flow is based on the Git system, it inherits all the powerful featuers that Git offers. Since Git is complex and often confusing, the GitHub flow helps to simplify the development process and allows for simultaneously multi-branch development.

### Create a Branch

Creating a branch off of the master branch gives you an environment to test out new ideas. Since you branch off of master, you get a complete working copy of the entire project without testing these ideas on the branch you deploy to production. This makes it safe for feature development as well as creating a great environment for other developers to test out new ideas without making conflicting changes.  

### Add Commits

Once a branch is created, you make edits to files and folders in the project by making commits to the feature branch. This keeps track of all your progress as you make edits. It's best to commit early and often for a transparent historical record of the different changes you made. It's also very helpful if one of the changes you committed is something you want to revert. Instead of reverting the entire commit that has other changes, if you committed early and often, you can just revert that specific commit while keeping the other commits. 

### Open a Pull Request

When you're ready to start a discussion about the changes you made you need to open a Pull Request. A Pull Request is basically saying you intend to merge these changes into the master branch. At this point, anyone who has access to view this repository can see your Pull Request. You can open a Pull Request at anytime during the development stage.

### Review and Discuss Changes

Once the Pull Request has been opened, the person or team reviewing your changes can then make suggestions or ask questions about your changes. You can also continue to commit changes during this change to respond to the comments and discussions. 

### Merge into Master

Once the changes have been reviewed and approved, you can merge your Pull Request into the master branch. By doing so, this takes the changes in your feature branch and integrates them into the master branch. Once merged, Pull Requests preserve a record of the changes you committed to the master branch. You can go back at any time and review the changes.

