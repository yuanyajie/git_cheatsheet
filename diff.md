# Checking differences

-   Checking unstaged changes

        git diff
-   Checking staged changes

        git diff --cached
-   Comparing commits

        git diff old_commit..new_commit
-   Looing at the changes in one file between commits

        git commit old_commit..new_commit filename
-   Using HEAD to get the latest commit

        git diff 2896f02..HEAD
-   Showing the changes in commit

        git show <commit> (<file>)
