# git


# Remote Repository 


## Branch

### Get branch list

```bash

# Local
git branch

# Remote
git branch -r

# All
git branch -a
```

### Checkout remote branch
```bash
git checkout -b <local-branch-name> <remote-name>/<remote-branch-name>
```

Ex.

```bash
git checkout -b my-feature-branch origin/feature-branch
```

