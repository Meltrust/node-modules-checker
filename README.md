# test-new-linter
A GitHub action that contains a Bash script that asserts for a node_modules folder existence in the branch to be merged.  

If the branch contains the node_modules folder, the PR will display an error so the user knows the situation.
Upon clicking on the error an explanation of the error will be displayed along with a possible adequate solution (e.g. adding the node_modules folder to .gitignore).
