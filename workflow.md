# Workflow

When developing for hatch keep this simple workflow.

1. Select tasks assigned to the current milestone _also make sure the task isn't assigned to someone else_
    1. If no tasks exist choose a task that has no milestone
        1. If no tasks exist work on enhancing the system by refactoring and writing tests (unit for API or e2e for Angular)
2. Assign yourself to the issue
3. Work on the issue in new branch `git checkout master && git pull && git checkout -b fix-123-require-email-address`
4. Commit your work `git commit -m "fix(athlete): require email address" -m "Closes #123"`
    1. Note it is **required** that your commit complys with [AngularJS Git Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y)
    1. Optionally you can `git commit` and do the line break in a text editor. Please see [here](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) and [here](http://ablogaboutcode.com/2011/03/23/proper-git-commit-messages-and-an-elegant-git-history/) for detail on **proper** git messages.
5. Push your work `git push origin fix-123-require-email-address :`
6. Create pull request and assign to `@jrschumacher`
    1. **no need** to comment on issue about pull request Github automatically adds it with the `Close #123`
