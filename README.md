> Extends the capabilities of Angular preset of [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog).

**If you want to make changes this version of the preset, please take a look at [how-to-make-changes](how-to-make-changes.md) file.**

## How to use

* Install conventional-changelog-cli globally by running

```
npm install -g conventional-changelog-cli
```

* Install `hipo-web-conventional-changelog` package as a dev dependency to your project.

```
npm install hipo-web-conventional-changelog --save-dev
```

* Generate a `changelog-context-variables.json` file at the root of your project and include the codebase project name for your project:

```
{
  "codebaseProjectName": "chroma"
}
```

* Create a script for generating changelog

```
{
  "changelog": "conventional-changelog --config ./node_modules/hipo-web-conventional-changelog/index.js --context ./changelog-context-variables.json -o CHANGELOG.md -r 0"
}
```

## Recommended workflow

- Make changes
- Commit those changes
- Bump version in package.json
- `npm run changelog`
- Commit package.json and CHANGELOG.md files
- Tag
- Push

## Convention

See Hipo web-handbook for [commit conventions](https://github.com/Hipo/web-handbook/blob/master/version-control-and-code-review.md#commit-messages).

The following commit types will appear in the changelog:
* feat
* fix
* perf
* revert
* refactor

Other commit types won't appear unless their footer includes `BREAKING CHANGES` notes.
