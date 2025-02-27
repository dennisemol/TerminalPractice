- What challenges did you face using the terminal?

At first, I encountered issues with Git. Even though my account was supposed to be synchronized, it wasn't working properly. 

Additionally, some commands like nano and touch were not working. After researching online, I found that these commands don't work natively on Windows. Even though I was using VS Code terminal, I wasn't able to use these commands directly. However, I found alternative commands that worked on Windows.

Also, I encountered issues when pushing to GitHub because my branch was named "master" instead of "main".


- How did you solve them?

I had to manually set my name and email again using the following commands:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

I used commands like copy nul for creating files and notepad for editing the files, and I managed to complete the exercises successfully.

To solve the branch issue, I renamed my branch using: git branch -M main


- What is the purpose of using Git branches?

Git branches allow developers to work on different features or fixes without affecting the main project. 
For example, a developer can create a new branch for a feature, work on it, and merge it into the main branch once it is complete.