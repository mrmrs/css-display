# css-display 2.0.1

Css module of single purpose classes for display

#### Stats

371 | 30 | 30
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-display
```

#### With Git

```
git clone https://github.com/tachyons-css/css-display
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-display";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-display">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   DISPLAY

   https://developer.mozilla.org/en-US/docs/Web/CSS/display

*/
.display-none { display: none; }
.display-inline { display: inline; }
.display-block { display: block; }
.display-inline-block { display: inline-block; }
.display-contents { display: contents; }
.display-list-item { display: list-item; }
.display-inline-list-item { display: inline-list-item; }
.display-table { display: table; }
.display-inline-table { display: inline-table; }
.display-table-cell { display: table-cell; }
.display-table-column { display: table-column; }
.display-table-column-group { display: table-column-group; }
.display-table-footer-group { display: table-footer-group; }
.display-table-header-group { display: table-header-group; }
.display-table-row { display: table-row; }
.display-table-row-group { display: table-row-group; }
.display-table-caption { display: table-caption; }
.display-flex { display: flex; }
.display-inline-flex { display: inline-flex; }
.display-grid { display: grid; }
.display-inline-grid { display: inline-grid; }
.display-ruby { display: ruby; }
.display-ruby-base { display: ruby-base; }
.display-ruby-text { display: ruby-text; }
.display-ruby-base-container { display: ruby-base-container; }
.display-ruby-text-container { display: ruby-text-container; }
.display-run-in { display: run-in; }
/* Global values */
.display-inherit { display: inherit; }
.display-initial { display: initial; }
.display-unset { display: unset; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

