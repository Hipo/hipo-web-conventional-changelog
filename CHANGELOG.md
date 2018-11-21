# [5.3.0](https://github.com/Hipo/hipo-web-conventional-changelog/compare/5.2.0...5.3.0) (2018-11-21)



# [5.2.0](https://github.com/Hipo/hipo-web-conventional-changelog/compare/1bc7a87...5.2.0) (2018-11-21)


* [Angular Package] Adapt to new Angular Commit Conventions (#296) ([4a033a7](https://github.com/Hipo/hipo-web-conventional-changelog/commit/4a033a7)), closes [#296](https://github.com/Hipo/hipo-web-conventional-changelog/issues/296)


### Bug Fixes

* **angular:** smarter username detection ([#219](https://github.com/Hipo/hipo-web-conventional-changelog/issues/219)) ([f7e6a3b](https://github.com/Hipo/hipo-web-conventional-changelog/commit/f7e6a3b)), closes [#218](https://github.com/Hipo/hipo-web-conventional-changelog/issues/218)
* **template:** whitespace ([c692806](https://github.com/Hipo/hipo-web-conventional-changelog/commit/c692806))
* **template:** wrong version link if no host ([cb029da](https://github.com/Hipo/hipo-web-conventional-changelog/commit/cb029da)), closes [#8](https://github.com/Hipo/hipo-web-conventional-changelog/issues/8)
* Fix plurality of "are" vs. "is" ([#331](https://github.com/Hipo/hipo-web-conventional-changelog/issues/331)) ([0ede849](https://github.com/Hipo/hipo-web-conventional-changelog/commit/0ede849))
* revert previous change ([94d51aa](https://github.com/Hipo/hipo-web-conventional-changelog/commit/94d51aa))
* update to reference conventional-changelog org ([1314559](https://github.com/Hipo/hipo-web-conventional-changelog/commit/1314559))
* Upgrade to Lerna 3, fix Node.js v11 error ([#385](https://github.com/Hipo/hipo-web-conventional-changelog/issues/385)) ([586b2de](https://github.com/Hipo/hipo-web-conventional-changelog/commit/586b2de))


### Chores

* **package:** set Node requirement to oldest supported LTS ([#329](https://github.com/Hipo/hipo-web-conventional-changelog/issues/329)) ([f9b545a](https://github.com/Hipo/hipo-web-conventional-changelog/commit/f9b545a))


### Code Refactoring

* **issueUrl:** remove unneeded code ([cb6dfe2](https://github.com/Hipo/hipo-web-conventional-changelog/commit/cb6dfe2))
* **templates:** make it easier to read ([8cde0da](https://github.com/Hipo/hipo-web-conventional-changelog/commit/8cde0da)), closes [#11](https://github.com/Hipo/hipo-web-conventional-changelog/issues/11)
* **test:** use better-than-before ([75c740a](https://github.com/Hipo/hipo-web-conventional-changelog/commit/75c740a))
* remove anchor from header templates ([#298](https://github.com/Hipo/hipo-web-conventional-changelog/issues/298)) ([81ad7d4](https://github.com/Hipo/hipo-web-conventional-changelog/commit/81ad7d4)), closes [#186](https://github.com/Hipo/hipo-web-conventional-changelog/issues/186)
* remove anchor from header templates ([#301](https://github.com/Hipo/hipo-web-conventional-changelog/issues/301)) ([cace350](https://github.com/Hipo/hipo-web-conventional-changelog/commit/cace350)), closes [#186](https://github.com/Hipo/hipo-web-conventional-changelog/issues/186)


### Features

* **angular:** find package.json from cwd upwards ([#206](https://github.com/Hipo/hipo-web-conventional-changelog/issues/206)) ([7df039b](https://github.com/Hipo/hipo-web-conventional-changelog/commit/7df039b))
* **angular:** use the context for getting the repository and host urls ([#217](https://github.com/Hipo/hipo-web-conventional-changelog/issues/217)) ([b275619](https://github.com/Hipo/hipo-web-conventional-changelog/commit/b275619))
* **exports:** export the promise ([9ebb262](https://github.com/Hipo/hipo-web-conventional-changelog/commit/9ebb262))
* **github:** adds github-specific replacements for issues and users ([9302f91](https://github.com/Hipo/hipo-web-conventional-changelog/commit/9302f91)), closes [#12](https://github.com/Hipo/hipo-web-conventional-changelog/issues/12)
* **init:** extracting code from https://github.com/ajoslin/conventional-changelog ([1bc7a87](https://github.com/Hipo/hipo-web-conventional-changelog/commit/1bc7a87))
* **noteKeywords:** make BREAKING CHANGE more forgiving ([283b223](https://github.com/Hipo/hipo-web-conventional-changelog/commit/283b223))
* **preset:** add recommended-bump opts into presets ([cd44361](https://github.com/Hipo/hipo-web-conventional-changelog/commit/cd44361)), closes [#241](https://github.com/Hipo/hipo-web-conventional-changelog/issues/241)
* **references:** remove references that already appear in the subject ([6c72dc2](https://github.com/Hipo/hipo-web-conventional-changelog/commit/6c72dc2))
* migrate repo to lerna mono-repo ([938381c](https://github.com/Hipo/hipo-web-conventional-changelog/commit/938381c))
* **template:** bold scope in breaking change ([dc74d33](https://github.com/Hipo/hipo-web-conventional-changelog/commit/dc74d33))
* **template:** use context.repoUrl ([b5d767d](https://github.com/Hipo/hipo-web-conventional-changelog/commit/b5d767d))
* **writer-opts:** Customize for Hipo convention ([f29d37b](https://github.com/Hipo/hipo-web-conventional-changelog/commit/f29d37b))
* **writerOpts.transform:** do not discard commit if there is BREAKING CHANGE ([c477955](https://github.com/Hipo/hipo-web-conventional-changelog/commit/c477955)), closes [ajoslin/conventional-changelog#127](https://github.com/ajoslin/conventional-changelog/issues/127) [angular/angular#5672](https://github.com/angular/angular/issues/5672) [angular/angular#5762](https://github.com/angular/angular/issues/5762)
* re-use parser options within each preset ([#335](https://github.com/Hipo/hipo-web-conventional-changelog/issues/335)) ([3e1b573](https://github.com/Hipo/hipo-web-conventional-changelog/commit/3e1b573)), closes [#241](https://github.com/Hipo/hipo-web-conventional-changelog/issues/241)
* remove commit length restriction ([b6a60d1](https://github.com/Hipo/hipo-web-conventional-changelog/commit/b6a60d1)), closes [#12](https://github.com/Hipo/hipo-web-conventional-changelog/issues/12)


### BREAKING CHANGES

* re-use parser options within each preset ([#335](https://github.com/Hipo/hipo-web-conventional-changelog/issues/335)) ([3e1b573](https://github.com/Hipo/hipo-web-conventional-changelog/commit/3e1b573))<div>
Re-use parser options object between components of a preset. For some
presets this may change the behavior of `conventional-recommended-bump`
as the parser options object for the `conventional-recommended-bump` options
within a preset were different than the parser options object for the
`conventional-changelog` options within a preset.

If you are not using `conventional-recommended-bump`, then this is
**not** a breaking change for you.
</div>

* **package:** set Node requirement to oldest supported LTS ([#329](https://github.com/Hipo/hipo-web-conventional-changelog/issues/329)) ([f9b545a](https://github.com/Hipo/hipo-web-conventional-changelog/commit/f9b545a))<div>
Set the package's minimum required Node version to be the oldest LTS
currently supported by the Node Release working group. At this time,
that is Node 6 (which is in its Maintenance LTS phase).
</div>

* remove anchor from header templates ([#301](https://github.com/Hipo/hipo-web-conventional-changelog/issues/301)) ([cace350](https://github.com/Hipo/hipo-web-conventional-changelog/commit/cace350))<div>
Anchor tags are removed from the changelog header templates. The
rendered Markdown will no longer contain anchor tags proceeding the
version number header that constitutes the changelog header. This means
that consumers of rendered markdown will not be able to use a URL that
has been constructed to contain a version number anchor tag reference,
since the anchor tag won't exist in the rendered markdown.

It's stronly recomended consumers use the full URL path to the release
page for a given version, as that URL is a permalink to that verison,
contains all relavent release information, and does not, otherwise, rely
on the anchor tag being excessible from the current page view.

As an example, for version `2.0.0` of a GitHub project, the following
URL should be used:
- https://github.com/conventional-changelog/releaser-tools/releases/tag/v2.0.0
</div>

* [Angular Package] Adapt to new Angular Commit Conventions (#296) ([4a033a7](https://github.com/Hipo/hipo-web-conventional-changelog/commit/4a033a7))<div>
  The Angular conventions specifically say that breaking changes must
  start with "BREAKING CHANGE", not the plural form. Therefore the
  previous plural form "CHANGES" has been corrected to singular "CHANGE".

  Former "chore" type has been replaced by a type "build" for commits on
  the build system and "ci" for commits regarding CI
</div>




