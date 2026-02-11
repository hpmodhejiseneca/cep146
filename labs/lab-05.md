
# Lab 05

# GitHub Introduction

## Introduction
Your instructor will show how to create a GitHub repository and make a commit. And show how to create a branch and add a new file.

## Exercise 1: Creating Your First Repository and Making Commits
**Type:** Solo Activity

### Objectives:
- Create a GitHub repository
- Understand repository structure
- Make your first commit with proper commit messages

### Step-by-Step Instructions:

1. **Create a New Repository (5 minutes)**
   - Log into your GitHub account
   - Click the "+" icon in the top right corner
   - Select "New repository"
   - Repository name: `my-course-portfolio`
   - Description: "Portfolio of my work and projects for [Course Name]"
   - Set to Public
   - ✅ Check "Add a README file"
   - Choose "MIT License"
   - Click "Create repository"

2. **Edit Your README File (5 minutes)**
   - Click on the `README.md` file in your repository
   - Click the pencil icon to edit
   - Replace the content with:
   ```markdown
   # My Course Portfolio
   
   Welcome to my academic portfolio for [Course Name]!
   
   ## About Me
   - Name: [Your Name]
   - Major: [Your Major]
   - Year: [Your Academic Year]
   - Favorite Programming Language: [Your Choice]
   
   ## Course Goals
   - [ ] Learn version control with Git and GitHub
   - [ ] Complete all lab assignments
   - [ ] Build a professional portfolio
   - [ ] Collaborate on group projects
   
   ## Projects
   *This section will be updated as I complete assignments*
   ```

3. **Make Your First Commit (5 minutes)**
   - Scroll down to "Commit changes"
   - Commit message: "Add personal information and course goals to README"
   - Extended description: "Initialized portfolio with personal details, learning objectives, and project tracker"
   - Click "Commit changes"

### Checkpoint:
- Verify your repository appears on your GitHub profile
- Check that your README displays properly formatted
- Note the commit appears in your repository's commit history

### Deliverable:
**Students must show the instructor:**
1. Your repository URL (e.g., `https://github.com/yourusername/my-course-portfolio`)
2. Point to your personalized README content with your name and course goals
3. Show the commit history with your descriptive commit message

**OR upload a screenshot showing:**
- Your repository homepage with the formatted README
- The commit message in the repository's commit history

---

## Exercise 2: Working with Branches and File Management (15 minutes)
**Type:** Solo Activity

### Objectives:
- Create and switch between branches
- Add new files to repository
- Understand branching workflow

### Step-by-Step Instructions:

1. **Create a New Branch (5 minutes)**
   - In your `my-course-portfolio` repository
   - Click the branch dropdown (currently shows "main")
   - Type: `add-study-resources`
   - Click "Create branch: add-study-resources from main"
   - Verify you're now on the new branch

2. **Add a Study Resources File (10 minutes)**
   - Click "Add file" → "Create new file"
   - Name the file: `study-resources.md`
   - Add the following content:
   ```markdown
   # Study Resources
   
   ## Useful Websites
   - [GitHub Docs](https://docs.github.com/) - Official GitHub documentation
   - [Markdown Guide](https://www.markdownguide.org/) - Learn Markdown syntax
   - [Git Handbook](https://guides.github.com/introduction/git-handbook/) - Git basics
   
   ## Tools I Use
   - Text Editor: [Your preferred editor]
   - Browser: [Your preferred browser]
   - Note-taking: [Your preferred method]
   
   ## Study Schedule
   | Day | Topic | Time |
   |-----|-------|------|
   | Monday | GitHub Basics | 2:00 PM - 3:00 PM |
   | Wednesday | Branching & Merging | 2:00 PM - 3:00 PM |
   | Friday | Collaboration | 2:00 PM - 3:00 PM |
   
   ## Quick Reference
   - Create branch: Branch dropdown → Type name → Create
   - Switch branch: Use branch dropdown menu
   - Commit changes: Add message → Commit
   ```

3. **Commit the New File (3 minutes)**
   - Commit message: "Add study resources and weekly schedule"
   - Extended description: "Created comprehensive study guide with useful links, tools, and scheduled study times"
   - Click "Commit new file"

4. **Explore Branch Differences (2 minutes)**
   - Switch back to `main` branch using the dropdown
   - Notice that `study-resources.md` doesn't exist on main
   - Switch back to `add-study-resources` branch
   - Confirm the file is there

### Checkpoint:
- You have two branches: `main` and `add-study-resources`
- The study resources file exists only on the feature branch
- You can successfully switch between branches

### Deliverable:
**Students must demonstrate to the instructor:**
1. Switch between `main` and `add-study-resources` branches to show the study-resources.md file appears/disappears
2. Show the commit for the study resources file with your descriptive commit message
3. Navigate to the study-resources.md file and show the formatted table

**OR submit:**
- Screenshot of the branch dropdown showing both branches
- Screenshot of the study-resources.md file with the formatted content
- Screenshot of the commit history showing your branch-specific commit

---

## Exercise 3: Issue Tracking and Project Management (15 minutes)
**Type:** Solo Activity

### Objectives:
- Create and manage issues
- Use labels and assignments
- Understand project tracking workflow

### Step-by-Step Instructions:

1. **Create Your First Issue (5 minutes)**
   - Go to the "Issues" tab in your repository
   - Click "New issue"
   - Title: `Add contact information to README`
   - Description:
   ```
   ## Description
   The README file is missing contact information that would be helpful for potential collaborators or employers.
   
   ## Tasks to Complete
   - [ ] Add email address (use school email)
   - [ ] Add LinkedIn profile link
   - [ ] Add GitHub profile link
   - [ ] Consider adding personal website if available
   
   ## Expected Outcome
   A "Contact Me" section in the README with professional contact information.
   
   ## Priority
   Medium - This would improve the professional appearance of the portfolio.
   ```
   - Click "Submit new issue"

2. **Create a Bug Report Issue (5 minutes)**
   - Click "New issue" again
   - Title: `Study schedule table formatting needs improvement`
   - Description:
   ```
   ## Bug Description
   The study schedule table in study-resources.md could be more readable and include more detailed information.
   
   ## Current Behavior
   Basic table with minimal information about study topics and times.
   
   ## Expected Behavior
   Well-formatted table with:
   - Specific topics for each session
   - Duration of study sessions
   - Location or method (online/library/etc.)
   - Progress tracking
   
   ## Steps to Reproduce
   1. Navigate to study-resources.md
   2. Scroll to "Study Schedule" section
   3. Observe the current table format
   
   ## Suggested Solution
   Expand table columns and add more descriptive content.
   ```
   - Click "Submit new issue"

3. **Organize Issues with Labels (3 minutes)**
   - Click on the first issue you created
   - In the right sidebar, click "Labels"
   - Add the "enhancement" label
   - Go to the second issue
   - Add the "bug" label
   - If available, also add "good first issue" to both

4. **Assign Issues to Yourself (2 minutes)**
   - On each issue, click "Assignees" in the right sidebar
   - Assign both issues to yourself
   - Add a comment to the first issue: "I'll work on this after completing the current branch"

### Checkpoint:
- You have 2 open issues in your repository
- Issues are properly labeled and assigned
- You understand how to track work using GitHub Issues

### Deliverable:
**Students must show the instructor:**
1. Navigate to the Issues tab and show both created issues
2. Click on each issue to demonstrate proper labels ("enhancement" and "bug")
3. Show that both issues are assigned to yourself
4. Display the issue URLs (e.g., `https://github.com/yourusername/my-course-portfolio/issues/1`)

**OR submit:**
- Screenshot of the Issues tab showing both open issues with labels
- Screenshot of one issue's detail page showing the assignment and description
- Copy and paste the URLs of both issues

---

## Exercise 4: Collaboration and Commenting (15 minutes)
**Type:** Partner Activity (Teams of 2)

### Objectives:
- Practice collaboration features
- Learn to give constructive feedback
- Use GitHub's commenting system effectively

### Step-by-Step Instructions:

1. **Find Your Lab Partner (2 minutes)**
   - Partner up with a classmate
   - Exchange GitHub usernames
   - Navigate to your partner's `my-course-portfolio` repository

2. **Explore Your Partner's Repository (3 minutes)**
   - Read through their README file
   - Check their study resources (if on the feature branch)
   - Look at their commit history
   - Review their open issues

3. **Provide Constructive Feedback (5 minutes)**
   - **On their README file:**
     - Click on `README.md`
     - Click on a line number next to content you want to comment on
     - Click the "+" icon that appears
     - Leave a helpful comment, such as:
       - "Great choice of course goals! You might also want to add a goal about learning markdown."
       - "Consider adding a section about your favorite coding projects."
       - "Nice formatting! The checklist format makes it easy to track progress."

   - **Create an issue for your partner:**
     - Go to their Issues tab
     - Click "New issue"
     - Title: `Suggestion: Add project showcase section`
     - Description:
     ```
     Hi [Partner's Name]!
     
     I was reviewing your portfolio and think it would be great to add a project showcase section. Here are some ideas:
     
     ## Suggested Addition
     A "Featured Projects" section that could include:
     - Brief description of each project
     - Technologies used
     - Links to live demos or repositories
     - Screenshots or GIFs if applicable
     
     ## Benefits
     - Makes your portfolio more visually appealing
     - Helps potential employers see your work quickly
     - Demonstrates your range of skills
     
     ## Example Format
     ```markdown
     ## Featured Projects
     ### Project Name
     - **Description:** Brief overview
     - **Technologies:** List of tools/languages used
     - **Link:** [View Project](link-here)
     ```
     
     Let me know what you think!
     ```
     - Add label: "enhancement"
     - Submit the issue
     ```

4. **Respond to Feedback (3 minutes)**
   - Check if your partner has left comments on your repository
   - Respond to any line comments with a thank you or follow-up question
   - If they created an issue, add a comment like:
     - "Thanks for the suggestion! I'll work on implementing this after I finish my current branch."
     - "Great idea! I hadn't thought of adding a project showcase. I'll create a new branch for this."

5. **Star Your Partner's Repository (2 minutes)**
   - Click the "Star" button on your partner's repository
   - This shows appreciation for their work and helps you bookmark interesting projects
   - Check if they've starred yours in return

### Lab Checkpoint:
- You've provided constructive feedback to a classmate
- You've created an issue on someone else's repository
- You've responded professionally to feedback
- You understand the social aspects of GitHub collaboration

### Lab Deliverable:
**Both partners must show the instructor:**
1. The issue you created on your partner's repository (provide the URL)
2. At least one line comment you made on your partner's code/README
3. Your response to feedback received from your partner
4. Show that you've starred your partner's repository

**OR submit as a team:**
- Partner A's name and GitHub username
- Partner B's name and GitHub username  
- URL of the issue Partner A created on Partner B's repository
- URL of the issue Partner B created on Partner A's repository
- Screenshot showing the line comments exchanged between partners
- Screenshot showing both repositories have been starred by the respective partners

---

## Lab Wrap-Up: Reflection and Next Steps

### What You've Accomplished:
1. ✅ Created your first GitHub repository with proper documentation
2. ✅ Learned to work with branches and manage files
3. ✅ Used GitHub's issue tracking system for project management
4. ✅ Practiced collaboration and professional communication

### Final Deliverable Summary:
**For complete lab credit, ensure you have submitted/demonstrated:**
- Exercise 1: Repository URL and formatted README with commit history
- Exercise 2: Branch switching demonstration and study resources file
- Exercise 3: Two properly labeled and assigned issues in your repository
- Exercise 4: Collaborative work evidence (issues and comments on partner's repo)

---
# Lab Rubric - GitHub Introduction

**Total Points: 2 marks**

## Requirements for Completion:
* **Exercise 1:** Create repository with personalized README and proper commit message
* **Exercise 2:** Create branch, add study-resources.md file, demonstrate branch switching
* **Exercise 3:** Create two properly labeled and assigned issues
* **Exercise 4:** Complete partner collaboration (create issue on partner's repo, provide feedback, respond professionally)

## Lab Rubric:

| Criteria | Poor - 0 mark | Fair - 1 mark | Good - 2 marks |
|---|---|---|---|
| Lab Completion | Major exercises incomplete (Exercise 1 and 2 not completed OR no repository created OR no collaboration attempted) OR deliverables not demonstrated/submitted | Completed individual exercises (1-3) but collaboration incomplete OR missing key components (branches not working, issues improperly created, or minimal partner interaction) | Successfully completed all four exercises: repository with personalized content, functional branching, proper issue management, and meaningful collaboration with partner including professional feedback |

## Detailed Expectations:

### For 2 marks (Good), demonstrate:
- **Exercise 1 - Repository Creation:**
  - Successfully created `my-course-portfolio` repository with MIT license
  - Personalized README with student's actual name, major, and course goals
  - Proper commit message: descriptive and professional
  - Repository accessible and properly formatted

- **Exercise 2 - Branching & File Management:**
  - Created `add-study-resources` branch successfully
  - Added `study-resources.md` with all required sections (websites, tools, schedule table)
  - Can demonstrate switching between branches and file visibility differences
  - Proper commit messages for branch work

- **Exercise 3 - Issue Management:**
  - Created two distinct issues with detailed descriptions
  - Applied appropriate labels ("enhancement" and "bug")
  - Self-assigned both issues
  - Issues follow proper format with clear tasks and expected outcomes

- **Exercise 4 - Collaboration:**
  - Created meaningful issue on partner's repository with constructive suggestions
  - Left at least one thoughtful line comment on partner's code
  - Responded professionally to partner's feedback
  - Starred partner's repository
  - Demonstrated professional communication skills

### For 1 mark (Fair), show:
- **Basic Repository Skills:** Repository created and README updated, but content may be generic or commits lack detail
- **Incomplete Branching:** Branch created but file management or switching demonstration incomplete
- **Minimal Issue Tracking:** Issues created but poorly formatted, missing labels, or inadequate descriptions
- **Limited Collaboration:** Attempted partner work but feedback is superficial or unprofessional

### For 0 marks (Poor):
- **No Repository:** Failed to create repository or major components missing
- **No Branching Understanding:** Cannot demonstrate branch creation or switching
- **No Issue Management:** Issues not created or completely inadequate
- **No Collaboration:** Did not engage with partner or provide any meaningful feedback

