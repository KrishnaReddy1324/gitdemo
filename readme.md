# 🌐 Web Page Project

![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)
![Git](https://img.shields.io/badge/Git-Version_Control-orange?logo=git)
![HTML](https://img.shields.io/badge/HTML5-Web-red?logo=html5)
![CSS](https://img.shields.io/badge/CSS3-Styling-blue?logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Programming-yellow?logo=javascript)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-green)

---

## 📌 About the Project

This project is a simple web page created to understand and demonstrate the basic workflow of **Git, GitHub, and GitHub Pages**.

The project demonstrates how a developer can create a website locally, track changes using Git, upload the project to GitHub, and deploy the website online using GitHub Pages.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the fundamentals of Git.
* Understand the purpose of GitHub.
* Create and manage a Git repository.
* Track changes in project files.
* Create commits.
* Connect a local repository with a remote GitHub repository.
* Push code from a local computer to GitHub.
* Understand branches and repositories.
* Deploy a website using GitHub Pages.
* Understand a basic real-world development workflow.

---

## 🛠️ Technologies Used

| Technology   | Purpose                               |
| ------------ | ------------------------------------- |
| HTML5        | Creates the structure of the web page |
| CSS3         | Provides styling and layout           |
| JavaScript   | Adds functionality and interactivity  |
| Git          | Version control                       |
| GitHub       | Remote code repository                |
| GitHub Pages | Website deployment                    |

---

## 📂 Project Structure

```text
Web-Page-Project/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### File Description

| File         | Description              |
| ------------ | ------------------------ |
| `index.html` | Main HTML page           |
| `style.css`  | CSS styling              |
| `script.js`  | JavaScript functionality |
| `README.md`  | Project documentation    |

---

## 🔄 Development Workflow

The project follows this basic development workflow:

```text
        Create Project
              ↓
       Create Git Repo
              ↓
       Create / Modify Files
              ↓
          git status
              ↓
           git add
              ↓
         git commit
              ↓
      Connect GitHub Repo
              ↓
          git push
              ↓
           GitHub
              ↓
       GitHub Pages
              ↓
       Live Web Page
```

---

## 💻 Git Commands

| Command                   | Purpose                                |
| ------------------------- | -------------------------------------- |
| `git init`                | Creates a new Git repository           |
| `git status`              | Shows the current repository status    |
| `git add .`               | Stages all modified files              |
| `git add filename`        | Stages a specific file                 |
| `git commit -m "message"` | Creates a commit                       |
| `git log`                 | Displays commit history                |
| `git diff`                | Shows changes between versions         |
| `git branch`              | Displays available branches            |
| `git switch main`         | Switches to the main branch            |
| `git remote -v`           | Displays remote repository information |
| `git push`                | Uploads commits to GitHub              |
| `git pull`                | Downloads and merges changes           |
| `git clone`               | Copies a remote repository locally     |

---

## 🧠 Git vs GitHub

| Git                       | GitHub                                         |
| ------------------------- | ---------------------------------------------- |
| Version control system    | Cloud-based Git hosting platform               |
| Runs on your computer     | Runs primarily online                          |
| Tracks changes            | Stores and shares repositories                 |
| Works without GitHub      | Usually used with Git for remote collaboration |
| Created by Linus Torvalds | Owned by Microsoft                             |

### Simple Example

```text
Git
↓
Tracks changes on your computer

GitHub
↓
Stores and shares your Git repository online
```

---

## 📦 Repository Concepts

| Concept           | Meaning                            |
| ----------------- | ---------------------------------- |
| Repository        | Project folder tracked by Git      |
| Local Repository  | Repository stored on your computer |
| Remote Repository | Repository stored on GitHub        |
| Commit            | Saved version of your project      |
| Branch            | Separate line of development       |
| Main              | Default primary branch             |
| Remote            | Connection to a remote repository  |
| Clone             | Copying a remote repository        |
| Push              | Sending local commits to GitHub    |
| Pull              | Getting changes from GitHub        |

---

## 🔗 Local Repository and Remote Repository

```text
        LOCAL COMPUTER
        ┌──────────────┐
        │ Git Repo     │
        │              │
        │ index.html   │
        │ style.css    │
        │ script.js    │
        └──────┬───────┘
               │
             git push
               │
               ↓
        ┌──────────────┐
        │    GitHub    │
        │              │
        │ Remote Repo  │
        └──────────────┘
```

---

## 🚀 Getting Started

### 1. Create a Project Folder

Create a folder for the web project.

### 2. Create the Web Files

Create:

* `index.html`
* `style.css`
* `script.js`

### 3. Initialize Git

```bash
git init
```

### 4. Check the Repository

```bash
git status
```

### 5. Add Files

```bash
git add .
```

### 6. Create a Commit

```bash
git commit -m "Initial commit"
```

### 7. Connect GitHub Repository

```bash
git remote add origin <repository-url>
```

### 8. Push the Project

```bash
git push -u origin main
```

---

## 🌐 GitHub Pages Deployment

GitHub Pages can be used to publish the website online.

### Deployment Process

```text
GitHub Repository
       ↓
Settings
       ↓
Pages
       ↓
Select Source
       ↓
Select Branch
       ↓
Select Root Folder
       ↓
Save
       ↓
GitHub Builds Website
       ↓
Live Website
```

### Example URL

```text
https://username.github.io/repository-name/
```

---

## 🔐 SSH Authentication

GitHub can use SSH authentication to securely connect your local Git installation with GitHub.

Example SSH remote:

```bash
git remote add origin git@github.com:username/repository-name.git
```

Check the configured remote:

```bash
git remote -v
```

Example:

```text
origin  git@github.com:username/repository-name.git (fetch)
origin  git@github.com:username/repository-name.git (push)
```

---

## 🔁 Basic Git Lifecycle

```text
Working Directory
       ↓
     git add
       ↓
Staging Area
       ↓
   git commit
       ↓
Local Repository
       ↓
    git push
       ↓
Remote Repository
       ↓
     GitHub
```

---

## 📝 Example Commit History

A project may contain multiple commits as development progresses.

```text
Initial commit
      ↓
Added HTML structure
      ↓
Added CSS styling
      ↓
Added JavaScript
      ↓
Updated navigation
      ↓
Fixed responsive design
      ↓
Deployed using GitHub Pages
```

View commit history:

```bash
git log --oneline
```

---

## 🌿 Branching

Branches allow developers to work on different features without directly modifying the main branch.

Example:

```text
                    main
                     │
                     ├───────────────┐
                     │               │
                  feature          testing
                     │               │
                     ↓               ↓
               New Feature      Testing Changes
                     │               │
                     └───────┬───────┘
                             ↓
                           main
```

Create a branch:

```bash
git branch feature
```

Switch to a branch:

```bash
git switch feature
```

Create and switch simultaneously:

```bash
git switch -c feature
```

---

## 📚 Learning Outcomes

After completing this project, students should be able to:

1. Explain what Git is.
2. Explain what GitHub is.
3. Differentiate between Git and GitHub.
4. Create a Git repository.
5. Track files using Git.
6. Stage files.
7. Create commits.
8. View commit history.
9. Create and switch branches.
10. Connect a local repository to GitHub.
11. Push code to GitHub.
12. Clone a GitHub repository.
13. Understand remote repositories.
14. Deploy a basic website using GitHub Pages.
15. Explain the basic Git development lifecycle.

---

## 🧪 Practice Tasks

### Task 1 — Basic Git

Create a new repository and perform:

```text
git init
git status
git add .
git commit
```

### Task 2 — GitHub

Create a GitHub repository and connect it with your local repository.

### Task 3 — Push

Push the project to GitHub.

### Task 4 — Modify

Modify `index.html`, create another commit, and push the changes.

### Task 5 — Branch

Create a new branch and add a new feature.

### Task 6 — GitHub Pages

Deploy the website using GitHub Pages.

---

## ❓ Frequently Asked Questions

### What is Git?

Git is a distributed version control system used to track changes in source code.

### What is GitHub?

GitHub is a cloud platform that hosts Git repositories and provides collaboration features.

### What is a repository?

A repository is a project directory tracked by Git.

### What is a commit?

A commit is a saved snapshot of changes in a Git repository.

### What is push?

`git push` sends local commits to a remote repository.

### What is pull?

`git pull` downloads changes from a remote repository and integrates them into the local repository.

### What is clone?

`git clone` creates a local copy of a remote repository.

### What is GitHub Pages?

GitHub Pages is a hosting service that can publish static websites from GitHub repositories.

---

## 🔮 Future Improvements

Possible improvements include:

* Responsive design
* Navigation menu
* JavaScript interactions
* Contact form
* Animations
* Additional pages
* Mobile optimization
* Custom domain
* CI/CD deployment
* Automated testing

---

## 👨‍💻 Author

**Krish**

This project is created for learning and demonstrating Git, GitHub, web development, version control, and basic web deployment concepts.

---

## ⭐ Conclusion

This project demonstrates a simplified real-world software development workflow:

```text
Develop
   ↓
Track Changes
   ↓
Commit
   ↓
Push
   ↓
GitHub
   ↓
Deploy
   ↓
Live Website
```

The same basic workflow can be extended to larger software projects involving multiple developers, branches, pull requests, code reviews, testing, and CI/CD pipelines.
