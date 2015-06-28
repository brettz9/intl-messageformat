# Updating steps

1. Reflect any `package.json` changes in `bower.json`, such as changes to `version`.
1. Delete latest tag (see below)
1. Add new tag (see below).:

```
git tag -d v100.1.1
git push origin :refs/tags/v100.1.1

git tag -a v100.1.2 -m "Version 100.1.2 with bower.json"
git push origin --tags
```
