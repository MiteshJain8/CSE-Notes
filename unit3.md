## Question 1: Explain the Process of Transferring Ownership of a Repository on GitHub. What Happens to the Repository's URL During This Process?

### **Steps to Transfer Repository Ownership:**
1. Navigate to the repository’s **Settings** on GitHub.
2. Scroll down to the **Danger Zone** and click **Transfer ownership**.
3. Enter the new owner's GitHub username or organization name.
4. Confirm the repository transfer by typing the repository name.
5. Click **I understand, transfer this repository**.

### **Effects on the Repository URL:**
- The old URL will redirect to the new repository location.
- Users should update their remotes with the new URL.

---

## Question 2: How to Block or Report a User on GitHub, and What Happens Once a User is Blocked?

### **Steps to Block a User:**
1. Go to the user’s GitHub profile.
2. Click **Block or Report User** from the menu.
3. Select **Block User** to prevent them from interacting with your repositories.

### **Effects of Blocking a User:**
- They cannot comment on your repositories.
- They are removed from your followers list.
- They cannot fork your repositories.

---

## Question 3: Four Key Sections in Open Source Software Exploration

1. **Repositories:** Publicly available projects that anyone can explore or contribute to.
2. **Issues:** Track bugs, enhancements, and discussions related to the software.
3. **Pull Requests:** Proposals for merging new code into the project.
4. **Discussions:** A place where the community collaborates beyond code changes.

---

## Question 4: Steps to Add a License to an Existing GitHub Repository

1. **Navigate to the Repository on GitHub.**
2. **Click "Add File" → "Create New File".**
3. **Name the File `LICENSE`.**
4. **Choose a License Template (MIT, Apache, GPL, etc.).**
5. **Commit the New License File to the Repository.**

---

## Question 5: How to Review the Conversation Tab and Examine Change Files

### **Reviewing Conversations:**
1. Open a pull request or issue.
2. Navigate to the **Conversation** tab to review discussions.

### **Examining Changed Files:**
1. Click on the **Files Changed** tab in a pull request.
2. Review line-by-line changes with added and removed lines highlighted.

---

## Question 6: Define Pull Request and Explain How to Open One

### **What is a Pull Request?**
A pull request (PR) is a request to merge changes from one branch into another in a Git repository.

### **Steps to Open a Pull Request:**
1. **Push Code to GitHub:**
   ```bash
   git push origin feature-branch
   ```
2. **Go to GitHub Repository → Pull Requests → New Pull Request.**
3. **Select the Base (e.g., `main`) and Compare (e.g., `feature-branch`).**
4. **Add a Title, Description, and Click "Create Pull Request".**

---

## Question 7: Converting a Private GitHub Repository to a Public One

### **Steps to Convert a Repository:**
1. Go to **Settings** of the repository.
2. Scroll to the **Danger Zone**.
3. Click **Change repository visibility** → Select **Public**.
4. Confirm the change.

### **Precautions:**
- Ensure no sensitive data exists in the repository.
- Review commit history for secrets or credentials.

---

## Question 8: Reasons for Contributing to Open Source and Guidelines to Follow

### **Reasons to Contribute:**
- Gain experience and enhance coding skills.
- Collaborate with developers globally.
- Improve software quality.
- Build a professional reputation.

### **Guidelines:**
- Follow project contribution guidelines.
- Write clear commit messages.
- Respect community rules and maintain professionalism.

---

## Question 9: Steps to Archive a Repository on GitHub and Consequences

### **Steps to Archive a Repository:**
1. Navigate to **Settings** in the repository.
2. Scroll to the **Danger Zone**.
3. Click **Archive this repository**.
4. Confirm the action.

### **Consequences of Archiving:**
- The repository becomes read-only.
- No new issues, pull requests, or modifications can be made.

---

## Question 10: Detailed Process of Triaging Issues in GitHub

### **Steps to Triaging Issues:**
1. **Review New Issues:** Check for duplicates and relevance.
2. **Apply Labels:** Categorize issues as bug, enhancement, documentation, etc.
3. **Assign Issues:** Assign issues to contributors or teams.
4. **Engage in Discussions:** Ask clarifying questions and provide guidance.
5. **Close or Mark Stale Issues:** If unresolved for a long time, mark them inactive or close them.

### **Importance of Triaging:**
- Keeps project backlog organized.
- Helps prioritize urgent bugs and feature requests.
- Ensures a smoother contribution workflow.

---

## Question 11: Purpose of Temporary Interaction Limits in a Public Repository

### **Purpose of Temporary Interaction Limits:**
- Prevent spam and abuse in repositories.
- Reduce distractions from non-constructive contributors.
- Maintain a productive discussion environment.

### **When They Are Useful:**
- During high-visibility project launches.
- When a repository receives spam issues or PRs.
- To control heated discussions in controversial topics.

---

## Question 12: Importance of Labeling Issues in GitHub and Default Labels

### **Why Label Issues?**
- Helps categorize issues and pull requests.
- Improves visibility for maintainers and contributors.
- Simplifies project management.

### **Default Labels in GitHub:**
- **bug**: Something isn’t working.
- **documentation**: Improvements or additions to documentation.
- **duplicate**: Similar to an existing issue.
- **enhancement**: New feature request.
- **good first issue**: Beginner-friendly tasks.
- **help wanted**: Contributions are needed.

---
