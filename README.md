#Git Cheat Sheet

First `init` a new repository to work with:

```
$ git init REPO_NAME
$ cd REPO_NAME

```

**Note** Directories are not tracked, just add a `.keep`file

To ignore files add them to`.gitignore`:

```
log/*.log
```

To just add parts of the index we cann use `git add -p` (`-p` as in "patch").
