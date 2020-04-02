# git

```sh
# cleanup .git http://gcc.gnu.org/ml/gcc/2007-12/msg00165.html
git repack -a -d --depth=250 --window=250

# reset to previous commit
git reset HEAD~
```

```bash
# Set PGP key for Git globally.
# <key> = fingerprint w/o spaces
git config --global user.signingkey <key>
```

```bash
# Delete commit from remote.

# 1. Delete commit from local repo
git reset --hard HEAD~1

# 2. Delete commit from remote repo (can get commit using git log)
git push -f origin last_known_good_commit:branch_name
```
