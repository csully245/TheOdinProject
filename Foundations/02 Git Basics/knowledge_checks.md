# Foundations / Prerequisites Knowledge Checks

## 3.1 Introduction to Git

1. What kind of program is Git?

    Application.

2. What are the differences between Git and a text editor in terms of what they save and their record keeping?

    A text editor saves a single version, while Git records the entire history and metadata on the edits.

3. Does Git work at a local or remote level?

    Local.

4. Does GitHub work at a local or remote level?

    Remote.

5. Why is Git useful for an individual developer?

    Checking and restoring past versions, trying things out in a new branch.

6. Why are Git and GitHub useful for a team of developers?

    Tracking who did what, managing merging each dev's version, and storing the records across a distributed system.

## 3.2 Git Basics

1. How do you create a new repository on GitHub?

    \+ > New Repository

2. How do you copy a repository onto your local machine from GitHub?

    Hit the green Clone button, select SSH, run $git clone < url >

3. What is the default name of your remote connection?

    origin

4. Explain what origin is in git push origin main.

    A reference to the remote repository to be updated to match the local repository.

5. Explain what main is in git push origin main.

    The branch to be pushed to the remote repository.

6. Explain the two-stage system that Git uses to save files.

    Commit: A snapshot is saved to the local repository.

    Push: The remote repository is updated to match the local repository.

7. How do you check the status of your current repository?

    `git status`

8. How do you add files to the staging area in git?

    `git add < files to be added > `

9. How do you commit the files in the staging area and add a descriptive message?

    `git commit -m < message > `

10. How do you push your changes to your repository on GitHub?

    `git push origin main`

11. How do you look at the history of your previous commits?

    `git log`