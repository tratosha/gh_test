# gh_test
Test git functionality

This file has been created by github during initialization of the repository. 

# Master branch
This section is added from master branch. To add it, the following commands were issued:

    # get files to local disk
    git clone https://github.com/tratosha/gh_test.git

    # edit file
    vi README.md

    # commit to local repo and send to server
    git add README.md
    git commit -m "Message ... "
    git push 

The last command generated some message about different default behaviour in current and previous versions of git.
    


# dev1 branch
This branch has been created on the local workplace by the command

    git checkout -b dev1

After this, some text has been added here and a commit to current branch has been made:

    vi README.md
    git add README.md
    git commit -m "Added to dev1 branch."

To send the modifications to a new branch on the server, use

    git push --set-upstream origin dev1

After this command, a new branch, named ``dev1`` hs become visible in the web interface. 
