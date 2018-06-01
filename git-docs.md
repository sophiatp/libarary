# Git documentation

## push force
Using when you have more than one commit.
From second commit, flow this instruction:

$ git add .
$ git commit --amend  // Rewrite commit message if you want
$ git push origin <feature-branch> --force  // Can use -f instead of --force

By this way, your branch always has only one commit!
