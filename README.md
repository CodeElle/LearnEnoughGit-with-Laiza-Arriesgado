# LearnEnoughGit-with-Laiza-Arriesgado
## by Laiza Arriesgado - 2025
## Overview
This Project demonstrates foundational skills in using Git and GitHub for version control and collaboration.
It is part of an assessment designed to evaluate the following learning outcomes:
1. Install and configure Git for local development
2. Understand and explain the use cases and benefits of GitHub

## Installation & Set-Up
1. Download and Install Git
2. Ensure that you have a sufficiently recent version of Git using
    ```bash
    $ git --version # should be atleast 2.28.0
    ```
3. Clone or download this repository
    ```bash
    git clone <repository_url>

## The Assignment - The Making
1. Exercise 1.3.1 
    - Created empty files called `foo` and `bar` using `touch` command
    - Added `foo` to the staging area using `git add foo` and confirmed with `git status`
    - Added a comment using `git commit -m`
    - Added `bar`to staging area and comfirmed with `git status`
    - Added a comment by running `git commit` without the `-m` option and using the Vim knowledge "Add bar", saved, and quit
    - Used `git log`, confirming that the commits made in the previous exercises worked correctly

2. Exercise 1.4.1
    - Created a file called `baz`
    - Running `git commit -am "Add baz" returns

        ```bash
        $ git commit -am "Add baz"
        [main 35e1f1a] Add baz
        1 file changed, 21 insertions(+), 1 deletion(-)
    - Added `baz` to the staging area using `git add -A` then commits a message "Add bazz"
    - Amending the typo from `bazz` to `baz` using `git commit --amend -m "Add baz"`

3. Exercise 1.5.1
    - Learning the difference between `git log` vs `git log -p`
        `git log` command shows ONLY the COMMIT MESSAGES
        Adding `-p` option shows the FULL diffs represented by each commit.
    - Verified by running `git log -p`
    - Adding `index.html` using `touch` command and an html tag with a paragraph consisting "Call me Ishmael." to successfully finish exercise 1.5.1

4. Exercise 1.6.1
    - Added a title "A Whale of a greeting" to `index.html`
    - Commit the new title with a commit message
    - Pasting the contents of index.html into an HTML validator (check the Reference Section #2 for website and link)
    - `index.html` was verified using the HTML Validator that recommended to put `lang="en"` into the html.

5. 2.1 Prompts to create GitHub Account
    - This assignment was created using GitHub to enhance the writer's skills and ensure a strong familiarity with using GitHub Website.

6. Exercise 2.2.1
    -
    > On the GitHub page for your repo, click on
    > “Commits” to see a list of your commits. 
    > Confirm that they match the results of running
    > git log on your local system. 
    -
    > At GitHub, click on the commit for adding HTML structure (Listing 1.10)
    > Verify that the diff for the commit agrees with the one shown in Listing 1.9
    -
    > In honor of shipping your first Git repo, drink a celebratory beverage of your choice (Figure 2.7)

7. Exercise 2.3.1
    - Adding a line at the end of the README with a link to the Official Git documentation

## References
1. Hartl, M. (n.d.). "Learn Enough Git to Be Dangerous." Retrieved from https://www.robertson.brigthspace.com
2. Markup validation service. The W3C Markup Validation Service. (n.d.). https://validator.w3.org#validate_by_input+with_options