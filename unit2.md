## Question 1: Outline and Explain the Steps Involved in Creating a Branch for Contributing to a Project.

### **Steps to Create a Branch for Contribution**
1. **Ensure Local Repository is Updated:**
   ```bash
   git checkout main
   git pull origin main
   ```
2. **Create a New Branch:**
   ```bash
   git checkout -b feature-branch
   ```
3. **Make and Stage Changes:**
   ```bash
   git add .
   ```
4. **Commit the Changes:**
   ```bash
   git commit -m "Added new feature"
   ```
5. **Push the Branch to Remote Repository:**
   ```bash
   git push origin feature-branch
   ```
6. **Create a Pull Request on GitHub for Review.**

---

## Question 2: Describe the Process of Fetching Changes and Contributing Updates to the Upstream Repository.

### **Steps to Fetch and Contribute Updates:**
1. **Set Up Upstream Repository (If Not Done Earlier):**
   ```bash
   git remote add upstream https://github.com/original-repo.git
   ```
2. **Fetch Latest Changes from Upstream:**
   ```bash
   git fetch upstream
   ```
3. **Merge Updates into Local Branch:**
   ```bash
   git checkout main
   git merge upstream/main
   ```
4. **Push Merged Changes to Remote Repository:**
   ```bash
   git push origin main
   ```

---

## Question 3: Difference Between Cloning and Forking a Git Repository.

| **Feature**  | **Cloning** | **Forking** |
|-------------|------------|------------|
| **Definition** | Creates a local copy of an existing repository. | Creates a copy of a repository under a different user account on GitHub. |
| **Usage** | Used for local development and contribution. | Used to modify a project independently before contributing back. |
| **Ownership** | No ownership, linked to the original repository. | Owned by the forking user on GitHub. |
| **Command** | `git clone <repo-url>` | Click “Fork” on GitHub UI. |

---

## Question 4: Steps and Permissions Needed to Clone a Repository from GitHub.

### **Steps to Clone a Repository:**
1. **Copy Repository URL from GitHub.**
2. **Run the Clone Command:**
   ```bash
   git clone https://github.com/username/repository.git
   ```
3. **Navigate into the Cloned Directory:**
   ```bash
   cd repository
   ```

### **Permissions Needed:**
- Public repositories can be cloned by anyone.
- Private repositories require authentication (SSH key or GitHub credentials).

---

## Question 5: Explain the Steps in Building Your Personal Website.

1. **Choose a Website Platform (HTML, GitHub Pages, WordPress, etc.).**
2. **Set Up a Repository (If Using GitHub Pages):**
   ```bash
   git init
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```
3. **Create and Modify Website Files (HTML/CSS/JS).**
4. **Deploy the Website Using Hosting Services.**

---

## Question 6: Process of Triaging Issues in a GitHub Repository.

### **Steps Involved in Triaging Issues:**
1. **Review New Issues and Prioritize Them.**
2. **Apply Labels (e.g., bug, enhancement, documentation).**
3. **Assign Issues to Contributors.**
4. **Engage with the Reporter (Ask for Clarifications if Needed).**
5. **Close Stale or Resolved Issues.**

---

## Question 7: How to Set Up a Personal Website Repository Using GitHub Pages.

### **Steps to Set Up GitHub Pages:**
1. **Create a New Repository on GitHub.**
2. **Enable GitHub Pages in Repository Settings.**
3. **Push HTML Files to the Repository.**
4. **Verify Website Deployment at `username.github.io/repository`.**

---

## Question 8: Process of Staging Changes and Creating a Commit in Git.

### **Steps to Stage and Commit Changes:**
1. **Make Modifications to Files.**
2. **Stage the Changes:**
   ```bash
   git add .
   ```
3. **Create a Commit with a Descriptive Message:**
   ```bash
   git commit -m "Updated feature X for better performance"
   ```
4. **Push the Changes to Remote Repository:**
   ```bash
   git push origin branch-name
   ```
