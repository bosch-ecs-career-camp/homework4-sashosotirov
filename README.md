[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9480382&assignment_repo_type=AssignmentRepo)
# github-actions-homework-4

## 1. Create an Action which reads a Readme file from remote repository and updates the current one based on the remote content.

## 2. Example:

```yaml

  - uses: myCustomAction
    with:
      remote-repo: bosch-ecs-career-camp/${my_previous_homework_repo}@main
      remote-file: README.md
      current-file: README.md

```
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9456048&assignment_repo_type=AssignmentRepo)
# Javascript-hello-world action Template

Homework from Lection Github Actions 2/3.

# Task

Add your custom parameter similar to `who-to-greet` and print it to the console with the help of the template action. Follow the steps which you remembered yesterday.
# Requirements

1. Nodejs
2. Npm

# How to Install and Build

1. npm install
2. npm run build

# Contribution

1. Create a branch with the name dev-${YOUR_GIT_NAME}
2. Build locally and verify the action
3. Commit your changes
4. PR will be opened automatically
5. Wait for @ZdravkoChiflishki Review.

add new tets task
