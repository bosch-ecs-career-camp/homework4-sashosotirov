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
