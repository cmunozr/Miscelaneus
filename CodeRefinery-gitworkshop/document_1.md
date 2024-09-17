# Document 1

Task: 
A document that shows that you did the exercises during the course. Note: if you are planning to delete the exercise repository from your GitHub projects, instead of sending links to your work you can send PDF screenshots e.g. by doing "print to PDF" with your browser.


## Day 1

*Write one or more paragraphs about Day 1 - Exercise 2: provide the link to the forked repository on your GitHub account and show that you did new commits. If you did not use GitHub and if you used the command line, then provide the output of the command git log --all for the forked repository. Explain what you did.*


In this exercise, I forked the “main” branch of the repository called “recipe-book” to my user "cmunozr". Having forked it, I created a new recipe for a main dish. In this recipe, I present the ingredients and instructions for risotto rice inside a new branch called “risotto”. The recipe is stored in a markdown document inside the “mains” folder. In the first commit, I created the document and fill out the recipe template, including ingredients and instructions. Then, in a second commit, I credited the author and linked to their webpage.

### Repository forked

[recipe-book](https://github.com/cmunozr/recipe-book)

## Day 2

*Write one or more paragraphs about Day 2 - Exercise 3: provide the link to the new repository you have created on your GitHub account. If you did not use GitHub and if you used the command line, then provide the output of the command git log --all for the newly created repository. Explain what you did*


In this exercise, I created a local repository called “myproject” and then pushed it to a remote repository. First, I created a folder called “myproject” locally. Then, using nano, I created three files. Using git, I initialized a local repository. The first commit added the three files and put the folder under version control. Later, I added a README.md document, created using nano. This latter file was committed. Once I had both commits ready locally, I created an empty repository called “myproject” on GitHub. This is the remote repository. I followed the instructions provided to push my existing local repository from the command line using the SSH protocol to the remote repository previously created on GitHub. This took my commits online to the remote repository.

### Repository created

[myproject](https://github.com/cmunozr/myproject)

### git log -all output

```

Carlos Munoz@lund_office MINGW64 /c/myproject (main)
$ git log --all
commit 07cde7dd8909495ac6a7641fbdb9f2f2d3fbc457 (HEAD -> main, origin/main)
Author: Carlos Munoz <cmunozbiol@gmail.com>
Date:   Mon Sep 16 12:09:06 2024 +0200

    adding readme to the repo

commit 81ce9508bcc6f69acdab32a969e68ebf4f24dd9f
Author: Carlos Munoz <cmunozbiol@gmail.com>
Date:   Mon Sep 16 12:06:46 2024 +0200

    putting my project under version control

```

## Day 3

*Write one or more paragraphs about Day 3 - Exercise 1: provide the link to the pull request. Explain what you did.*

In this exercise, I collaborated to improve the [recorded repository](https://github.com/cr-workshop-exercises). First, I requested access. Using the GitHub web interface, I created an issue suggesting a new soup called Ajiaco, a traditional dish from Colombia. After creating the issue, I made a new branch named “ajiaco_soup”. Within this branch, inside the soups folder, I created a new file called “ajiaco-soup.md”. I documented the ingredients, added more chicken to the recipe, and formatted the document in Markdown, all in three separate commits. Once the document was ready, I initiated a pull request. During this process, I learned how to cross-reference issues inside the pull request. However, my pull request has not yet been reviewed, so my changes do not appear in the main branch.

### Link to pull request

[Pull request](https://github.com/cr-workshop-exercises/centralized-workflow-exercise-recorded/pull/46)
