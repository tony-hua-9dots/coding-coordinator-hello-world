### git add [_filename_]
Adds the current (saved) version of a file to staging.

### git add .
Adds all files in your current directory, and their subdirectories, to staging.

### git branch [_branch_name_]
Creates a new branch.

### git branch -u origin/[_remote_branch_name_]
Sets _remote_branch_name_ as the upstream of your current branch, so you can use git push without arguments (among other things).

### git checkout [_branch_name_]
Switches branches.

### git checkout -b [_new_branch_name_]
Creates a new branch and checks it out.

### git clone [_url_]
Clones a repository to a new directory on your computer.

### git commit -m "[_commit_message_]"
Commits everything in staging to your current branch.

### git merge [_branch_name_]
Merges _branch_name_ into your current branch.

### git push
Pushes your current branch to its upstream branch. Only works if an upstream has been set.

### git push origin [_remote_branch_name_]
Pushes your current branch to _remote_branch_name_ on the remote origin repository.

### git push -u origin [_remote_branch_name_]
Pushes your current branch to _remote_branch_name_ on the remote origin repository, **and** sets _remote_branch_name_ as the upstream of your branch, so you can use git push without arguments (among other things).

### git status
Displays helpful status information.
