# cpdo-aew-w14-gh_actions

Alpha E&amp;W W14 - Github Actions

Managing local inits
```zsh
git init #
git remote add origin {my forked repo url}          # Adds remote connection called origin
git remote add upstream {source repo url}           # Adds remote connection called upstream

git remote set-url origin {}                        # Reconfigures the url for a remote connection

git remote -v                                       # Verbose flag:  Display the URLs along with remote connections
git status                                          # check commit and branch status
```

```zsh
git add {filename}                                  # Add a change
git commit -m {message}                             # Commit any additions
git commit -am {message}                            # Add and commit simultaneously
git push {remote} {branchname}                      # Push a change

```

```zsh
git clone {url}                                     # Pulling down a fork or source repo
git fetch origin main                               # Retrieves historical branch and commit data
git pull origin main -f --allow-unrelated-histories # Useful for merging an existing new repo with an existing new local repo
git rebase -i HEAD~n                                # Interactively squash n number of commits
```

```zsh
git tag -a v1.0.0 -m 'Message to annotate'          # Add a tag with an annotated message
git tag                                             # Display all tags
git tag -l 'v1.2*'                                  # Search for tag range

```

```zsh

```