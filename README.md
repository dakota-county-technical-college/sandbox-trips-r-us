# sandbox-trips-r-us

Test anything out in this sandbox that involves the project: trips-r-us

## Mission Brief: GitHub Collaboration in Sandbox-Trips-R-Us

Your mission, should you choose to accept it, involves several key tasks to help you become familiar with GitHub within the context of our protected branch structure. The primary goal is to open the README in the root of the project `sandbox-trips-r-rus` and add your name under the "Developers" section. This will involve creating a new branch, making your changes, and submitting these changes through a pull request. As our `dev`, `stage`, and `main` branches are protected, direct pushes to these branches are not permitted. Follow the steps below to navigate this process!

### Table of Contents

- [Mission Objectives](#mission-objectives)
- [Setting Up Git](#setting-up-git)
- [Understanding Protected Branches](#understanding-protected-branches)
- [Branch Naming Conventions](#branch-naming-conventions)
- [Creating and Updating a Branch](#creating-and-updating-a-branch)
- [Editing the README.md](#editing-the-readmemd)
- [Committing and Pushing Changes](#committing-and-pushing-changes)
- [Preparing to Open a Pull Request](#preparing-to-open-a-pull-request)
- [Opening a Pull Request](#opening-a-pull-request)
- [Assigning Reviewers](#assigning-reviewers)
- [Developers of the Project](#developers-of-the-project)

### Mission Objectives

Your tasks are:

1. Add your name to the "Developers" section in `README.md` of the `sandbox-trips-r-rus` project.
2. Follow specific branch naming conventions for features, defects, or patches.

### Setting Up Git

If you haven't already, set up Git on your computer. Use [this guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for installation and setup instructions.

### Understanding Protected Branches

In our project, `dev`, `stage`, and `main` are protected branches. This means direct pushes to these branches are not allowed. All changes must be made in separate branches (feature, defect, or patch branches) and then merged into these protected branches via pull requests.

### Branch Naming Conventions

Your branch should follow one of these formats:

- For new features: `feature-your_initials-featurename` (e.g., `feature-jd-nav-bar`).
- For defects: `defect-your_initials-description-of-issue` (e.g., `defect-jd-nav-bar-date_not_converting_as_expected`).
- For patches: `patch-your_initials-description-of-patch` (e.g., `patch-jd-date-formatting`).

### Creating and Updating a Branch

1. Clone the repository: `git clone [Repository URL]`.
2. Switch to the `dev` branch to pull the latest changes: `git checkout dev`.
3. Update your local `dev` branch: `git pull origin dev`.
4. Create a new branch using the above conventions: `git checkout -b your-branch-name`.

### Editing the README.md

1. Open `README.md` from the project root.
2. Add your name under "Developers".
3. Save the changes.

### Committing and Pushing Changes

1. Stage your changes: `git add README.md`.
2. Commit them: `git commit -m "Add [Your Name] to Developers list"`.
3. Push to GitHub: `git push origin your-branch-name`.

### Preparing to Open a Pull Request

Before opening a pull request:

1. Switch to the `dev` branch: `git checkout dev`.
2. Pull the latest changes: `git pull origin dev`.
3. Switch back to your branch: `git checkout your-branch-name`.
4. Merge `dev` into your branch to make sure it's up-to-date: `git merge dev`.

### Opening a Pull Request

1. Navigate to the repository on GitHub.
2. Click 'Pull requests' > 'New pull request'.
3. Select your branch and describe your changes.
4. Click 'Create pull request'.

### Assigning Reviewers

1. In the pull request, select 'Reviewers' on the right.
2. Choose at least one person for review.

### Developers of the Project

- JJ Menya
- User 3
- Todd Harper
- Sam Richter
- Lidiya Kuznetsova //commit test 2

Your adherence to this workflow is crucial for the orderly development of our project. If you encounter any obstacles, reach out for support. Good luck!

---

This message will not self-destruct. Happy coding!
