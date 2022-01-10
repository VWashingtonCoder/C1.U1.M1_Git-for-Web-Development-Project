# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [X] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac 
2. [X] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [X] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [X] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [X] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name` 
6. [X] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [X] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [X] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [X] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
    - Git is an open software content tracker used to store content (like writings, pictures, etc) that will continue to change as more content is added. Git has a remote version stored on a server and a local version stored on dev's computer which allows devs the ability to modify local versions of the code, save the revisions, and upload to the remote server.  

    - Github is one of the remote servers that can store git repositories. It is also one of the largest and most used git servers.

2. Why do we create a branch?
    - We create branches in order to independently work on projects that may contain new features or bug fixes while isolating our work from other team members.

3. What is the purpose of a pull request?
    - To update the local repository from the remote. Ex: We performed a pull request to download this questionaire project from Github to our computers.

4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main.
    - "git Checkout" command. 

5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do?
    - git fetch: Downloads the remote content but won't update your local repo's working state, leaving your work intact.
    - git merge: Used to put forked repositories back together again.
    - git pull: Used to update the local version of a repository from a remote server as well. However, it will download the remote content for the active local branch and immediately execute git merge to create a merge commit for new remote content. This can cause conflicts if you have pending changes in progress.

6. What is a merge conflict? How do you resolve a merge conflict?
    - A merge conflict is what results when competing changes are made to the same line of a file, or when one person edits a file and another deletes the same file.
    - To resolve a merge conflict by competing line changes, you must choose which changes to incorporate from the different branches in a new commit.
    - To resolve a merge conflict by removed file merge conflicts, you must choose whether or not to keep the deleted file in a new commit.
    -Overall, to solve a merge conflict, choose which version of changes you want and write in a new commit.
