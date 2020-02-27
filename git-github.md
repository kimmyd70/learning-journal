### This link is a great source [Git intro](https://www.udemy.com/blog/git-tutorial-a-comprehensive-guide/#3)
Here are some highlights and takeaways:
* Git began as a distributed version control service (*DVCS*) in 2005
* It's useful to do some initial configuration via the Terminal such as adding name and e-mail to be included in file meta--we did that on Tuesday
* Git has built in help that can be accessed by:
    - git help command
    - git command --help
    - man git-command
   
 * The first thing we want to do is set up a repository.  We've already done this through GitHub, but you can also do it using Terminal
 
 * You can use the Terminal to clone a repository you've set up on GitHub in order to work on your computer with a repository’s URL: `$ git clone https://github.com/test`
 
 * GitHub manages files using a lifecycle that tracks what state your file is in.  Perfect for DVCS!
 ![GitHub lifecycle](https://user-images.githubusercontent.com/61428656/75408991-3f7dc080-58cc-11ea-9ca9-bc06a25c1c08.png)
 
 Several commands are useful when working with the files in Terminal:
* Track one file only by using the following format: `git add filename`
* Track all files in a repository by using the following command: `$ git add *`
* See information regarding changes to be committed when using the git status command: `$ git status`
* Committing a File: `$ git commit -m “made change x,y,z”` with a message on what changes were made
* Committing All Changes: `$ git commit -a`
* Pushing Changes: `$ git push origin master`
    - This command pushes changes from the local “master” branch to the remote repository named “origin”.
    - For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.
    
* When you are not ready to commit changes but do not want to lose them either, `$ git stash` is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the `$ git stash apply` command to retrieve the hidden changes. 
 
### Use this! [Git keyboard shortcuts](https://help.github.com/en/github/getting-started-with-github/keyboard-shortcuts)
