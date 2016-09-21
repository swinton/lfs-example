# Git LFS Example

Tracking `.zip` files in LFS.

## Example

First, track those `.zip` files:

```
git lfs track *.zip
```

Next create a `.zip` file:

```
cat > hello-world.md
zip hello-world hello-world.md
git add hello-world.zip
git commit
git push
```

To examine the pointer:

```
git show HEAD:hello-world.zip
```

## Resources

1. [This tutorial](https://github.com/github/git-lfs/wiki/Tutorial)
1. [This guide on setting up LFS on GitHub Enterprise](https://help.github.com/enterprise/admin/guides/installation/git-large-file-storage-on-github-enterprise/)
1. [This article on configuring LFS for a GitHub Enterprise repository](https://help.github.com/enterprise/admin/articles/configuring-git-large-file-storage-for-a-repository/)

