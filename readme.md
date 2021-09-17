# History

- First commit on master
```
git push
```

- Branching off master and fixing a bug
```
git checkout -b my_first_debug
# commit changes
git push --set-upstream origin my_first_debug
# perform MR, changes are now on master
```

- Branching off master an "open" branch 
```
git checkout master
git pull
# We're in sync with the repo
git checkout -b my_open_branch
```

- Branching off master another bug branch
```
git checkout master
git checkout -b my_second_bug
```

- Shipping things on my_open_branch
```
git checkout my_open_branch
# commit changes
git push
```
