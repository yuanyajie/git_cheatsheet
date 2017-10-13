-   Checking out an old commit (detached HEAD)

        git checkout <commit>
-   Creating a new branch from the detached HEAD state

        git checkout -b old_version
-   Reverting one file (need to commit to keep the changes)
        
        git checkout <commit> <file>
-   Reverting one commit

        git revert
-   Reverting to a commit by deleting children commit (dangerous)

        git reset
