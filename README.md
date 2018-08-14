[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vaadin/foo-element)
[![Build Status](https://travis-ci.org/vaadin/foo-element.svg?branch=master)](https://travis-ci.org/vaadin/foo-element)
[![Coverage Status](https://coveralls.io/repos/github/vaadin/foo-element/badge.svg?branch=master)](https://coveralls.io/github/vaadin/foo-element?branch=master)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

 [![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinfoo-element)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/foo-element-directory-urlidentifier.svg)](https://vaadin.com/directory/component/vaadinfoo-element)




# &lt;foo-element&gt;

[Live Demo ↗](https://vaadin.com/components/foo-element/html-examples)
|
[API documentation ↗](https://vaadin.com/components/foo-element/html-api)


[&lt;foo-element&gt;](https://vaadin.com/components/foo-element) is a Web Component providing &lt;element-functionality&gt;, part of the [Vaadin components](https://vaadin.com/components).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="foo-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<foo-element>
  ...
</foo-element>
```

[<img src="https://raw.githubusercontent.com/vaadin/foo-element/master/screenshot.png" width="200" alt="Screenshot of foo-element">](https://vaadin.com/components/foo-element)


## Installation

The Vaadin components are distributed as Bower and npm packages.
Please note that the version range is the same, as the API has not changed.
You should not mix Bower and npm versions in the same application, though.

Unlike the official Polymer Elements, the converted Polymer 3 compatible Vaadin components
are only published on npm, not pushed to GitHub repositories.

### Polymer 2 and HTML Imports compatible version

Install `foo-element`:

```sh
bower i vaadin/foo-element --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/vaadin-button/vaadin-button.html">
```
### Polymer 3 and ES Modules compatible version


Install `foo-element`:

```sh
npm i @vaadin/foo-element --save
```

Once installed, import it in your application:

```js
import '@vaadin/foo-element/foo-element.js';
```

## Getting started

Vaadin components use the Lumo theme by default.

To use the Material theme, import the correspondent file from the `theme/material` folder.

## Entry points

- The component with the Lumo theme:

  `theme/lumo/component-name.html`

- The component with the Material theme:

  `theme/material/component-name.html`

- Alias for `theme/lumo/component-name.html`:

  `component-name.html`


## Running demos and tests in browser

1. Fork the `foo-element` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `foo-element` directory, run `npm install` and then `bower install` to install dependencies.

1. Make sure you have [polymer-cli](https://www.npmjs.com/package/polymer-cli) installed globally: `npm i -g polymer-cli`.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/foo-element/demo
  - http://127.0.0.1:8080/components/foo-element/test


## Running tests from the command line

1. When in the `foo-element` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  To contribute to the component, please read [the guideline](https://github.com/vaadin/vaadin-core/blob/master/CONTRIBUTING.md) first.


## License

Apache License 2.0

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
