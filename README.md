 ## How to get started into Git 

#### 1. Create and initialize a local repository
```bash
mkdir Intro_to_Git
cd Intro_to_Git
git init
```

#### 2. Create a README.md file (or any other files)
You can use any editor, or:
```bash
echo "## How to get started into Git" > README.md
```

Write a good description using Markdown.

#### 3. Add files and make the first commit
```bash
git add .
git commit -m "Initial commit: Add README.md with project setup instructions"
```

Always use **descriptive commit messages** (explain what and why).

#### 4. Create a new empty repository on GitHub
- Go to GitHub URL
- Enter the repository name (`Intro_to_Git`)
- Choose Public or Private
- **Do NOT** check "Add a README file" (we already have one)
- Click "Create repository"

#### 5. Link your local repo to GitHub and push
GitHub will show you the exact commands. They look like this (replace with your username and repo name)

```bash
git remote add origin <<GitHub link>>
git branch -M main
git push -u origin main
```

Enter your GitHub credentials if prompted (or better, set up SSH keys).

