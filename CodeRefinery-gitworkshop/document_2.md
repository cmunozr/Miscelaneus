# Document 2

Written answers to the following four questions submitted as a document (pdf or word or txt). Evaluation criteria: we expect critical answers related to the content of first 3 days with both pros and cons (when relevant):

*When should you work with branches?*

Working with branches is useful to

* Plan and diferentiate several lines of development of a software  
* Create and test changes in the main code without breaking it
* Develop several features at the same time that in the future will be merged
* Collaborate and modify an existing project throug cross reference of issues and pull requests
* Help in conflict resolution of contrasting ideas of development

*What is the difference between a `git clone` and a `git fork`?*

Let's to define each one:

* `git clone` is a command used in git to have a local copy of a remote repository. It is made by using either both HTTPS and SSH protocols.
* `git fork` is a GitHub action (not a git command) to create a copy of an existing remote repository in your own account in github. This action can be set up to only copy some branches. 

The key difference is where the copy of a repository is made,  `git clone` creates a local copy and `git fork` creates a remote copy in your GitHub account. 

Aditionally, forking is an action typically used to collaborate on an upstream (original) remote repository that you do not own or you are not part of the core development team. It allows you to work on your own version of the code before submitting contributions throug pull requests. On the other hand, cloning is a git command used to work directly on a repository where you have write access to the original repository. 

*What is the difference between a fork and a branch?*

Forking is a GitHub action that creates a copy of an upstream repository in your own GitHub account. Depending on your forking settings, this action copies all commits and history or only a specific branch. In contrast, branching creates a new line of development inside a single repository. This means that your following code and commits are separated and labeled according to the branch (or line of development) in which you are working on. In this way, branching is a command that can isolate changes without affecting other parts of the repository. This command can be performed in Git or GitHub, in either local or remote repositories. 

*What advantages and disadvantages to code review can you imagine/list?*

 * Advantages
    * Better code quality: Code reviews help identify and fix problems before the code is merged.
    * Improved performance: They ensure that code can be optimized and improved, given that it’s reviewed by a second person.
    * Sharing knowledge: Experienced reviewers can give feedback to junior or beginner programmers in real time, in this way theres is a great opportunity to learn from each other

 * Disadvantages
    * Time-consuming: Reviewing code takes time, both for the reviewer and the original author who may need to make revisions.
    * Potential for personal conflicts: Depending on how feedback is provided, code reviews can lead to personal issues or tension between team members.
    * Delays in software delivery: Since the review process can take time, it may lead to delays in meeting project deadlines.
 