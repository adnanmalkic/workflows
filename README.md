
## Learning Objectives

<details>
<summary>Priorities: 🥚, 🐣, 🐥, 🐔 (click to learn more)</summary>
<br>

There is a lot to learn in this repository. If you can't master all the material
at once, that's expected! Anything you don't master now will always be waiting
for you to review when you need it. These 4 emoji's will help you prioritize
your study time and to measure your progress:

- 🥚: Understanding this material is required, it covers the base skills you'll
  need for this module and the next. You do not need to finish all of them but
  should feel comfortable that you could with enough time.
- 🐣: You have started all of these exercises and feel you could complete them
  all if you just had more time. It may not be easy for you but with effort you
  can make it through.
- 🐥: You have studied the examples and started some exercises if you had time.
  You should have a big-picture understanding of these concepts/skills, but may
  not be confident completing the exercises.
- 🐔: These concepts or skills are not necessary but are related to this module.
  If you are finished with 🥚, 🐣 and 🐥 you can use the 🐔 exercises to push
  yourself without getting distracted from the module's main objectives.

---

</details>

### 🥚 [0. Local Development Without Git](./0-local-development-without-git)

Practice the foundational workflows of software development by learning to write
Markdown locally on your own computer using Visual Studio Code (VSCode), the
Command Line Interface (CLI), and NPM scripts to automate your code's quality
(formatting, linting and spell checking).

- [ ] 🥚 **Folder Structures**: You can explain how files and folders are stored
      in your computer and can find, open or create files in your computer
      without using the Command Line Interface.
- 🥚 **Command Line Interface (CLI)**: In a Unix shell you can ...
  - [ ] Open a new terminal window
  - [ ] Navigate up and down directories using `cd`
  - [ ] List the contents of a directory using `ls`
  - [ ] View the contents of a file using `cat`
  - [ ] Create new files using `touch`
  - [ ] Create new folders using `mkdir`
- [ ] 🥚 **Markdown**: You can write a document in Markdown with no syntax
      mistakes that renders into a well-formatted document.
- 🥚 **VSCode**: You can complete these workflows in VScode, and can use
  keyboard shortcuts to complete them all:
  - [ ] Opening a repository in a new window
  - [ ] Opening the VSCode terminal
  - [ ] Adding a new file
  - [ ] Adding a new folder
  - [ ] Deleting a file
  - [ ] Deleting a folder
  - [ ] Previewing a Markdown File
  - [ ] Formatting a Markdown document
- [ ] 🥚 **READMEs**: You can write a README file that describes the project you
      are working on, why it's helpful, and how someone can use it.
- 🥚 **NPM**: You can use NPM commands to verify your code's quality, this
  includes ...
  - [ ] Using `npm install` to install a project's dependencies
  - [ ] Reading a `package.json` file to find which scripts are available for
        the project
  - [ ] Use `npm run <script>` to execute an npm script
- 🥚 **Formatting Code**: You can use Prettier to make sure all the code in your
  project is well-formatted:
  - [ ] You can use the Prettier VSCode extension to format a document while you
        are writing it
  - [ ] You can use `npm run format` to format all of the documents in your
        project
  - [ ] You can use `npm run format:check` to make sure all files are
        well-formatted
- 🥚 **Linting Folder and File Names**: You can ...
  - [ ] Use `npm run lint:ls` to check all folder and file names in your project
  - [ ] You can fix all linting mistakes reported by `npm run lint:ls`
- 🥚 **Linting Code**: You can ...
  - [ ] Use `npm run lint:md` to check all Markdown files in your folder for
        linting mistakes
  - [ ] You can fix all linting mistakes reported by `npm run lint:md`
- 🥚 **Spell Check**: You can ...
  - [ ] Use the Code Spell Checker VSCode extension to correct spelling mistakes
        in your Markdown documents while you are writing
  - [ ] Use `npm run spell-check` to check the spelling in all the files of your
        project
  - [ ] Update `.cspell.json` to add words that should be allowed in your
        project
- 🥚 **File and Folder Naming Conventions**: You can ...
  - [ ] Identify and follow the naming conventions for the project you are
        working on.
  - [ ] Use `npm run lint:ls` to check that all files and folders follow the
        project's naming conventions.
  - [ ] You can correct any file and folder names to make them match the project
        conventions.
- [ ] 🐣 **File Extensions**: You can identify all of the languages covered at
      HYF and give the correct file extension. You don't need to know the
      languages, just recognize them.
- [ ] 🐣 **Touch Typing**: You can write a Markdown file without looking at your
      keyboard to find any letters, numbers or special characters. (slowly is
      ok!)

### 🥚 [1. Local Development With Git](./1-local-development-with-git)

Practice using Git to save and organize your development process. You will learn
how you can use Git to go back to previous versions of your project, and to work
on different changes in parallel.

- 🥚 **Git**: Using the CLI you can ...
  - [ ] Initialize a new git repository with `git init`
  - [ ] Stage changes using `git add <path>`
  - [ ] Check what is staged with `git status`
  - [ ] Commit changes using `git commit -m <message>`
  - [ ] Display your repository's git history using `git log`
  - [ ] Create a new branch using `git branch <branch-name>`
  - [ ] Check out a branch using `git checkout <branch-name>`
  - [ ] Create a new branch and check it out using
        `git checkout -b <branch-name>`
  - [ ] Merge changes from one branch to another using `git merge <branch-name>`
  - [ ] Update current branch (your branch) from _main_ branch:
    - [ ] Check out to _main_ branch using `git checkout main`
    - [ ] Pull changes from remote repository using `git pull`
    - [ ] Check out to your branch using `git checkout <branch-name>`
    - [ ] Merge changes from _main_ branch to your branch using `git merge main`
  - [ ] Merge changes from _main_ branch to current branch in one step using
        `git pull origin main`
  - [ ] Return to a previous version of your project with `git log` and
        `git checkout <commit-hash>`
  - [ ] Stash and retrieve uncommitted changes with `git stash` and `git pop`
  - [ ] Display list of existing remote URLs using `git remote -v`
  - [ ] Add a new remote repository URL using
        `git remote add <shortname> <remote-url>`
  - [ ] Update a remote repository URL using
        `git remote set-url <exsit-shortname> <new-remote-url>`
  - [ ] Rename a remote repository URL using
        `git remote rename <old-shortname> <new-shortname>`
  - [ ] Remove a remote repository URL using `git remote rm <exsit-shortname>`
- 🥚 **`.gitignore`**: You can use a `.gitignore` file to describe which files
  you don't want included in your git history.
- 🥚 **VSCode**: You can ...
  - [ ] Use the _Git Graph_ extension to to visualize your repo's commit history
  - [ ] Use the _Git Lens_ extension to investigate your repository's commit
        history
  - [ ] Explain how the file tree in VSCode can show you which files have
        uncommitted changes
- [ ] 🥚 **Atomic Commits**: You can save your development progress using small
      commits with clear and helpful message.
- [ ] 🐣 **Feature Branches**: You can organize your development process using
      branches. You can create a new branch for each part of your project and
      merge those changes to `main` when they are finished.

### 🥚 [2. Local/Remote Development](./2-local-remote-development)

Learn how you can connect your local Git repositories with a GitHub repository
to add more structure to your development process and to share your projects.

- 🥚 **Licenses**: You can ...
  - [ ] Explain why it's important to include a license for your code on GitHub
  - [ ] Choose a license for your projects that matches how you want others to
        use your code
- [ ] 🥚 **GitHub SSH Key**: You can connect your computer to your GitHub
      account using an SSH key, clone using the SSH link, and push/pull using
      your SSH connection.
- 🥚 **GitHub Repositories**: You can ...
  - [ ] Create new repository on GitHub
  - [ ] Write a description for your repository
  - [ ] Turn on GitHub Pages
  - [ ] Configure your repository to block pushing to `main`
  - [ ] Configure your repository to block merging to `main` until Continuous
        Integration (CI) checks have passed
- 🥚 **Git Remote/Local Connection**: You can ...
  - [ ] Clone a remote repository to your computer using
        `git clone <remote-url>`
  - [ ] initialize a new repository locally and connect it to an empty remote
        repository
  - [ ] `git push` command is used to upload local repository content to a
        remote repository
  - [ ] `git fetch` a primary command used to download contents from a remote
        repository
  - [ ] `git pull` command downloads the changes directly and then applies those
        changes to the current working files
  - [ ] `push` and `pull` changes between remote & local branches
  - [ ] You can distinguish between `git fetch` and `git pull`
- [ ] 🥚 **Pull Requests**: You can create a pull request between two branches
      in your repository and merge changes without causing any conflicts.
- [ ] 🥚 **PR templates**: You can use a PR template to add a checklist to all
      of your PRs so you are sure the code is great before merging to `main`.
- [ ] 🥚 **Continuous Integration**: You can use GitHub Actions to check your
      code's quality before merging a pull request to the `main` branch.
- [ ] 🐣 **Local/Remote Branching Workflow**: You can use a branching workflow
      that keeps mistakes away from the `main` branch and prevents conflicts
      from happening in GitHub. For each contribution to the project you can ...
  1. Check out a new local branch and write your code
  2. Check out `main` on your local machine
  3. Pull changes from remote `main` to local `main`
  4. Merge changes locally from `main` to your new branch
     - Fix any conflicts on your new branch before pushing!
  5. Format and lint your code
  6. Push your new local branch to your remote repository
  7. Open a Pull Request from the new branch to `main`
     - Go through the PR's checklist to make sure everything is correct
     - Make sure all CI checks pass!
  8. Merge your new remote branch to `main`
     - You can delete the branch after it's merged if you want to

### 🐣 [3. Remote Collaboration](./3-remote-collaboration)

Learn how to collaborate with a group on a single project hosted in a GitHub
repository. Practice using GitHub's project management features to organize your
group's tasks and to double-check your project's code quality.

- [ ] 🥚 **Contributor Guidelines**: Your group can define contributor
      guidelines that describes how everyone can add their work to the project.
- [ ] 🥚 **Code of Conduct**: Your group can write a code of conduct for your
      project that describes how everyone should communicate and what behavior
      is considered unproductive.
- [ ] 🥚 **Repository Contributors**: You can add group members as collaborators
      in a repository.
- [ ] 🥚 **Issue Templates**: Your group can use issue templates to make sure
      all issues are complete and relevant to the project. in your repository
      and merge changes without causing any conflicts.
- [ ] 🥚 **Code Review**: You can use the PR Template and CI checks to review
      another group member's code before merging it to `main`.
- 🐣 **GitHub Project Management**: You can ...
  - [ ] Use issues to define tasks in a group project. Each issue should have a
        helpful title, complete description, and helpful labels.
  - [ ] Use a Project Board to organize a project's issues
  - [ ] Claim issues and track your progress with the project board
  - [ ] Link a PR to your claimed issue
  - [ ] Assign someone to review your PR
  - [ ] Use GitHub code review features to discuss your code with your reviewer
- [ ] 🐣 **Fixing Merge Conflicts**: You can fix merge conflicts by selecting
      which change to keep, or deciding how to combine them. If a conflict
      occurs in a GitHub PR you can pull both branches and fix the conflict
      locally.

### 🐥 [4. Open Source Development](./4-open-source-development)

Explore the wider world of Open Source software by learning how communities of
independent developers write and maintain the code we all rely on.

- [ ] 🥚 **Finding Issues**: You can read through an open source project's
      issues and determine if there is one you can help with.
- [ ] 🐣 **Commenting in Issues**: You can productively join the conversation in
      an open source projects' issues.
- [ ] 🐥 **Opening Issues**: You can open a helpful issue in an open source
      repository, following their contributor guidelines and code of conduct.
- [ ] 🐔 **Contributing**: You can create a fork of an open source project and
      open a PR that contributes something helpful and follows the Contributor
      Guidelines and Code of Conduct.






