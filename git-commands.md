To Clone a repo onto your computer.
```shell
git clone ...
```

To create new branch.
```shell
git branch name-of-a-branch
```

To go the new branch
```shell
git checkout name-of-a-branch
```

To create a new branch, and switch to it.
```shell
git checkout -b name-of-a-branch
```

add changes to push
```shell
git add -A -a
```

committing changes to push
```shell
git commit -m "write a commit message."
```

Pushing changes to origin
```shell
git push origin name-of-a-branch
```

Add a new remote, fetch, and check out a branch from it
```shell
$ git remote
origin
$ git branch -r
  origin/HEAD -> origin/master
  origin/master
$ git remote add staging git://git.kernel.org/.../gregkh/staging.git
$ git remote
origin
staging
$ git fetch staging
...
From git://git.kernel.org/pub/scm/linux/kernel/git/gregkh/staging
 * [new branch]      master     -> staging/master
 * [new branch]      staging-linus -> staging/staging-linus
 * [new branch]      staging-next -> staging/staging-next
$ git branch -r
  origin/HEAD -> origin/master
  origin/master
  staging/master
  staging/staging-linus
  staging/staging-next
$ git switch -c staging staging/master
...
```
