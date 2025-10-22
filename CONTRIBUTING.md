# Contribution Guidelines 

First off, thank you for considering contributing! We are thrilled to have you here. This project is for students, by students, and every contribution makes a big difference.

Following these guidelines ensures that your contribution is clear, effective, and helps us maintain a well-organized project.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## The Contribution Workflow

Our project uses an **"Issue-First"** workflow. This means that before you write any code or notes, you must **claim an issue** first. This process prevents multiple people from working on the same topic and makes it clear what tasks are available.

The entire process looks like this:

1.  **Find an Issue** you want to work on.
2.  **Claim the Issue** by commenting on it.
3.  **Fork, Clone, and Branch** the repository.
4.  **Make Your Changes** (add your notes file).
5.  **Submit a Pull Request** that links back to the original issue.

---

## Step-by-Step Guide to Contributing

### Step 1: Find and Claim an Issue

1.  Go to the **[Issues Tab](https://github.com/murugnn/Hacktoberfest_Disaster_Prep/issues)** of this repository.
2.  Browse the list of available topics. Each topic from the MCN 301 syllabus is an issue.
3.  Look for an issue that is **not assigned** to anyone yet.
4.  Open the issue you want to work on and **leave a comment** saying: `"I would like to work on this."`
5.  A project maintainer (one of the student coordinators) will then **assign the issue to you**. Please wait for the assignment before you start working to avoid conflicts.

### Step 2: Fork & Clone the Repository

Once an issue is assigned to you, you can start!

1.  **Fork** this repository by clicking the "Fork" button at the top right.

  <img width="1278" height="80" alt="image" src="https://github.com/user-attachments/assets/8acb5d8e-8bf4-488d-8c14-36ff343bfb27" />

  <img width="1235" height="629" alt="image" src="https://github.com/user-attachments/assets/061fe31a-7518-4685-9f38-94c36c9330f4" />


2.  **Clone** your forked repository to your local machine. Replace `[YOUR_GITHUB_USERNAME]` with your actual username.

    ```bash
    git clone https://github.com/[YOUR_GITHUB_USERNAME]/Githober-RepoRescue.git
    cd Githober-RepoRescue
    ```

### Step 3: Create a New Branch

It's best practice to create a new branch for each contribution. Name your branch descriptively, including the issue number.

```bash
# Example: If you are working on issue #15
git checkout -b feat/issue-15-disaster-cycle-notes
```

### Step 4: Add Your Contribution

This is where you do the actual work.

1.  **Create Your Notes File:** Navigate to the `notes/` directory and find the correct module folder (e.g., `Module-3/`). Create your new Markdown file there.
2.  **Add and Verify Content:** Add your AI-generated notes to the file. **Crucially, review, edit, and verify the information for accuracy.**
3.  **Update the README:** Open the `README.md` file and add a new row to the "Our Awesome Contributors" table with your name and GitHub profile link.

### Step 5: Commit and Push Your Changes

Save your work and push it to your forked repository.

```bash
# Add your changed files to the staging area
git add .

# Commit your changes with a clear message
# Example: git commit -m "feat: Add notes for Disaster Management Cycle (#15)"
git commit -m "feat: Add notes for [Your Topic] (#[issue-number])"

# Push your new branch to your fork on GitHub
git push origin your-branch-name
```

### Step 6: Create a Pull Request (PR)

This is the final and most important step!

1.  Go to your forked repository on GitHub.
2.  You will see a banner prompting you to "Compare & pull request". Click it.
3.  **Title:** Make sure your PR title is clear and concise (e.g., `Add Notes for Disaster Management Cycle`).
4.  **Description:** This is critical. In the description box, you **must link the issue you worked on**. Type the following magic words:
    ```
    Closes #[issue-number]
    ```
    *Example:* If you worked on issue #15, you would write `Closes #15`. This tells GitHub to automatically close the issue once your PR is merged.
5.  Click the **"Create pull request"** button.

### And... You're Done! 🎉

A project maintainer will now review your pull request. They might ask for some changes, but once it's approved, your contribution will be merged into the main project.

Thank you for helping us build this amazing resource!
