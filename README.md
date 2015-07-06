# gh_test
Test git functionality

This file has been created by github during 

# Master branch
This section is added from master branch.

To get back to the default branch (``master``), use the command

    git checkout master

Thus, ``checkout`` changes files in the current folder to the current state of correspondent branch. And the ``branch`` command creates a new branch.
Changes in this state will go the the ``master`` branch, at least if nothing is specified like here:

    # modify content
    vi README.md

    # commit to current branch
    git add README.md
    git commit -m "Adding again to master branch."

    # send to server
    git push

The last commands again writes a message and sends info to the ``master`` branch.




