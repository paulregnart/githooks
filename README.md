# githooks
Githooks  provide arbitary checks before commiting using git.

This hook searches the git commit log for any changes about to be committed to a given directory. If there are changes, a message/warning is displayed.

In this example, the database folder in a rails app is being checked.

##Usage

1. Amend the SRC_PATTERN to the name of folder you want to check.
2. Change the message to what you want.

For more info: https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks 
