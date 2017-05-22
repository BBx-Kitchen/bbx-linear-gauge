[![project status](http://www.repostatus.org/badges/latest/active.svg)](http://www.gitchecker.com/BBx-Kitchen/bbx-linear-gauge)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/BBx-Kitchen/bbx-linear-gauge)

# BBX Linear-gauge

Simple Polymer element to create linear gauge

_[Demo and API docs](https://bbx-kitchen.github.io/bbx-linear-gauge/components/bbx-linear-gauge/)_


## How to install

`bower install --save BBx-Kitchen/bbx-linear-gauge`

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bbx-linear-gauge.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

## Usage

```html
<h3>Horizontal Gauge - Top</h3>
<bbx-linear-gauge min="0" max="100" value="50" position="top" gradients='[[0,"#A770EF"],[50,"#CF8BF3"],[100,"#FDB99B"]]'>
</bbx-linear-gauge>

<h3>Horizontal Gauge - Bottom</h3>
<bbx-linear-gauge min="0" max="100" value="50" position="bottom" gradients='[[0,"#A770EF"],[50,"#CF8BF3"],[100,"#FDB99B"]]'>
</bbx-linear-gauge>
```



## Viewing Element

```
$ polymer serve --open
```

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to start up a local server where you can view documentation & demos for `bbx-linear-gauge`


## Running Tests

```
$ polymer test
```

`bbx-linear-gauge` is set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run the test suite locally.

## Contributing

Everyone is welcome to help contribute and improve this element. There are several
ways you can contribute:

* Reporting issues (please read [issue guidelines](https://github.com/necolas/issue-guidelines))
* Suggesting new features
* Writing or refactoring code
* Fixing [issues](https://github.com/BBx-Kitchen/bbx-linear-gauge/issues)
