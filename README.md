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

