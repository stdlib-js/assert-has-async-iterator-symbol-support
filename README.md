<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Async Iterator Symbol Support

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Detect native [`Symbol.asyncIterator`][mdn-symbol] support.



<section class="usage">

## Usage

<!-- eslint-disable id-length -->

```javascript
import hasAsyncIteratorSymbolSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-async-iterator-symbol-support@deno/mod.js';
```

#### hasAsyncIteratorSymbolSupport()

Detects if a runtime environment supports ES2018 [`Symbol.asyncIterator`][mdn-symbol].

<!-- eslint-disable id-length -->

```javascript
var bool = hasAsyncIteratorSymbolSupport();
// returns <boolean>
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint-disable id-length -->

<!-- eslint no-undef: "error" -->

```javascript
import hasAsyncIteratorSymbolSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-async-iterator-symbol-support@deno/mod.js';

var bool = hasAsyncIteratorSymbolSupport();
if ( bool ) {
    console.log( 'Environment has Symbol.asyncIterator support.' );
} else {
    console.log( 'Environment lacks Symbol.asyncIterator support.' );
}
```

</section>

<!-- /.examples -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/assert/has-iterator-symbol-support`][@stdlib/assert/has-iterator-symbol-support]</span><span class="delimiter">: </span><span class="description">detect native Symbol.iterator support.</span>
-   <span class="package-name">[`@stdlib/assert/has-symbol-support`][@stdlib/assert/has-symbol-support]</span><span class="delimiter">: </span><span class="description">detect native Symbol support.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-has-async-iterator-symbol-support.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-has-async-iterator-symbol-support

[test-image]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-has-async-iterator-symbol-support/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-has-async-iterator-symbol-support?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-has-async-iterator-symbol-support.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-has-async-iterator-symbol-support/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-has-async-iterator-symbol-support/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-has-async-iterator-symbol-support/main/LICENSE

[mdn-symbol]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol

<!-- <related-links> -->

[@stdlib/assert/has-iterator-symbol-support]: https://github.com/stdlib-js/assert-has-iterator-symbol-support/tree/deno

[@stdlib/assert/has-symbol-support]: https://github.com/stdlib-js/assert-has-symbol-support/tree/deno

<!-- </related-links> -->

</section>

<!-- /.links -->
