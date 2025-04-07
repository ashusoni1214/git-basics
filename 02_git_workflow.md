# 🔁 Git Workflow

A **Git workflow** is a set of steps that developers follow when working with Git.  
It helps you manage your code efficiently, collaborate with others, and keep your project organized.

---

## 🧭 Common Git Workflow (Step-by-Step)

---

## 1️⃣ Clone the Repository

Cloning means copying an existing GitHub repository to your local machine so you can work on it.

```bash
git clone https://github.com/yourusername/project-name.git
cd project-name
```
✅ Now you have a local copy of the project.

## 2️⃣ Create a New Branch

Always create a branch before making changes. This keeps the main branch clean and safe.

```bash
git checkout -b feature-branch
```
✅ This creates and switches to a new branch called feature-branch.

## 3️⃣ Make and Stage Changes
Edit or create files as needed. Then stage those changes to prepare them for committing.
```bash
git add .

```
✅ Stages all files in the current folder.

To stage specific files:
```bash
git add index.html style.css
```
## 4️⃣ Commit the Changes
A commit saves your staged changes to your local Git history. Always use a clear message.
```bash 
git commit -m "Add homepage layout and styles"
```
✅ Keep messages short but meaningful!

## 5️⃣ Pull Latest Changes from Remote
Before pushing, always pull the latest version of the main branch to avoid conflicts.
```bash
git pull origin main
```
✅ This syncs your local branch with the remote main.

## 6️⃣ Push Your Branch to GitHub
Send your local branch and commits to the remote repository on GitHub
```bash
git push origin feature-branch
```
✅ Others can now see your changes on GitHub.

## 7️⃣ Create a Pull Request (PR)
On GitHub, open your repo and create a Pull Request from your feature-branch to main.

💬 A PR lets your team review the code and merge it into the main project safely.


## Visual Workflow Summary. 
```bash
clone ➝ branch ➝ code ➝ add ➝ commit ➝ pull ➝ push ➝ PR
```

🧠 Pro Tips
✅ Pull before you push — always!

💬 Write clear commit messages

🧪 Test your changes before creating a PR

🧹 Keep your branches short-lived to reduce merge conflicts

🙅‍♂️ Never commit directly to main in a shared project. 



