# Experiment 6: GitHub Actions CI

## Aim
To create a Continuous Integration (CI) workflow using GitHub Actions and verify it using a simple text file.

## Tools Used
- Git and GitHub
- Visual Studio Code
- GitHub Actions

## Procedure
1. Created the GitHub repository `CDD-lab`.
2. Cloned the repository to the local Mac.
3. Created `message.txt` containing `Hello from CI/CD lab`.
4. Created the workflow file `.github/workflows/ci.yml`.
5. Configured GitHub Actions to display the text file and verify its expected contents.
6. Committed and pushed the changes to GitHub.
7. Changed the text to test a workflow failure.
8. Restored the correct text and verified that the workflow passed again.

## Result
The GitHub Actions CI workflow was executed successfully. The workflow passed when the expected text was present, failed when the text was changed, and passed again after the text was corrected.