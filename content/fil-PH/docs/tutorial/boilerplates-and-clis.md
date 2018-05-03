# Boilerplates at CLIs

Electron development is un-opinionated - there is no "one true way" to develop, build, package, or release an Electron application. Additional features for Electron, both for build- and run-time, can usually be found on [npm](https://www.npmjs.com/search?q=electron) in individual packages, allowing developers to build both the app and build pipeline they need.

That level of modularity and extendability ensures that all developers working with Electron, both big and small in team-size, are never restricted in what they can or cannot do at any time during their development lifecycle. However, for many developers, one of the community-driven boilerplates or command line tools might make it dramatically easier to compile, package, and release an app.

## Boilerplates laban sa CLIs

A boilerplate is simply a starting point - a canvas, so to speak - from which you build your application. They usually come in the form of a repository you can clone and customize to your heart's content.

A command line tool on the other hand continues to support you throughout the development and release. They are more helpful and supportive but enforce guidelines on how your code should be structured and built. *Especially for beginners, using a command line tool is likely to be helpful*.

## pagpipilit ng elektron

A "complete tool for building modern Electron applications". Electron Forge unifies the existing (and well maintained) build tools for Electron development into a simple, easy to use package so that anyone can jump right in to Electron development.

Forge comes with [ready-to-use templates](https://electronforge.io/templates) for popular frameworks like React, Vue, or Angular. It uses the same core modules used by the greater Electron community (like [`electron-packager`](https://github.com/electron-userland/electron-packager)) –  changes made by Electron maintainers (like Slack) benefit Forge's users, too.

You can find more information and documentation on [electronforge.io](https://electronforge.io/).

## pagbubuo ng elektron

A "complete solution to package and build a ready-for-distribution Electron app" that focuses on an integrated experience. [`electron-builder`](https://github.com/electron-userland/electron-builder) adds one single dependency focused on simplicity and manages all further requirements internally.

`electron-builder` replaces features and modules used by the Electron maintainers (such as the auto-updater) with custom ones. They are generally tighter integrated but will have less in common with popular Electron apps like Atom, Visual Studio Code, or Slack.

You can find more information and documentation in [the repository](https://github.com/electron-userland/electron-builder).

## electron-react-boilerplate

If you don't want any tools but simply a solid boilerplate to build from, CT Lin's [`electron-react-boilerplate`](https://github.com/chentsulin/electron-react-boilerplate) might be worth a look. It's quite popular in the community and uses `electron-builder` internally.

## Ibang mga tools at boilerplates

The ["Awesome Electron" list](https://github.com/sindresorhus/awesome-electron#boilerplates) contains more tools and boilerplates to choose from. If you find the length of the list intimidating, don't forget that adding tools as you go along is a valid approach, too.