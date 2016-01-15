# css-display 0.0.7

Css module of single purpose classes for display

#### Stats

512 | 76 | 76
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

   - Mobile First
   - Breakpoint: not-small
   - Breakpoint: medium
   - Breakpoint: large

*/
.dn { display: none; }
.di { display: inline; }
.db { display: block; }
.dib { display: inline-block; }
.dli { display: list-item; }
.dit { display: inline-table; }
.dt { display: table; }
.dtc { display: table-cell; }
.dtcol { display: table-column; }
.dtcolg { display: table-column-group; }
.dtfg { display: table-footer-group; }
.dthg { display: table-header-group; }
.dtr { display: table-row; }
.dtrg { display: table-row-group; }
.df { display: flex; }
.dif { display: inline-flex; }
.dg { display: grid; }
.dig { display: inline-grid; }
.dri { display: run-in; }
@media screen and (min-width: 48em) {
 .dn-ns { display: none; }
 .di-ns { display: inline; }
 .db-ns { display: block; }
 .dib-ns { display: inline-block; }
 .dli-ns { display: list-item; }
 .dit-ns { display: inline-table; }
 .dt-ns { display: table; }
 .dtc-ns { display: table-cell; }
 .dtcol-ns { display: table-column; }
 .dtcolg-ns { display: table-column-group; }
 .dtfg-ns { display: table-footer-group; }
 .dthg-ns { display: table-header-group; }
 .dtr-ns { display: table-row; }
 .dtrg-ns { display: table-row-group; }
 .df-ns { display: flex; }
 .dif-ns { display: inline-flex; }
 .dg-ns { display: grid; }
 .dig-ns { display: inline-grid; }
 .dri-ns { display: run-in; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .dn-m { display: none; }
 .di-m { display: inline; }
 .db-m { display: block; }
 .dib-m { display: inline-block; }
 .dli-m { display: list-item; }
 .dit-m { display: inline-table; }
 .dt-m { display: table; }
 .dtc-m { display: table-cell; }
 .dtcol-m { display: table-column; }
 .dtcolg-m { display: table-column-group; }
 .dtfg-m { display: table-footer-group; }
 .dthg-m { display: table-header-group; }
 .dtr-m { display: table-row; }
 .dtrg-m { display: table-row-group; }
 .df-m { display: flex; }
 .dif-m { display: inline-flex; }
 .dg-m { display: grid; }
 .dig-m { display: inline-grid; }
 .dri-m { display: run-in; }
}
@media screen and (min-width: 64em) {
 .dn-l { display: none; }
 .di-l { display: inline; }
 .db-l { display: block; }
 .dib-l { display: inline-block; }
 .dli-l { display: list-item; }
 .dit-l { display: inline-table; }
 .dt-l { display: table; }
 .dtc-l { display: table-cell; }
 .dtcol-l { display: table-column; }
 .dtcolg-l { display: table-column-group; }
 .dtfg-l { display: table-footer-group; }
 .dthg-l { display: table-header-group; }
 .dtr-l { display: table-row; }
 .dtrg-l { display: table-row-group; }
 .df-l { display: flex; }
 .dif-l { display: inline-flex; }
 .dg-l { display: grid; }
 .dig-l { display: inline-grid; }
 .dri-l { display: run-in; }
}
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

