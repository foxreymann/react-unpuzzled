## Tools

### React - View Library

https://facebook.github.io/react

### JSX - JS syntax extension

- right seperation of concerns - presentation & business logic
- JS, HTML and CSS in one file helps to code quicker

### Redux - predictable state container

https://github.com/reactjs/redux  
[Quick into talk](https://vimeo.com/167609765#t=150s)  
[Best full training](https://egghead.io/series/getting-started-with-redux)  

### fetch API with polyfill for IE - API client

https://developer.mozilla.org/en/docs/Web/API/Fetch_API
[polyfill](https://github.com/github/fetch)

### react-router - routing

https://github.com/reactjs/react-router

### react-router-redux - sync react-router with Redux state

https://github.com/reactjs/react-router-redux

### redux-form - complete forms solution

http://redux-form.com  
[pros and cons of redux-form talk](https://www.youtube.com/watch?v=kkqArkYV4fw#t=33m)

### Webpack & CommonJS - Module Bundler, build tool

http://webpack.github.io/docs/what-is-webpack.html

### React Hot Loader

- no page refresh needed after code update!

https://github.com/gaearon/react-hot-loader

### Babel.js - JSX & ES6 transpiler

https://babeljs.io

### ESLint & lint-plugin-react - linting

https://github.com/eslint/eslint  
https://www.npmjs.com/package/eslint-plugin-react

## React Boilerpalte

<img src="https://raw.githubusercontent.com/mxstbr/react-boilerplate-brand/master/assets/banner-metal.jpg" alt="react boilerplate banner" align="center" />

<br />

<div align="center"><strong>Start your next react project in seconds</strong></div>
<div align="center">A highly scalable, offline-first foundation with the best DX and a focus on performance and best practices</div>

<br />

<div align="center">
  <!-- Dependency Status -->
  <a href="https://david-dm.org/mxstbr/react-boilerplate">
    <img src="https://david-dm.org/mxstbr/react-boilerplate.svg" alt="Dependency Status" />
  </a>
  <!-- devDependency Status -->
  <a href="https://david-dm.org/mxstbr/react-boilerplate#info=devDependencies">
    <img src="https://david-dm.org/mxstbr/react-boilerplate/dev-status.svg" alt="devDependency Status" />
  </a>
  <!-- Build Status -->
  <a href="https://travis-ci.org/mxstbr/react-boilerplate">
    <img src="https://travis-ci.org/mxstbr/react-boilerplate.svg" alt="Build Status" />
  </a>
  <!-- Test Coverage -->
  <a href="https://coveralls.io/r/mxstbr/react-boilerplate">
    <img src="https://coveralls.io/repos/github/mxstbr/react-boilerplate/badge.svg" alt="Test Coverage" />
  </a>
</div>
<div align="center">
    <!-- Backers -->
  <a href="#backers">
    <img src="https://opencollective.com/react-boilerplate/backers/badge.svg" alt="Backers" />
  </a>
      <!-- Sponsors -->
  <a href="#sponsors">
    <img src="https://opencollective.com/react-boilerplate/sponsors/badge.svg" alt="Sponsors" />
  </a>
  <!-- Gitter -->
  <a href="https://gitter.im/mxstbr/react-boilerplate">
    <img src="https://camo.githubusercontent.com/54dc79dc7da6b76b17bc8013342da9b4266d993c/68747470733a2f2f6261646765732e6769747465722e696d2f6d78737462722f72656163742d626f696c6572706c6174652e737667" alt="Gitter Chat" />
  </a>
</div>

<br />

<div align="center">
  <sub>Made with ❤︎ by <a href="https://twitter.com/mxstbr">Max Stoiber</a> and <a href="https://github.com/mxstbr/react-boilerplate/graphs/contributors">contributors</a>. <i>If you're using this boilerplate, we'd love to <a href="https://github.com/mxstbr/react-boilerplate/issues/115">hear from you</a>!</i></sub>
</div>

## Features

<dl>
  <dt>Quick scaffolding</dt>
  <dd>Create components, containers, routes, selectors and sagas - and their tests - right from the CLI!</dd>

  <dt>Instant feedback</dt>
  <dd>Enjoy the best DX (Developer eXperience) and code your app at the speed of thought! Your saved changes to the CSS and JS are reflected instantaneously without refreshing the page. Preserve application state even when you update something in the underlying code!</dd>

  <dt>Predictable state management</dt>
  <dd>Unidirectional data flow allows for change logging and time travel debugging.</dd>

  <dt>Next generation JavaScript</dt>
  <dd>Use template strings, object destructuring, arrow functions, JSX syntax and more, today.</dd>

  <dt>Next generation CSS</dt>
  <dd>Write composable CSS that's co-located with your components for complete modularity. Unique generated class names keep the specificity low while eliminating style clashes. Ship only the styles that are on the page for the best performance.</dd>

  <dt>Industry-standard routing</dt>
  <dd>It's natural to want to add pages (e.g. `/about`) to your application, and routing makes this possible.</dd>

  <dt>Offline-first</dt>
  <dd>The next frontier in performant web apps: availability without a network connection from the instant your users load the app.</dd>
</dl>

But wait... there's more!

  - *The best test setup:* Automatically guarantee code quality and non-breaking
    changes. (Seen a react app with 99% test coverage before?)
  - *Native web app:* Your app's new home? The home screen of your users' phones.
  - *The fastest fonts:* Say goodbye to vacant text.
  - *Stay fast*: Profile your app's performance from the comfort of your command
    line!
  - *Catch problems:* AppVeyor and TravisCI setups included by default, so your
    tests get run automatically on Windows and Unix.

There’s also a <a href="https://vimeo.com/168648012">fantastic video</a> on how to structure your React.js apps with scalability in mind. It provides rationale for the majority of boilerplate's design decisions.

<sub><i>Keywords: React.js, Redux, Hot Reloading, ESNext, Babel, PostCSS, Autoprefixer, react-router, Offline First, ServiceWorker, CSS Modules, redux-saga, FontFaceObserver, PageSpeed Insights</i></sub>

## Quick start

1. Clone this repo using `$ git clone --depth=1 https://github.com/mxstbr/react-boilerplate.git`
1. Run `$ npm run setup` to install dependencies and clean the git repo.<br />
   *At this point you can run `$ npm start` to see the example app at `http://localhost:3000`.*
1. Run `$ npm run clean` to delete the example app.

Now you're ready to rumble!

## Documentation

- [Intro](docs/general): What's included and why
- [**Commands**](docs/general/commands.md): Getting the most out of this boilerplate
- [Testing](docs/testing): How to work with the built-in test harness
- [Styling](docs/css): How to work with the CSS tooling
- [Your app](docs/js): Supercharging your app with Routing, Redux, simple
  asynchronicity helpers, etc.

## Supporters

This project would not be possible without the support by these amazing folks. [**Become a sponsor**](https://opencollective.com/react-boilerplate) to get your company in front of thousands of engaged react developers and help us out!

<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/0/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/1/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/2/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/3/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/4/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/5/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/6/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/7/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/8/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/bronze-sponsor/9/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/bronze-sponsor/9/avatar.svg"></a>

----

<a href="https://opencollective.com/react-boilerplate/backer/0/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/1/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/2/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/3/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/4/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/5/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/6/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/7/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/8/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/react-boilerplate/backer/9/website" target="_blank"><img src="https://opencollective.com/react-boilerplate/backer/9/avatar.svg"></a>


## License

This project is licensed under the MIT license, Copyright (c) 2016 Maximilian
Stoiber. For more information see `LICENSE.md`.
