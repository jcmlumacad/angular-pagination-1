## Angular Pagination
[![npm version](https://img.shields.io/npm/v/tmj-pagination.svg)](https://www.npmjs.org/package/tmj-pagination)
[![CDN](https://img.shields.io/badge/cdn-rawgit-brightgreen.svg)](https://cdn.rawgit.com/TMJPEngineering/angular-pagination/master/dist/pagination.min.js)

---

## Description

Renders a pagination powered by Bootstrap

## Installation

```
npm install tmj-pagination
```

## Usage

```html
<pagination
    [limit="{number}"]
    [route="{string}"]
    [values="{string}"]>
</pagination>
```

**Note: This route supports laravel pagination. Refer to this [link](https://laravel.com/docs/5.2/pagination#paginating-eloquent-results).**

## Parameters

| **Name** | **Type** | **Description**                      | **Default** |
|----------|----------|--------------------------------------|-------------|
| *limit*  | *number* | Set the data limit for every request |     15      |
| *route*  | *string* | Set the url to be called             |      -      |
| *values* | *string* | Set variable name to be save         |      -      |

## Credits

- [John Papa Angular Style Guide](https://github.com/johnpapa/angular-styleguide)
- [TMJP Engineering](https://github.com/TMJPEngineering)

## License

Copyright (c) 2017 [TMJ](http://www.tmj.jp/en/) Philippines
