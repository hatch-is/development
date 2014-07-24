# Workflow

When developing for hatch keep this simple workflow.

1. Select tasks assigned to the current milestone _also make sure the task isn't assigned to someone else_
    1. If no tasks exist choose a task that has no milestone
        1. If no tasks exist work on enhancing the system by refactoring and writing tests (unit for API or e2e for Angular)
2. Assign yourself to the issue
3. Work on the issue in new branch `git checkout master && git pull && git checkout -b fix-123-require-email-address`
4. Commit your work `git commit -m "fix(athlete): require email address" -m "Closes #123"`
5. Push your work `git push origin fix-123-require-email-address :`
6. Create pull request and assign to `@jrschumacher`
    7. **no need** to comment on issue about pull request Github automatically adds it with the `Close #123`
