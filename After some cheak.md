<h1>Checking the log of Git commits</h1>

1- To check the log of the commits to your Git repository, type
`git log --oneline`

<h1>Checking out a file from an earlier commit</h1>

2- To check out the index.html from the second commit, find the number of the second commit using the git log, and then type the following at the prompt:
`git checkout <second commit's number> index.html`

<h1>Resetting the Git repository</h1>

3- To discard the effect of the previous operation and restore index.html to its state at the end of the third commit, type:
`git reset HEAD index.html`

4- Then type the following at the prompt:
`git checkout -- index.html`
