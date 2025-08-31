
## 🔑 Key Concepts  

- **Repository (Repo):** A project storage location (local or remote).  
- **Commit:** A snapshot of your project at a point in time.  
- **Branch:** A parallel version of the repository to isolate features or fixes.  
- **Merge:** Combining changes from one branch into another.  
- **Clone:** Copying a remote repository to your local system.  
- **Pull:** Fetching and merging updates from a remote repository.  
- **Push:** Sending your local commits to a remote repository.  

---

## 🛠 Common Git Commands  

```bash
# Configure Git (run once per machine)
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Create a new repository
git init

# Clone an existing repository
git clone <repository_url>

# Check repository status
git status

# Stage and commit changes
git add .
git commit -m "Your commit message"

# Push to remote
git push origin main

# Pull latest changes
git pull origin main

# Create and switch to a branch
git checkout -b feature-branch

# Merge a branch
git merge feature-branch
