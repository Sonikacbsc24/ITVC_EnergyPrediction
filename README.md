# ITVC_EnergyPrediction

## Git & GitHub Workflow Documentation

This project follows a structured Git branching and version control strategy to ensure smooth collaboration, clear contribution tracking, and efficient code management across all five pipeline modules.

## Branching Strategy

Five dedicated feature branches were created, one per module of the ML pipeline. Each team member worked exclusively on their own branch to avoid conflicts, and the main branch was kept stable at all times only receiving code through reviewed Pull Requests.

feature-process: data cleaning and preprocessing

feature-encoding: label encoding, one-hot encoding, feature scaling

feature-visualization: EDA charts and visual analysis

feature-models: Linear Regression models and evaluation

feature-streamlit: interactive Streamlit dashboard (energy_dashboard.py)

## Individual Contributions

Each team member committed their notebook or script directly to their assigned branch. All 19 commits in the repository are traceable per file and per contributor, with descriptive commit messages such as "Added EnergyPredictionModels.ipynb" and "Added energy_dashboard.py".
Merging Process
Once a member completed their module, they pushed their branch to GitHub and opened a Pull Request (PRs #1–#5). The team reviewed each diff before approving the merge into main. This ensured that only reviewed, working code entered the stable branch.
Version Control History
The repository maintains a clean 19-commit history covering the full development lifecycle — from the initial clone and branch creation through to the final Streamlit dashboard merge (PR #5). Git operations used include clone, branch, checkout, add, commit, push, and merge via GitHub's web UI.

## Use of GitHub

GitHub was actively used for code hosting, branch and PR management, and contribution tracking. The public repository at https://github.com/Sonikacbsc24/ITVC_EnergyPrediction provides full transparency into the project's evolution, with all four notebooks and the dashboard file visible on the main branch.

