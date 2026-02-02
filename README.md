# 01-github-project-x-github-actions
## 🛠️ Workshop: Building the Industrial Foundation


#### **Project Management Setup** (The Brain)
- [ ] Kanban Board: Initialize a GitHub Project using the Kanban methodology to visualize your workflow with "To Do," "In Progress," and "Done" columns. 
- [ ] Backlog Documentation: Create at least 3 GitHub Issues to document your initial tasks, such as "API Contract Definition" or "Database Schema Design". 
- [ ] Smart Categorization: For each issue, assign Labels (priority/type), Assignees (responsibility), and link them to a Milestone (deadline).
sss
#### **Guardrails & Governance** (The Rules)

- [ ] Branch Protection: Configure your repository settings to disallow direct pushes to the main branch, forcing the use of Pull Requests for all changes. 

- [ ] Clean Workspace: Create a .gitignore file to ensure that environment variables, secrets, and local dependencies (like node_modules) are never tracked. 

### **CI Pipeline Implementation** (The Muscle)

- [ ] Workflow Anatomy: Create a .github/workflows/ci.yml file to define your first automation. 

- [ ] The Trigger: Set the workflow to trigger on every pull_request targeting the main branch. 

- [ ] The Virtual Sandbox: Configure a Job to run on a fresh ubuntu-latest runner to ensure environment isolation. 

### Automation Steps: Implement a sequence of steps:

  - [ ] Checkout: Use actions/checkout to pull your code into the runner.

  - [ ] Environment Setup: Install the necessary runtime (Node.js, Python, etc.).
  - [ ] Quality Check: Run a command (e.g., npm test or a simple echo) to simulate a "Quality Gate." 