## Getting Started

With [Node.js](http://nodejs.org) and npm installed, run:

```sh
$ npm run deps
```

### Serve / watch

```sh
$ gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

### Run tests

```sh
$ gulp test:local
```

This runs the unit tests defined in the `app/test` directory through [web-component-tester](https://github.com/Polymer/web-component-tester).

### Build & Vulcanize

```sh
$ gulp
```

Build and optimize the current project, ready for deployment. This includes linting as well as vulcanization, image, script, stylesheet and HTML optimization and minification.


### Deploy

```sh
$ gulp deploy
```
Deploy site into https://github.com/GDG-Ukraine/devfest.gdg.org.ua

## Application Theming

Polymer 1.0 introduces a shim for CSS custom properties. We take advantage of this in `app/elements/app-theme.html` to provide theming for your application. You can also find our presets for Material Design breakpoints in this file.

## Unit Testing

Web apps built with Polymer Starter Kit come configured with support for [Web Component Tester](https://github.com/Polymer/web-component-tester) - Polymer's preferred tool for authoring and running unit tests. This makes testing your element based applications a pleasant experience.

## Dependency Management

Polymer uses [Bower](http://bower.io) for package management. This makes it easy to keep your elements up to date and versioned. For tooling, we use NPM to manage Node-based dependencies.

## Service Worker

Polymer Starter Kit offers an offline-first experience thanks to Service Worker and the [Platinum Service Worker elements](https://github.com/PolymerElements/platinum-sw). New to Service Worker? Read the following [introduction](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) to understand how it works.

Our default offline setup should work well for relatively simple applications. For more complex apps, we recommend learning how Service Worker works so that you can make the most of the Platinum Service Worker element abstractions.
