# angular-package

<a href='https://angular-package.dev' target='_blank'>
  <img align="right"  width="92" height="92" src="https://avatars.githubusercontent.com/u/31412194?s=400&u=c9929aa36826318ccac8f7b84516e1ce3af7e21c&v=4" />
</a>

The angular-package supports the development process of [angular](https://angular.io)-based applications in varied ways through the thoughtful, reusable, easy-to-use small pieces of code called packages.

<br>

<a href="https://angular-package.github.io/sass"><img src="https://sass-lang.com/assets/img/logos/logo.svg" width="92" height="92" /></a>

## Sass List

Sass List - Modified list Sass module.

[![Gitter][gitter-badge]][gitter-chat]
[![Discord][discord-badge]][discord-channel]
[![Twitter][twitter-badge]][twitter-follow]

<!-- npm badge -->
[![npm version][sass-list-npm-badge-svg]][sass-list-npm-badge]

<!-- GitHub badges -->
[![GitHub issues][sass-list-badge-issues]][sass-list-issues]
[![GitHub forks][sass-list-badge-forks]][sass-list-forks]
[![GitHub stars][sass-list-badge-stars]][sass-list-stars]
[![GitHub license][sass-list-badge-license]][sass-list-license]

<!-- Sponsors -->
[![GitHub Sponsors][github-badge-sponsor]][github-sponsor-link]
[![Patreon Sponsors][patreon-badge]][patreon-link]

Extended sass modules:

* The [`sass:list`](https://sass-lang.com/documentation/modules/list/) is extended by [`@angular-package/sass-list`](https://docs.angular-package.dev/v/sass/list/overview) - module makes it easy to combine, search, or split apart strings.

<br>

Sass extension is **free** to use. If you enjoy it, please consider donating via [fiat](https://docs.angular-package.dev/v/sass/donate/fiat), [Revolut platform](https://checkout.revolut.com/pay/048b10a3-0e10-42c8-a917-e3e9cb4c8e29) or [cryptocurrency](https://spectrecss.angular-package.dev/donate/thb-cryptocurrency) the [@angular-package](https://github.com/sponsors/angular-package) for further development. ♥  

> Feel **free** to submit a pull request. Help is always appreciated.

<br>

## Table of contents

* [Skeleton](#skeleton)
* [Code scaffolding](#code-scaffolding)
* [Documentation](#documentation)
  * [API](#api)
* [Changelog](#changelog)
* [Git](#git)
  * [Commit](#commit)
  * [Versioning](#versioning)
* [License](#license)

<br>

## Skeleton

This package was generated by the [skeleton workspace][skeleton] with [Angular CLI](https://github.com/angular/angular-cli) version `14.2.0`.

Copy this package to the `packages/sass-list` folder of the [skeleton workspace][skeleton] then run the commands below.

<br>

## Code scaffolding

Run `ng generate component component-name --project sass-list` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module --project sass-list`.
> Note: Don't forget to add `--project sass-list` or else it will be added to the default project in your `angular.json` file. 

## Build

Run `ng build sass-list` to build the project. The build artifacts will be stored in the `dist/` directory.

## Publishing

After building your library with `ng build sass-list`, go to the dist folder `cd dist/sass-list` and run `npm publish`.

## Running unit tests

Run `ng test sass-list` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

<br>

## Documentation

The documentation is in construction and it's available at [https://docs.angular-package.dev/v/sass-list](https://docs.angular-package.dev/v/sass-list/)

### Api

#### list.add()

```scss
list.add($list, $separator: auto, $value, $values...)
```

#### list.append()

```scss
list.add($list, $separator: auto, $value, $values...)
```

#### list.each()

```scss
list.each($list, $comma: true, $index: 1)
```

#### list.empty()

```scss
list.empty($list)
```

#### list.extract-map()

```scss
list.extract-map($list, $occurrence: first)
```

#### list.first()

```scss
list.first($list)
```

#### list.flatten()

```scss
list.flatten($list)
```

#### list.from()

```scss
list.from($list, $from) // TODO
```

#### list.has()

```scss
list.has($list, $occurrence: any, $operator: '==', $value, $values...) // TODO
```

#### list.index()

```scss
list.index($list, $value, $values...)
```

#### list.insert-nth()

```scss
list.insert-nth($list, $n, $value)
```

#### list.invert()

```scss
list.invert($list)
```

#### list.is-length()

```scss
list.is-length($list, $length)
```

#### list.join()

```scss
list.join(
  $list1,
  $list2,
  $separator: auto,
  $bracketed: auto,
  $delimiter: null
)
```

#### list.last()

```scss
list.last($list)
```

#### list.limit()

```scss
list.limit($list, $limit...)
```

#### list.merge()

```scss
list.merge($list1, $list2)
```

#### list.nth()

```scss
list.nth($list, $n, $nts...)
```

#### list.nths()

```scss
list.nths($list, $n...)
```

#### list.of()

```scss
list.of($list, $spec, $separator: null, $type: false)
```

#### list.range()

```scss
list.range($list, $from: 1, $to: list.length($list))
```

#### list.replace()

```scss
list.replace($list, $replace, $replacement)
```

#### list.select()

```scss
list.select(
  $select: index,
  $from: null,
  $operand: value,
  $operator: '==',
  $value,
  $values...
) // TODO
```

#### list.swap()

```scss
list.swap($list, $n, $to, $nth: list.nth($list, $n))
```

#### list.to-map()

```scss
list.to-map($list, $keys...)
```

#### list.to()

```scss
list.to($list, $to)
```

#### list.type()

```scss
list.type($list, $n...)
```

#### list.update()

```scss
list.update($list, $nth-value...)
```

### list.get-[method]

Get methods.

#### list.get-bool()

```scss
list.get-bool($list, $occurrence: first)
```

#### list.get-list()

```scss
list.get-list($list, $occurrence: first)
```

#### list.get-map()

```scss
list.get-map($list, $occurrence: first)
```

#### list.get-number()

```scss
list.get-number($list, $occurrence: first)
```

#### list.get-string()

```scss
list.get-string($list, $occurrence: first)
```

#### list.get-type()

```scss
list.get-type($list, $occurrence: any, $type, $types...)
```

### list.remove-[method]

Remove methods.

#### list.remove-duplicate()

```scss
list.remove-duplicate($list, $values...)
```

#### list.remove-list()

```scss
list.remove-duplicate($list, $values...) // TODO
```

#### list.remove-map()

```scss
list.remove-map($list)
```

#### list.remove-nth()

```scss
list.remove-nth($list, $n, $nts...)
```

#### list.remove-number()

```scss
list.remove-number($list)
```

#### list.remove-range()

```scss
list.remove-range($list, $from: 1, $to: list.length($list)) // TODO
```

#### list.remove-string()

```scss
list.remove-string($list)
```

#### list.remove-type()

```scss
list.remove-type($list, $type, $types...)
```

#### list.remove-value()

```scss
list.remove-value($list, $value, $values...)
```

<br>

## Changelog

To read it, click on the [CHANGELOG.md][sass-list-github-changelog] link.

<br>

## GIT

### Commit

* [AngularJS Git Commit Message Conventions][git-commit-angular]
* [Karma Git Commit Msg][git-commit-karma]
* [Conventional Commits][git-commit-conventional]

### Versioning

[Semantic Versioning 2.0.0][git-semver]

**Given a version number MAJOR.MINOR.PATCH, increment the:**

* MAJOR version when you make incompatible API changes,
* MINOR version when you add functionality in a backwards-compatible manner, and
* PATCH version when you make backwards-compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

**FAQ**
How should I deal with revisions in the 0.y.z initial development phase?

> The simplest thing to do is start your initial development release at 0.1.0 and then increment the minor version for each subsequent release.

How do I know when to release 1.0.0?

> If your software is being used in production, it should probably already be 1.0.0. If you have a stable API on which users have come to depend, you should be 1.0.0. If you’re worrying a lot about backwards compatibility, you should probably already be 1.0.0.

<br>

## License

MIT © angular-package ([license][sass-list-license])

<!-- Funding -->
[github-badge-sponsor]: https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/angular-package
[github-sponsor-link]: https://github.com/sponsors/angular-package
[patreon-badge]: https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dangularpackage%26type%3Dpatrons&style=flat
[patreon-link]: https://www.patreon.com/join/angularpackage/checkout?fan_landing=true&rid=0

[angulario]: https://angular.io
[skeleton]: https://github.com/angular-package/skeleton

<!-- Update status -->
[experimental]: https://img.shields.io/badge/-Experimental-orange
[fix]: https://img.shields.io/badge/-Fix-red
[new]: https://img.shields.io/badge/-eNw-green
[update]: https://img.shields.io/badge/-Update-red
[documentation]: https://img.shields.io/badge/-Documentation-informational
[demonstration]: https://img.shields.io/badge/-Demonstration-green

<!-- Discord -->
[discord-badge]: https://img.shields.io/discord/925168966098386944?style=social&logo=discord&label=Discord
[discord-channel]: https://discord.com/invite/rUCR2CW75G

<!-- Gitter -->
[gitter-badge]: https://img.shields.io/gitter/room/angular-package/ap-sass?style=social&logo=gitter
[gitter-chat]: https://app.gitter.im/#/room/#ap-sass:gitter.im

<!-- Twitter -->
[twitter-badge]: https://img.shields.io/twitter/follow/angularpackage?label=%40angularpackage&style=social
[twitter-follow]: https://twitter.com/angularpackage

<!-- GIT -->
[git-semver]: http://semver.org/

<!-- GIT: commit -->
[git-commit-angular]: https://gist.github.com/stephenparish/9941e89d80e2bc58a153
[git-commit-karma]: http://karma-runner.github.io/0.10/dev/git-commit-msg.html
[git-commit-conventional]: https://www.conventionalcommits.org/en/v1.0.0/

<!-- This package: sass  -->
  <!-- GitHub: badges -->
  [sass-list-badge-issues]: https://img.shields.io/github/issues/angular-package/sass-list
  [sass-list-badge-forks]: https://img.shields.io/github/forks/angular-package/sass-list
  [sass-list-badge-stars]: https://img.shields.io/github/stars/angular-package/sass-list
  [sass-list-badge-license]: https://img.shields.io/github/license/angular-package/sass-list
  <!-- GitHub: badges links -->
  [sass-list-issues]: https://github.com/angular-package/sass-list/issues
  [sass-list-forks]: https://github.com/angular-package/sass-list/network
  [sass-list-license]: https://github.com/angular-package/sass-list/blob/master/LICENSE
  [sass-list-stars]: https://github.com/angular-package/sass-list/stargazers
<!-- This package -->
  [sass-list-github-changelog]: https://github.com/angular-package/sass-list/blob/main/CHANGELOG.md

<!-- Package: sass-list -->
  <!-- npm -->
  [sass-list-npm-badge-svg]: https://badge.fury.io/js/@angular-package%2Fsass-list.svg
  [sass-list-npm-badge-png]: https://badge.fury.io/js/@angular-package%2Fsass-list.png
  [sass-list-npm-badge]: https://badge.fury.io/js/@angular-package%2Fsass-list
  [sass-list-npm-readme]: https://www.npmjs.com/package/@angular-package/sass-list#readme

  <!-- GitHub -->
  [sass-list-github-readme]: https://github.com/angular-package/sass-list#readme

