## 1. Define Version Control and Explain Its Benefits in Software Development.

### **What is Version Control?**
Version control is a system that records changes to files over time, allowing developers to track modifications, revert to previous versions, and collaborate efficiently.

### **Benefits of Version Control:**
- **History Tracking:** Keeps a detailed log of all code changes.
- **Collaboration:** Multiple developers can work on a project simultaneously.
- **Branching & Merging:** Enables development of new features without disrupting the main codebase.
- **Backup & Recovery:** Protects against accidental loss or corruption of code.
- **Revert Changes:** Developers can roll back to previous versions when necessary.

---

## 2. What is the Significance of the `git init` Command? Illustrate with an Example.

The `git init` command initializes a new Git repository in the specified directory. This creates a `.git` directory, which contains all necessary metadata and tracking information for version control.

### **Example:**
```bash
mkdir my_project && cd my_project
git init
```
**Output:**
```
Initialized empty Git repository in /path/to/my_project/.git/
```
This means Git is now tracking changes in the `my_project` directory.

---

## 3. Steps to Create a Project and Track Changes Using Git

### **1. Initialize a Git Repository**
```bash
git init
```

### **2. Add Files to Staging Area**
```bash
git add .  # Adds all files in the directory
```

### **3. Commit the Changes**
```bash
git commit -m "Initial commit"
```

### **4. Check the Repository Status**
```bash
git status
```

### **5. View Commit History**
```bash
git log --oneline
```

---

## 4. Production Branch vs. Development Branch in Git

| Branch | Purpose |
|--------|---------|
| **Production (`main` or `master`)** | Stable version of the project, ready for deployment. |
| **Development (`dev`)** | Used for active development, testing new features before merging into production. |

### **Significance:**
- The **production branch** should always contain stable, tested code.
- The **development branch** allows developers to experiment without affecting the live environment.

---

## 5. Key Features of GitHub.com Homepage and Their Purposes

- **Repositories:** Store, manage, and share projects.
- **Pull Requests:** Review and merge changes from different branches.
- **Issues:** Track bugs and feature requests.
- **Actions:** Automate workflows such as testing and deployment.
- **Explore:** Discover trending open-source projects.

---

## 6. Git Branching Workflow When Two Collaborators Modify the Same File

### **Scenario:**
1. **Developer A** creates a feature branch and modifies `file.txt`.
2. **Developer B** creates another branch and edits the same `file.txt`.
3. Both push changes and attempt merging.
4. Git detects conflicts, requiring manual resolution before merging.

```
   main
    | 
    ├── feature-branch (Dev A changes `file.txt`)
    ├── bugfix-branch (Dev B changes `file.txt`)
    |
    ├── Merge Conflict Detected
    |
    ├── Conflict Resolved
    |
    └── Merged Successfully
```

---

## 7. Modifying a `README.md` File in a GitHub Repository

### **Steps to Modify and Merge Changes:**

1. **Edit the file locally or via GitHub UI.**
2. **Stage the changes:**
   ```bash
   git add README.md
   ```
3. **Commit the changes:**
   ```bash
   git commit -m "Updated README with new details"
   ```
4. **Push changes to GitHub:**
   ```bash
   git push origin branch_name
   ```
5. **Create a Pull Request and merge it to `main`.**

---

## 8. Creating a Git Repository, Making Commits, and Viewing History

### **Step 1: Initialize a New Repository**
```bash
mkdir new_repo && cd new_repo
git init
```

### **Step 2: Create and Commit a File**
```bash
echo "Hello Git" > file.txt
git add file.txt
git commit -m "First commit"
```

### **Step 3: View Commit History**
```bash
git log --oneline
```

**Output Example:**
```
3f1d2e1 First commit
```

---

## 9. Reviewing and Merging a Pull Request on GitHub

### **Steps to Review and Merge a Pull Request:**
1. **Navigate to the Pull Requests section in GitHub.**
2. **Review the changes, add comments if necessary.**
3. **Approve and merge the pull request.**
4. **Delete the feature branch after merging.**
5. **Sync local repository with `main` after merge:**
   ```bash
   git pull origin main
   ```

### **Post-Merge Branch Management:**
- If the feature is complete, delete the branch locally:
  ```bash
  git branch -d feature-branch
  ```
- Ensure the team updates their local branches to stay in sync.

