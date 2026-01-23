Hi everyone,

Please follow these steps exactly when working on our group project on GitHub.
This keeps the project clean and avoids conflicts.

---

### STEP 1: Connect your fork to the main repo (DO THIS ONCE ONLY)

```bash
git remote add upstream https://github.com/FangZxuan/Group-Project-IY470-WebProgramming.git
```

---

### STEP 2: Sync before starting any work (DO THIS EVERY TIME) 
IF It does not work, try step 2 and step 3.

```bash
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

### STEP 3: Create a new branch (REQUIRED)

❌ Never work on `main`

```bash
git checkout -b name
```

Example:
```bash
git checkout -b homepage
```

---

### STEP 4: Do your assigned work

* Edit files
* Add files
* Test your changes

---

### STEP 5: Commit your changes

```bash
git add .
git commit -m "Short description of what you did"
```

Example:

```bash
git commit -m "Add homepage layout"
```

---

### STEP 6: Push your branch to your fork

```bash
git push origin branch-name
```

If you don't know your branch name or what branch you are at - git branch (eg. *main, *blabla *mean the current branch)
Example:

```bash
git push origin homepage(the branch name you are working on)
```
---

### STEP 7: Create a Pull Request (GitHub website)

1. Go to **your fork**
2. Click **Compare & pull request**
3. Base repo → main project repo
4. Base branch → `main`
5. Head branch → your feature branch
6. Click **Create Pull Request**

Then wait for approval.

---

### IMPORTANT RULES

* ❌ Do NOT push to `main`
* ✔ One task = one branch
* ✔ Always sync before starting
* ✔ Clear commit messages

---
LETS GO GET 100% GUYS!!!
