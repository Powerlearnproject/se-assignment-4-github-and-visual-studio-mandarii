## GITHUB AND VISUAL STUDIO
## Brenda Ondimu
## Assignment 4

## Question one:Introduction to GitHub:

**Question**
What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

**Answer:**
GitHub is a command line interface that allows developers to to create, store, manage and share their code. 
# Primary functions
Storing and sharing code in repositories.
Code review and collaboration.
Hosting small websites and organizing projects.
Tracking and managing changes to code.

# Features
* Repositories
* Branches
* Commits
* Pull Requests
* Git (the version control software GitHub is built on)

## QUESTION TWO: Repositories on GitHub:

**Question**
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

**Answer**
A  github repository is a place where you store code,files and the files revision history.
To create a new repository login to your github account or create one if you don't have one. 
Click on the plus sign on the top right of your account and  new repository, You can give it a description or not, initialize it with a README.md file and choose whether to make it public or private.
Then click create new repository.

# Essential elements.
* Code Files: Add project code files (e.g., Python).
* README: A README.md file that can be edited.
* License: Include a license file.
* Issues: Use issues to track tasks, bugs, and enhancements.
* Pull Requests: Propose changes, collaborate with others.
* Branches: Create branches.
* Collaborators: Invite team members to collaborate.
* Tags: Use tags to mark specific versions or releases.

## QUESTION THREE: Version control with git

**Question**
Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

**Answer**
Git is a version control that tracks file changes.It also makes it easy to record and compare different file versions. 
Github is a web-based platform that enhances collaboration that allows developers to store, collaborate on their code and track the changes on said code.


## QUESTION FOUR:Branching and Merging in GitHub:

**Question**
What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

**Answer**
Branches allow you to develop features, fix bugs, or experiment with new ideas in a contained area of your repository.They also create a seperate context where you can work on different features without affecting the main code.
# Creating a branch
Creating a branch from an existing branch.
After creating a new branch make small commits to the branch.
Open a pull request to merge changes from your branch (the head branch) into another branch (usually the main branch).

## QUESTION FIVE:Pull Requests and Code Reviews:

**Question**
What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

**Answer**
A pull request is a way to propose changes in a project in a repository.
Pull requests allow team members to review code changes, discuss the proposed changes. It allows for continuous integration and documentation for future reference.
# Steps to create and review a pull request
* If you do not have access to make changes to the repository you have to fork it.
* Then clone it to your local machine (git clone <repo url>)
* Create a branch ( e.g git checkout -b my-branch)
* Make changes in the branch.
* Commit the changes( git add ., git commit -m"")
* Push the changes(git push)
* On the original repository on github, click on "pull requests" tab and click "new pull request"
* Fill out the pull request form, providing a title and description that explain the changes and their purpose. Select the base branch (e.g., main or master) and the compare branch (your branch).
* Go to the "Pull requests" tab in the repository and click on the PR you want to review.
* Go through the "Files changed" tab to see the code changes. You can add comments to specific lines by clicking the "+" icon next to the line numbers.
* Provide feedback by adding comments, suggesting changes, or asking questions.
* Once you’ve reviewed the code, you can either approve the changes or request changes. Use the "Review changes" button to select "Approve", "Comment", or "Request changes".
* If the PR is approved and CI checks pass, you can merge the PR using the "Merge pull request" button. Choose the type of merge (e.g., "Create a merge commit", "Squash and merge", or "Rebase and merge") based on your project's guidelines.
* If the PR is not going to be merged, it can be closed with the "Close pull request" button.

## QUESTION SIX:GitHub Actions:

**Question**
Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

**Answer**
Github actions refer to a continuous integration and a continuous delivery platform that allows you to automate your build, test and deployment pipeline.
# Example
* Create a workflow : In the repository add a .github/workflows directory and add a YAML file to define your workflow.
* In the YAML specify the steps for your workflow.

## QUESTION SEVEN:Introduction to Visual Studio:

**Question**
What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

**Answer**
Visual studio is a powerful IDE that provides a robust set of tools for writing, editing, debugging, and running code.
# Key Features
* Intelligent code editing
* Advanced debugging 
* Designer tools
* Built in Git integration
* Test tools

Visual Studio is suited for large, enterprise-level projects requiring robust tools, while Visual Studio Code is ideal for developers seeking a fast, customizable, and lightweight editor.

## QUESTION EIGHT:Integrating GitHub with Visual Studio:

**Question**
Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

**Answer**
# Steps to Integrate repository
* Install Github and Visual Studio Code
* Create a repository in github account
* Open command prompt and run as administrator
* Navigate to a directory and clone the repository
* After cloning the repository navigate to the cloned repository
* Open the repository on VS Code by using the command code .
* The repository will open on VS Code and you can begin working

Integrating a GitHub repository simplifies tasks such as committing code, creating branches, and managing pull requests without leaving Visual Studio.

## QUESTION NINE:Debugging in Visual Studio:

**Question**
Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

**Answer**
* Breakpoints- such as standard breakpoint that pause execution at a specific line of code.
* Watch windows- monitor the values of variables and expressions
* Output windows - displays output from the build process, debug output, and other messages from the IDE.
* Step commands - execute the next statement or the current function
* Edit and continue- allows you to make changes to your code during a debugging session and continue running the program with the changes applied without restarting the session.

 Dy using debugging tools, developers get deep insights into their code, understand the causes of the issues, and use effective fixes to improve the quality and performance of their applications.


## QUESTION TEN:Collaborative Development using GitHub and Visual Studio:

**Question**
Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

**Answer**
By linking repositories in Github to Visual Studio allowing developers to clone, commit and push changes effortlessly
Pull requests and code reviews- developers can discuss changes, review code, and collaborate effectively.
Automated Workflows using GitHub Actions can automate CI/CD pipelines within your Visual Studio projects.
Visual Studio Code (VS Code) is an example of a project benefiting from GitHub and Visual Studio integration.


## REFERENCES
* Class notes
* https://www.w3schools.com/whatis/whatis_github.asp
* https://dev.to/seracoder/decoding-git-and-github-an-introductory-handbook-on-version-control-and-collaborative-coding-4le6
* https://docs.github.com/articles/about-branches
* https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions
* https://stackshare.io/stackups/visual-studio-vs-visual-studio-code#:~:text=Visual%20Studio%20is%20a%20robust%20Integrated%20Development%20Environment,coding%20experience%2C%20particularly%20for%20web%20and%20cloud%20development.
* https://visualstudio.microsoft.com/vs/github/