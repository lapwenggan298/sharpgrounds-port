# Contributing to SharpGrounds

First off, thank you for taking the time to contribute! Every comment, suggestion, documentation improvement, and code change is meaningful to us!

Since this is not a very serious or big project, we are not very sure on how we we can have a standard for testing the program itself. We only have experience testing programs [for behaviors, issues, bugs] by actually running them. Any suggestions or ideas for it are welcome!

## Setup for our Programmer friends

This is strictly for our main friends or those close to us.

Please make sure that your commits and/or pull requests are focused on one change at a time.

1. Do a git clone of our project/repository or you can fork it. Please note that it is safer for us if you fork the repository
    - If you do decide to git clone instead, please do this:

    ```bash
    git clone https://github.com/lapwenggan298/sharpgrounds-port
    ```

    - else, once you have made a fork of the repo:

    ```bash
    git clone https://github.com/your-username/link-to-your-fork
    ```

2. Install the required dependencies and prerequisties of the project, should there be any.
    - We are using .NET10 SDK and NET10 compatible packages as of the writing and starting of this project and markdowns.
    - But we are planning to download and use .NET11, once we have finished this project just to keep it up to date.

3. Create a new branch where you will write or commit the changes you wish to make.
    - Regardless of if you make a fork, or a git clone.

    ```bash
    git branch <feature or branch name>
    git switch <feature or branch name>
    ```

4. Test those changes that you have made. Is it satisfactory to you? Please describe how you verified your changes.

5. Commit those changes. Make sure that they are as descriptive as they can be.
    - We recommend doing git commit, and then writing your message on your preferred text editor. But git commit -m "commit message" is fine as well, just that we find it easier to format text and there is a clear separation of the title/head from the main body.
        - Additionally, we want the commit details/body to be as detailed as possible so we can fully understand what it is you added.

    ```bash
    git add <filename.file_extension>
    git commit
    ```

6. Push your changes to your own fork of the project.
    - If you made a direct git clone, make sure that your branch is named differently.

    ```bash
    git push origin <feature or branch name>
    ```

7. Create a Pull Request (PR) of your branch.
    - Provide a description of your changes and submit the pull request to this repository.

### Coding Conventions

Please follow the naming, formatting, and patterns we have used in this project. Refrain from using a different format, pattern, and naming style. Thank you.

## For those who still wish to contribute

There are still ways you can contribute!

1. Reporting and/or reproducing issues, bugs
    - This goes kind of hand in hand with creating forks and making pull requests to our repository.
    - But still, you can report issues without coding! Just expect the progress to resolving the issue to be a bit slower than you may like.
    - First, check if your issue/s have been reported already. If it hasn't been reported yet, feel free to report it with details as to how you got the issue, and steps to replicate them so that we can easily verify them.
        - Also include the expected behavior, and what you got.

2. Comments and Suggestions
    - Please make it constructive, we don't promote hateful language, if it helps you make the comment a bit "friendlier", please consider using our native language of Filipino, or words that may not be misconstrued or interpreted with sarcasm or hate so that we may be able to pick it up and understand it easier.
    - Suggestions/comments may include:
        1. Beautification side of the program (javascript, css).
        2. Better implementation of certain parts of the project.
        3. Ideas and literal suggestions regarding the framework and the associated parts of it.
        4. Possible JavaScript frameworks (frontend and/or backend) that we can explore.
        5. Clearer/Better wording, syntax

3. Help fellow programmers
    - Help us learn the programming language, syntax, good practices, Data Structures and Algorithms (DSAs), frameworks, etc.

## Attribution

This guide is and was based on **[contributing.md](https://contributing.md/)**.
