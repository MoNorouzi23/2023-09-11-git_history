# 2023-09-11-git_history
Head
`add <FILENAME>`: adding the <FILENAME> to the staging area
`commit -m "MESSAGE"`: commit with a message everything in the staging area
`Push <where> <what>`: pushes the history /commits to the remote(where) using the commits from the specified branch (what)
`pull <where? <what>`: pulls (updates)the local repo with conents in the remote repo
`log`: shows the log
    `log --oneline`: shows the log in condenced format
    this may opeb a terminal program called `less`that lets you scroll
    use `q` to quit out of less

`diff`: shows you the differences between your changes and last known git state
`diff --staged`: shows you the diff of the files in the staging area 
`restore --staged <file>`: unstage <file> from the staging area
`revert <SHA1>`: undo the changes in the commit specified in <SHA1>
