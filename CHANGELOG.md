# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.8.0](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.7.4...v1.8.0) (2022-06-08)


### Features

* **tags and attributes:** added missing angular material and cdk tags and improved attributes ([5789d20](https://github.com/ghaschel/vscode-angular-syntax/commit/5789d2049d205ae79802edf81c85898309242b0a))

### [1.7.4](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.7.3...v1.7.4) (2022-06-01)


### Bug Fixes

* **tag-definition:** added missing mat-pseudo-checkbox tag ([c977af0](https://github.com/ghaschel/vscode-angular-syntax/commit/c977af0a67a23cdba1e663b19dffeb456a241f5e))

### [1.7.3](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.7.2...v1.7.3) (2022-06-01)


### Bug Fixes

* **added missing ng structural tag:** added missing mat-selection-list material tag ([5e40843](https://github.com/ghaschel/vscode-angular-syntax/commit/5e4084331c70fad465971da72236ac4545fa65a8))

### [1.7.2](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.7.1...v1.7.2) (2022-06-01)


### Bug Fixes

* **tag-definition:** fixed an issue with mat-list-option and mat-card-title-group ([9f78b18](https://github.com/ghaschel/vscode-angular-syntax/commit/9f78b18037581dace8a02e95cb97d0aa6697d21e))

### [1.7.1](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.7.0...v1.7.1) (2022-05-03)


### Bug Fixes

* **style-tag:** fixed style tag detection to allow detection of components starting with <style ([70e209a](https://github.com/ghaschel/vscode-angular-syntax/commit/70e209ad23a1094728fbcc8ab3fae5e90c355f1f)), closes [#48](https://github.com/ghaschel/vscode-angular-syntax/issues/48)

## [1.7.0](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.6.0...v1.7.0) (2020-02-19)


### Features

* **mat-drawer:** added support for mat-drawer and mat-drawer-content ([787efd9](https://github.com/ghaschel/vscode-angular-syntax/commit/787efd9d826ade8a16de4ca0ad030d8205ef6c38))

## [1.6.0](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.5.0...v1.6.0) (2020-01-28)


### Features

* **prefixed-attributes:** added highlighting for let- and ref prefix ([22df9bc](https://github.com/ghaschel/vscode-angular-syntax/commit/22df9bcd6e74fc45a6be0f5d71dc601348d64094))


### Bug Fixes

* **main-scope:** attempt to fix a bug where highlithting strips off ([658bbd9](https://github.com/ghaschel/vscode-angular-syntax/commit/658bbd914088e587efba77c85f615bba40cc7f09)), closes [#32](https://github.com/ghaschel/vscode-angular-syntax/issues/32)
* **script-tag:** fixed script tag with src attributes ([00a9e82](https://github.com/ghaschel/vscode-angular-syntax/commit/00a9e82dc8d38c15a3754649b27f16c7b3ad4bc2))

## [1.5.0](https://github.com/ghaschel/vscode-angular-syntax/compare/v1.4.0...v1.5.0) (2020-01-02)


### Features

* **prefixed-attributes:** added highlighting for let- and ref prefix ([b4ed81d](https://github.com/ghaschel/vscode-angular-syntax/commit/b4ed81dd6a9ee8c669b77594fea3f0bef4096886))


### Bug Fixes

* **main-scope:** attempt to fix a bug where highlithting strips off ([f113a35](https://github.com/ghaschel/vscode-angular-syntax/commit/f113a35dffaf4e75de33ad2ef0d104f5a97500a1)), closes [#32](https://github.com/ghaschel/vscode-angular-syntax/issues/32)

# 1.3.1 (13/09/2019)

- Fixed `s` tag being marked as deprecated [#29](https://github.com/ghaschel/vscode-angular-html/issues/29)

# 1.3.0 (23/08/2019)

- Fixed missing `router-outlet` to structural tags differentiation [#24](https://github.com/ghaschel/vscode-angular-html/issues/24)
- Added color differentiatio for pipes [#26](https://github.com/ghaschel/vscode-angular-html/issues/26)
- Fixed missing highlighting for single asterisk [#27](https://github.com/ghaschel/vscode-angular-html/issues/27)

# 1.2.0 (23/08/2019)

- Fixed the dom events that were being overwritted by the attributes without equal [#25](https://github.com/ghaschel/vscode-angular-html/issues/25)
- Added `else` and `then` keywords to \*ngIf directives [#23](https://github.com/ghaschel/vscode-angular-html/issues/23)
- Added color differentiation for angular structural tags [#24](https://github.com/ghaschel/vscode-angular-html/issues/24)

# 1.1.4 (15/08/2019)

- Fixed an issue with tags starting with deprecated tag names [#22](https://github.com/ghaschel/vscode-angular-html/issues/22)

# 1.1.3 (14/08/2019)

- Fixed an issue with multiple directives/attributes at the sime line. [#20](https://github.com/ghaschel/vscode-angular-html/issues/20)

# 1.1.2 (24/05/2019)

- Fixed an issue with angular attributes with underlines

# 1.1.1 (02/02/2019)

- Removed junk

# 1.1.0 (_02/02/2019_)

- Added highlighting for uppercase constants (it was white before)

# 1.0.3 (_28/12/2018_)

- Stupid mistake

# 1.0.2 (_28/12/2018_)

- Minor fixes in scope naming

# 1.0.1 (_12/12/2018_)

- Returned the language id to html until I figure it out the language server thing and prevent it from not having intelisense support for HTML.

# 1.0.0 (_11/12/2018_)

- Changed a lot of scope names for a more concise naming. See [scope names](SCOPE-NAMES.md) (Work in Progress)
- Changed language id from html to angular-html, so that it doesn't overwrite the default html syntax highlighting. (Althought this breaks support for icons on vscode-icons)

# 0.10.4 (_27/11/2018_)

- Cleaning in angular template expressions
- Updated version numbers and changelog to properly follow SemVer

# 0.10.3 (_25/11/2018_)

- Cleaning in angular template expressions

# 0.10.2 (_23/11/2018_)

- Fixed issue with safe operators inside function parameters
- Transformed adapted ts json to multiple json5 for a better maintability.
- Removed some surely not used ts scopes on templates (not all of them yet)

# 0.10.1 (_22/11/2018_)

- Improvements in gulpfile
- Although it's far from optimized yet, managed to fix the issue with angular expressions without semicolon at the end. [#15](https://github.com/ghaschel/vscode-angular-html/issues/15)

# 0.10.0 (_21/11/2018_)

- Style tag support (scss/stylus)

# 0.9.0 (_20/11/2018_)

- Code was improved by a thousand percent
- Removed unused patterns
- Fixed angular interpolations not being recognized inside strings in attributes [#9](https://github.com/ghaschel/vscode-angular-html/issues/9)
- Fixed minified boolean attributes [#11](https://github.com/ghaschel/vscode-angular-html/issues/11)
- Fixed strings not being recogized inside ngClass
- Improved html entities
- Fixed double quote recognition at the beginning of angular directives in other themes
- Visual differentiation between angular directives (ngFor, ngIf, bindings) and html attributes.
- Fixed the issue with `let` [#13](https://github.com/ghaschel/vscode-angular-html/issues/13)
- Switched angular directive unit scope with directive attribute name for better highlighting.

# 0.8.5 (_18/11/2018_)

- Improved generic attribute pattern

# 0.8.4 (_14/11/2018_)

- Further differentiation from attribute names and variables in angular directions. (Applied `support.type.object.module.html` scope)

# 0.8.3 (_14/11/2018_)

- Fixed deprecated tags
- Removed unused patterns
- Improved operator in angular directives and angular interpolations

# 0.8.2 (_12/11/2018_)

- Improves even further the previous issue

# 0.8.1 (_12/11/2018_)

- Fixed security issues pointed by Github with package-lock.json
- Fixed gulpfile tasks
- Fixes the case where normal attributes would apply text color to the next attributes that didn't have a newline before. [#6](https://github.com/ghaschel/vscode-angular-html/issues/6)

# 0.8.0 (_09/11/2018_)

- Support for DOCTYPE

# 0.7.0 (_08/11/2018_)

- Support for style binding with units `[style.font-size.px]="15"`
- Fixed self closing tags with space before being shown as blue instead of gray [#5](https://github.com/ghaschel/vscode-angular-html/issues/5)
- Fixed invalid attribute tag input pattern matching

# 0.6.9 (_08/11/2018_)

- Removed `$` from `[@]` highlight as it makes no sense.
- Returned `</>` colors to default keep it similar to any other HTML highlighting (feedbacks are welcome)
- Fixed issue with attributes value not being applied string scope name. [#4](https://github.com/ghaschel/vscode-angular-html/issues/4)

# 0.6.8 (_07/11/2018_)

- Fixed bug related to single quote. [#3](https://github.com/ghaschel/vscode-angular-html/issues/3)

# 0.6.7 (_07/11/2018_)

- Improved angular directive pattern matching to work with `[attr.test]`, `[@test]` and `[@$test]`

# 0.6.6 (_04/11/2018_)

- Improved tag start and end highlighting. [#2](https://github.com/ghaschel/vscode-angular-html/issues/2)

# 0.6.5 (_31/10/2018_)

- Improved tag script matching (still not perfect)

# 0.6.4 (_31/10/2018_)

- Stupid mistake

# 0.6.3 (_31/10/2018_)

- Code normalization
- Enforce entities scope to '=' on all occurrences (temporary)

# 0.6.2 (_31/10/2018_)

- Improved regex matching
- Fixed some scope names
- Fixed some includes
- Clutter removal
- Somehow managed to fix the issue with the attribute having no value (:ghost:) - only partially
- Highlighting for operators, safe operators, dots, commas, semicolons in angular interpolations and angular directives
- Improved punctuation and keyword such as var, let, const highlighting in inline script tags.

# 0.6.1 (_30/10/2018_)

- Improved script tag pattern matching (still not perfect)

# 0.6.0 (_30/10/2018_)

- Added support for script tags with content (not perfect yet)

# 0.5.0 (_29/10/2018_)

- Added support for style inline.

# 0.4.0 (_29/10/2018_)

- Changes in scope names.
- Initial support for invalid attributes in specific html tags. See [deprecated attributes](DEPRECATED-ATTRIBUTES.md).
- Improved generic attribute pattern recognition.

# 0.3.4 (_26/10/2018_)

- Improved attributes and events pattern (they were conflicting with angular directives).

# 0.3.3 (_26/10/2018_)

- Improved angular interpolation patterns by applying regex scope for brackets for a more readable content.
- Fixed Angular directives bracket matching and conflicts with events.

# 0.3.2 (_26/10/2018_)

- Changes in the deprecated tag recognition pattern for opening space for invalid attributes (not perfect yet).
- Fixed angular directive patterns that stopped recognizing attributes begining with "#" and "\*".

# 0.3.1 (_25/10/2018_)

- Changed the angular interpolations scope from punctuation to regex to take advantage of a more commonly seen regex syntax highlithing.
- Improved regex pattern matching.
- Initial support for deprecated tags. See [deprecated tags](DEPRECATED-TAGS.md).

# 0.3.0 (_24/10/2018_)

- Changes in scope names
- Added regex highlighting.
- Added ng-template and ng-container as block elements alongside html5's template tag.
- Removal of \[CDATA\] pattern as it is not usable inside of Angular's template file.
- Fixed the case when attributes would have their "=" colored.

# 0.2.1 (_24/10/2018_)

- Fixed tag opening and closing recognition caused by conflicts.
- Removal of XML pattern as it is not usable inside of Angular's template file.

# 0.2.0 (_23/10/2018_)

- Changes in scopes names.
- Fixed the issue with tag auto closing.
- Fixed the issue with vscode-icons.
- Fixed some conflicts in HTML attributes and Angular directives.
- Support for DOM events. See [DOM events](DOM-EVENTS.md).

# 0.1.0 (_15/10/2018_) - Fork

- Code rewrite for a better maintability.
- Added support for bindings and template variables: `()`, `[]`, `[()]`, `#`.

## 0.0.3 (_07-05-2018_)

- Update scope names.
- Add icon.

## 0.0.2 (_06-29-2018_)

- Update readme.
- Fix issue with filename.

## 0.0.1 (_06-29-2018_)

- Init.
