# CSS DISPLAY

  Mobile-first classes for css-display.
  Set the desired css-display on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-display
```
or download the css on github and include in your project.

## File Size


## The Code
```
.dn {     display: none; }
.di {     display: inline; }
.db {     display: block; }
.dib {    display: inline-block; }
.dli {    display: list-item; }
.dit {    display: inline-table; }
.dt {     display: table; }
.dtc {    display: table-cell; }
.dtcol {  display: table-column; }
.dtcolg { display: table-column-group; }
.dtfg {   display: table-footer-group; }
.dthg {   display: table-header-group; }
.dtr {    display: table-row; }
.dtrg {   display: table-row-group; }
.df {     display: flex; }
.dif {    display: inline-flex; }
.dg {     display: grid; }
.dig {    display: inline-grid; }
.dri {    display: run-in; }

@include break(not-small) {
  .dn-ns {     display: none; }
  .di-ns {     display: inline; }
  .db-ns {     display: block; }
  .dib-ns {    display: inline-block; }
  .dli-ns {    display: list-item; }
  .dit-ns {    display: inline-table; }
  .dt-ns {     display: table; }
  .dtc-ns {    display: table-cell; }
  .dtcol-ns {  display: table-column; }
  .dtcolg-ns { display: table-column-group; }
  .dtfg-ns {   display: table-footer-group; }
  .dthg-ns {   display: table-header-group; }
  .dtr-ns {    display: table-row; }
  .dtrg-ns {   display: table-row-group; }
  .df-ns {     display: flex; }
  .dif-ns {    display: inline-flex; }
  .dg-ns {     display: grid; }
  .dig-ns {    display: inline-grid; }
  .dri-ns {    display: run-in; }
}

@include break(medium) {
  .dn-m {     display: none; }
  .di-m {     display: inline; }
  .db-m {     display: block; }
  .dib-m {    display: inline-block; }
  .dli-m {    display: list-item; }
  .dit-m {    display: inline-table; }
  .dt-m {     display: table; }
  .dtc-m {    display: table-cell; }
  .dtcol-m {  display: table-column; }
  .dtcolg-m { display: table-column-group; }
  .dtfg-m {   display: table-footer-group; }
  .dthg-m {   display: table-header-group; }
  .dtr-m {    display: table-row; }
  .dtrg-m {   display: table-row-group; }
  .df-m {     display: flex; }
  .dif-m {    display: inline-flex; }
  .dg-m {     display: grid; }
  .dig-m {    display: inline-grid; }
  .dri-m {    display: run-in; }
}

@include break(large) {
  .dn-l {     display: none; }
  .di-l {     display: inline; }
  .db-l {     display: block; }
  .dib-l {    display: inline-block; }
  .dli-l {    display: list-item; }
  .dit-l {    display: inline-table; }
  .dt-l {     display: table; }
  .dtc-l {    display: table-cell; }
  .dtcol-l {  display: table-column; }
  .dtcolg-l { display: table-column-group; }
  .dtfg-l {   display: table-footer-group; }
  .dthg-l {   display: table-header-group; }
  .dtr-l {    display: table-row; }
  .dtrg-l {   display: table-row-group; }
  .df-l {     display: flex; }
  .dif-l {    display: inline-flex; }
  .dg-l {     display: grid; }
  .dig-l {    display: inline-grid; }
  .dri-l {    display: run-in; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

