# @turf/boolean-is-concave

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## booleanIsConcave

Takes a polygon and return true or false as to whether it is concave or not.

**Parameters**

-   `polygon` **[Feature](https://tools.ietf.org/html/rfc7946#section-3.2)&lt;[Polygon](https://tools.ietf.org/html/rfc7946#section-3.1.6)>** to be evaluated

**Examples**

```javascript
var convexPolygon = turf.polygon([[[0,0],[0,1],[1,1],[1,0],[0,0]]]);

turf.booleanIsConcave(convexPolygon)
//=false
```

Returns **[boolean](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** true/false

<!-- This file is automatically generated. Please don't edit it directly:
if you find an error, edit the source file (likely index.js), and re-run
./scripts/generate-readmes in the turf project. -->

---

This module is part of the [Turfjs project](http://turfjs.org/), an open source
module collection dedicated to geographic algorithms. It is maintained in the
[Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create
PRs and issues.

### Installation

Install this module individually:

```sh
$ npm install @turf/boolean-is-concave
```

Or install the Turf module that includes it as a function:

```sh
$ npm install @turf/turf
```