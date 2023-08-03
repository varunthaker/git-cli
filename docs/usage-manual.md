# How to use this Repository

## Once

Clone the repository via its ssh url:

-   `git clone git@github.com:[REPLACE_WITH_WORKING_REPO_URL]`

## Steps for every day

### for students

1. To see notes of a specific session go to the week-X folder to see them
2. To get access to the `handout` and `challenges` of a session go to the sessions folder and pick the session you are interested
3. Don't forget to update the main branch or checkout a specific branch if you don't see the wished notes/handout/challenges
    - for updating the main branch do the following steps:
        - `git switch main`
        - `git pull`
    - when the files are not merged yet to the main branch you'll need to checkout the corresponding branch by
        - `git fetch`
        - `git checkout topic` (replace topic with the topic taught)
        - `git pull`

### for teachers

1. Update your local repository before working in it (`git switch main` (alternative: `git checkout main`), then `git pull`)
2. Create a new branch (example name: `topic`) and switch to it.
3. Add handout and challenges file to the sessions folder. Create for each session a subfolder.
4. Commit and push your changes to GitHub.
5. Create a Pull Request.
6. On GitHub, merge your Pull Request into main and delete your branch.
7. On your computer, checkout/switch to main, pull your merged changes and delete the feature branch you have worked in.
