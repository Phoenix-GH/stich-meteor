Weclome to the Meteor.js version of Stitch, build with SpaceTalk and Rocket.Chat.

### How to begin

Please check out the [roadmap](https://trello.com/b/CoZWhiRP/stitch-ii) and [issues](https://github.com/stitchtechnologies/stitch-meteor/issues) to see if there's anything you can help with.

### Prerequisites

* [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Meteor](https://www.meteor.com/install)

### Style Guide & Naming Conventions

* We're following [Meteor Style Guide](https://github.com/meteor/meteor/wiki/Meteor-Style-Guide)
* Template names: `<template name="camelCase"></template>`
* Route names: `dashed-case/routing-perhaps`
* File names: `dashed-case.html`, `dashed-case.js`
* Custom HTML id / class naming convention: `<div id="dashed-case"></div>` however class names preferred instead of using ids `<div class="some-custom-class"></div>`


### Getting started

To setup, run through the following:

```
git clone https://github.com/stitchtechnologies/stitch-meteor.git
```

Add the SpaceTalk remote source to your local clone:

```
git remote add upstream https://github.com/SpaceTalk/SpaceTalk.git
```

Start the app:

```
cd stitch-meteor
meteor run --settings=settings.json
```

To update your clone do a pull with SpaceTalk:

```
git pull upstream master
```

Commit your changes to your fork, and create Pull Request with [github helper](https://github.com/SpaceTalk/SpaceTalk/compare/master...#)

### Guidelines for reviewing Pull Requests

1. Code follows the [Meteor Style Guide](https://github.com/meteor/meteor/wiki/Meteor-Style-Guide)
2. Code doesn’t break things (The app can still run)

### Libraries

This project is in flux at the moment, these are the currently agreed upon client side libraries;

* CSS Pre-Processor: [Sass / .scss](http://sass-lang.com/)
* Icon Font Library: [FontAwesome](http://fortawesome.github.io/Font-Awesome/)


### License

Note that SpaceTalk is distributed under the [MIT License](http://opensource.org/licenses/MIT).

-------

Copyright © 2015 Stitch Technologies, Inc.
