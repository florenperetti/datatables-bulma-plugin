# DataTables for jQuery with styling for [Bulma](http://bulma.io/)

This package contains distribution files required to style [DataTables library](https://datatables.net) for [jQuery](http://jquery.com/) with styling for [Bulma](http://bulma.io/).

DataTables is a table enhancing library which adds features such as paging, ordering, search, scrolling and many more to a static HTML page. A comprehensive API is also available that can be used to manipulate the table. Please refer to the [DataTables web-site](//datatables.net) for a full range of documentation and examples.


## Installation

### npm

```
npm install datatables.net-bulma
```

```
var $ = require( 'jquery' );
require( 'datatables.net-bulma' )( window, $ );
```

### Styles

You should import on your styles the .css file in order to visualize everything correctly.

Example on a .sass file:
```
@import "~datatables.net-bulma/css/dataTables.bulma.css";
```

## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.

*Note:* This code is highly based on the [Bootstrap integration](https://github.com/DataTables/Dist-DataTables-Bootstrap) for Datatables.