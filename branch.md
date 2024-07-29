

# Git Branch

## list branch 

```bash

# Local
git branch

# Remote
git branch -r

# All
git branch -a
```

## Local branch

## Remote branch

### Create/Delete remote branch

#### Create

```bash
git checkout -b feature-01
git push origin feature-01
git branch --set-upstream-to origin/feature-01
```

#### Delete

```bash
git checkout develop # move to different branch

git branch --delete feature-01
# or
git branch -D feature

git push origin origin :feature-01
```

* [Git 리모트 브랜치 생성 및 삭제하기](https://trustyoo86.github.io/git/2017/11/28/git-remote-branch-create.html)

### Checkout remote branch
```bash
git checkout -b <local-branch-name> <remote-name>/<remote-branch-name>
```

Ex.

```bash
git checkout -b my-feature-branch origin/feature-branch
```



