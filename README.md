<img width="620" height="620" alt="Team Taco (1)" src="https://github.com/user-attachments/assets/4303bfe3-c4dd-4573-9fcf-fb04a9a7d33f" />

# 🖥️ Git & GitHub Playground: GitHub Desktop Edition

Welcome to the team! We use **GitHub Desktop** to manage our code. It allows us to save our work and share it with the team using a simple visual interface instead of complex commands.

**This is a safe practice space.** You cannot break anything here, so feel free to experiment!

## 🏁 Step 0: Prerequisites

1. **Download GitHub Desktop:** [Get it here](https://desktop.github.com/).
2. **Sign In:** Open the app and sign in with your GitHub account.
3. **Code Editor:** You still need a tool to write code. We recommend [VS Code](https://code.visualstudio.com/).

---

## 🟢 Level 1: Getting the Code (Cloning)

"Cloning" just means downloading this project to your computer.

1. **On this GitHub Website:** Look for the green **Code** button at the top right of this file list.
2. Click it and select **Open with GitHub Desktop**.
3. **In the App:** A pop-up will appear asking where to save the folder.
* Choose a location (like your `Documents` folder).
* Click **Clone**.


4. **Verify:** In GitHub Desktop, look at the top-left toolbar. It should now say **Current Repository: git-playground-desktop**.

---

## 🟡 Level 2: The "Save Game" (Commit)

In Git, saving a file in your editor isn't enough. You have to take a "snapshot" of your changes for the team to see. This is called a **Commit**.

**The Workflow:**

1. **Open in Editor:** In GitHub Desktop, click the button that says **Open in Visual Studio Code** (or "Open in external editor").
2. **Create a File:** Create a new text file named `yourname.txt` (e.g., `fahim.txt`). Write "Hello Team" inside and save it (Ctrl+S).
3. **Check GitHub Desktop:** Switch back to the GitHub Desktop app.
* Look at the left sidebar. Do you see your file with a green `+` icon? That means the app sees your new file!


4. **Commit (Save Snapshot):**
* In the bottom-left corner, you will see two boxes.
* **Summary (Required):** Type "Created my personal file".
* **Description (Optional):** You can add details here.
* Click the blue **Commit to main** button.



> **Note:** Your file has disappeared from the left sidebar! This is good—it means your changes are safely "committed" to the history.

---

## 🟠 Level 3: Syncing with the Team (Push & Pull)

Right now, the commit is only on *your* computer. You need to upload it to the cloud.

1. **Push (Upload):** Look at the top toolbar. You should see a button that says **Push origin** (with a `1` next to it). Click it.
* *Result:* Your changes are now on the website!


2. **Fetch (Check for Updates):** Before you start working every day, click the **Fetch origin** button at the top.
* If the button changes to **Pull origin**, it means a teammate made changes. Click it to download their work to your computer.



---

## 🔵 Level 4: Safe Mode (Branching)

**Rule #1:** deeply avoid working directly on the `main` branch for real features. `main` is our "production" code. We work in "branches" (parallel versions) to keep things safe.

**Your Mission:**

1. **Create Branch:**
* Click the **Current Branch** tab at the top of the app.
* Click **New Branch**.
* Name it: `feature/update-team-list`.
* Click **Create Branch**.


2. **Make Changes:**
* Open the `team.md` file in your code editor.
* Add your name to the list and save.


3. **Commit:** Go back to GitHub Desktop. You will see your change. Type a summary (e.g. "Added myself to team list") and click **Commit**.
4. **Publish:** Click the blue **Publish branch** button at the top. This sends your new branch to GitHub.

---

## 🟣 Level 5: Merging Worlds (Pull Requests)

Now you have a branch, but you want to combine it with the `main` code.

1. In GitHub Desktop, after you publish your branch, a blue button will appear labeled **Create Pull Request**.
2. Click it. This will open your web browser.
3. **On the Website:**
* You will see a comparison of your changes.
* Click **Create Pull Request**.
* (In a real project, this is where we review your code).


4. **Merge:** If authorized, click **Merge pull request** → **Confirm merge**.
5. **Cleanup:** Go back to GitHub Desktop, switch your branch back to `main`, and click **Fetch origin** to see your merged changes come back into the main folder!

---

### 📚 Dictionary

| Term | Meaning |
| --- | --- |
| **Repository (Repo)** | The project folder containing all files and history. |
| **Commit** | A saved snapshot of your changes. |
| **Push** | Uploading your commits to GitHub. |
| **Fetch/Pull** | Downloading changes from GitHub. |
| **Branch** | A safe, separate copy of the code to work on features. |
| **Publish Branch** | Uploading a new branch to the cloud for the first time. |

---

