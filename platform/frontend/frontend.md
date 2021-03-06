# Front-end

1. [Technologies](#technologies)
1. [Development OS](#development-os)
1. [IDE](#ide)
1. [Coding Conventions](#coding-conventions)
1. [Test-Driven Development](#test-driven-development)
1. [Preferred Libraries](#preferred-libraries)
1. [Best Practices](#best-practices)
1. [Design And Markup](#design-and-markup)
1. [Search Engine Optimization](#search-engine-optimization)
1. [Google Analytics & other third-party services](#google-analytics--other-third-party-services)
1. [Useful Links](#useful-links)


## Technologies

* [Node.js](https://nodejs.org/en) v6.x.x (LTS)
* [npm](https://www.npmjs.com) package manager for Node.js _(deprecated; using in support projects)_
* [yarn](https://yarnpkg.com/) package manager for Node.js
* [bower](http://bower.io) package manager for web development _(deprecated; using in support projects)_
* [AngularJS](https://angularjs.org) 1.5.х as main framework _(deprecated; using in support projects)_
* [Angular](https://angular.io/) 5.x.x as main framework
* [Pug](https://pugjs.org) - HTML template engine
* [Stylus](http://stylus-lang.com/) - CSS preprocessor
* [Gulp](http://gulpjs.com) - streaming build system _(deprecated; using in support projects)_
* [Webpack](https://webpack.js.org/) 2.x.x - JavaScript module bundler
* [Babel](https://babeljs.io/) - JavaScript compiler
* [TypeScript](https://www.typescriptlang.org/) 2.x.x - optional types, classes, and modules to JavaScript


## Development OS

We don’t use Windows as OS for development machines. We use latest Mac OS X or Ubuntu/Debian (long-term support releases are preferred).


## IDE

* [WebStorm](https://www.jetbrains.com/webstorm) (not required)


## Coding Conventions

* [JavaScript Style Guide](https://github.com/airbnb/javascript)
* [Angular 1.x style guide](https://github.com/rwwagner90/angular-styleguide-es6) (good [article](https://www.sitepoint.com/writing-angularjs-apps-using-es6/))
* [Angular 5.x style guide](https://angular.io/docs/ts/latest/guide/style-guide.html)
* [Stylus style guide](https://github.com/skyout/stylus-styleguide)


## Unit testing

Use these frameworks:
* [Karma](http://karma-runner.github.io)
* [Jasmine](http://jasmine.github.io)


## Preferred Libraries

* [EventEmitter](https://github.com/Olical/EventEmitter)
* [Underscore](http://underscorejs.org) / [lodash](https://lodash.com)
* [ui-router](https://ui-router.github.io/ng1/) 1.x - routing in AngularJS
* [ng-file-upload](https://github.com/danialfarid/ng-file-upload) 12.x.x - Angular directive to upload files


## Best Practices

* Keep in mind that desktop web site is not a mobile app
* Keep in mind [300 milliseconds `onClick` delay](http://www.sitepoint.com/5-ways-prevent-300ms-click-delay-mobile-devices) in mobile devices' browsers


## Design And Markup

__Web sites that we develop should be *responsive and adaptive* by default.__

Screen sizes:
* Desktop min size: 1024x768
* Mobile min size: 320x480

We support these web browsers:
* Internet Explorer 11
* Edge 16
* Firefox 59
* Chrome 64, 65, 66
* Chrome for Android 66
* Desktop Safari 11, 11.1
* Mobile Safari 10.3, 11.2, 11.3
* Opera 52
* Android Browser 4.4
* Samsung Internet 6.2
* UC Browser for Android 11.8


## Search Engine Optimization

_This section is not finished yet._

* Properly setup `robots.txt` file. See [robotstxt.org](http://www.robotstxt.org)
* Generate `sitemap.xml` file. See [sitemaps.org](https://www.sitemaps.org)
* Use [prerender.io](https://prerender.io)
* Use tags: `h1...h6`, `p`, `meta`, `title` etc.


## Google Analytics & other third-party services

Create separate third-party service ID constant for each environment (development, staging, production).
Keep constants files out of repository.

Google Analytics:
* Test account - dev@mlsdev.com _(see on MLSDev Articles / Accounts)_ - create app google analytics for staging and development servers.
* Production account is to be provided/created by/for client


## Useful links

* [Frontend Dev Bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) - a _LOT_ of useful links
* [Material Design Icons](https://materialdesignicons.com)
* [AngularJS API Reference](https://docs.angularjs.org/api)
* [W3C](http://w3.org)
* [ngmodules.org](http://ngmodules.org) - find modules for AngularJS
* [The Twelve-Factor App](http://12factor.net/)
