This repo was created from a sub-tree split of [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) monorepo. You can still get the latest updates from the main `conventional-changelog` repo by following this guide. Here are the details about how the angular preset was splitted from the monorepo following this [answer](https://stackoverflow.com/questions/24577084/forking-a-sub-directory-of-a-repository-on-github-and-making-it-part-of-my-own-r):

* The `conventional-changelog` monorepo was cloned.
* The master of `conventional-changelog` was renamed to `upstream-master`.
* `packages/conventional-changelog-angular` part of the monorepo was split off and a branch that containing only the files inside `packages/conventional-changelog-angular` was created. This branch's name is `upstream-conventional-changelog-angular`.
* The original remote origin was renamed to `upstream` and `https://github.com/Hipo/hipo-web-conventional-changelog` was added as the remote origin.
* A new branch named as `master` was created from `upstream-conventional-changelog-angular` branch and it was pushed to the `https://github.com/Hipo/hipo-web-conventional-changelog` with `git push -u origin master`.

### Commiting changes to this repo

You need to checkout to `master` branch and do your changes (or from another branch and open a PR to `master`) from there and not touch `upstream` branches.

```
git checkout master
echo "New changes to this repo" > README
git add README
git commit -m "New changes"
git push
```

### Receiving upstream commits

```
git checkout upstream-master
git pull
```

Update `upstream-conventional-changelog-angular` branch while still one `upstream-master`.

```
git subtree split --prefix=addons/skin.confluence \
  --onto upstream-skin -b upstream-skin
```

Now update your `master` branch with `upstream-conventional-changelog-angular`:
```
git checkout master
git rebase upstream-skin
```
