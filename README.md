# css-display 2.0.3

Css module of single purpose classes for display

#### Stats

404 | 30 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-display
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-display
```

ssh:
```
git clone git@github.com:tachyons-css/css-display.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-display";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-display@2.0.3/css/css-display.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-display">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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
.display-flex { display: -webkit-box; display: -ms-flexbox; display: flex; }
.display-inline-flex { display: -webkit-inline-box; display: -ms-inline-flexbox; display: inline-flex; }
.display-grid { display: -ms-grid; display: grid; }
.display-inline-grid { display: -ms-inline-grid; display: inline-grid; }
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

ISC

