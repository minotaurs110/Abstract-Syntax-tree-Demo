# abstract-syntax-tree changelog

## 2.20.5

* edit: update dependencies

## 2.20.4

* edit: update dependencies

## 2.20.3

* edit: replace nyc with c8 (coverage)

## 2.20.2

* edit: update meriyah and path-parse

## 2.20.1

* add: pass parent node to the remove callback

## 2.20.0

* add: bring back esquery for better selector matching
* remove: rollup and client-side bundle

## 2.19.1

* add: ArrowFunctionExpression to types.json

## 2.19.0

* remove: esquery dependency (to simplify client-side bundling)

## 2.18.1

* edit: update dependencies

## 2.18.0

* edit: update required node to 14.0.0
* edit: improve logicalExpressionReduction

## 2.17.6

* edit: improve shorthand syntax for Literals

## 2.17.5

* add: support shorthand syntax for CallExpressions

## 2.17.4

* add: support shorthand syntax for Identifiers, Literals and ArrayExpressions

## 2.17.3

* edit: support array of nodes in the toBinaryExpression method
* edit: update dependencies

## 2.17.2

* edit: update rollup

## 2.17.1

* edit: update dependencies

## 2.17.0

* edit: update dependencies

## 2.16.0

* edit: update dependencies

## 2.15.3

* edit: downgrade required node to 12.20.1

## 2.15.2

* edit: update dependencies

## 2.15.1

* add: iife method (static)

## 2.15.0

* add: program method (static)
* remove: asttv dependency, inline code in the serialize method
* remove: estemplate dependency, inline code to support/import export and remove esprima dependency

## 2.14.0

* add: support dynamic imports in the generate method

## 2.13.0

* remove: to-ast dependency
* add: backfill code of the to-ast dependency inside of the template method
* add: possibility to use the library in the browser

## 2.12.0

* edit: update dependencies

## 2.11.0

* edit: improve binaryExpressionReduction

## 2.10.1

* edit: expose optimizations method directly

## 2.10.0

* add: new toBinaryExpression method

## 2.9.5

* add: new match method

## 2.8.1

* edit: fix README

## 2.8.0

* edit: add optimization techniques

## 2.5.0

* edit: change cherow to meriyah

## 2.3.0

* edit: append and prepend mutate existing arrays

## 2.2.0

* add: possibility to create a new abstract syntax tree instance without params
* add: append and prepend accept string as input
* update: ava

## 2.1.3

* edit: update nyc

## 2.1.2

* add: reduce method

## 2.1.1

* edit: update deps

## 2.1.0

* add: support object selector in the find, has and count methods
* edit: better performance for the remove method (string selector)
* remove: obsolete config.js file

## 2.0.1

* edit: remove nodes only if null is returned in the replace method

## 2.0.0

* add: static methods: find, each, first, last, count, has, remove, equal and traverse
* add: getters -> type, body, source and map
* edit: replace method now accepts options object instead of a callback
* edit: removed the `is` method, please use static `equal` method instead
* edit: ast property has been replaced with _tree
* remove: `minify` and `beautify` methods
* remove: `toSource`, `toSourceMap` and `toString` methods

## 1.1.2

* edit: add src dir to files in package.json

## 1.1.1

* edit: move prettier to deps

## 1.1.0

* add: update replace method to handle array and null value

## 1.0.3

* edit: update cherow to 1.6.8

## 0.11.0

* edit: replace escodegen with astring
* edit: pass npm audit

## 0.10.2

* add: static replace method

## 0.10.1

* add: body method, as a shortcut for accessing tree.ast.body

## 0.10.0

* edit: change espree to cherow
* remove: comments support
* remove: drop node 4.0.0 support (LTS end of life)

## 0.9.6

* add: static generate method

## 0.9.5

* add: basic jsx support

## 0.9.4
* add: support node >= 4.0.0 ([#40](https://github.com/buxlabs/abstract-syntax-tree/pull/40/files))

## 0.9.3
* add: mark method
* add: tests that show how to calculate binary expressions or drop if statements

## 0.9.2
* add: accept ast as a param of the constructor

## 0.9.1
* add: static walk method

## 0.9.0
* add: toSourceMap method
* edit: toSource accepts a sourceMap/sourceFile/sourceRoot options
* edit: expose removeByNode and removeBySelector as public methods

## 0.8.2
* add: docs, tests

## 0.8.1
* add: docs

## 0.8.0
* remove: astq

## 0.7.1
* add: browserified version in the build dir

## 0.7.0
* edit: replace js-beautify with prettier

## 0.6.0
* add: support astq query engine for find and query methods

## 0.5.0
* add: walk and traverse methods

## 0.4.3
* add: each and toString methods

## 0.4.2
* add: count method

## 0.4.1
* add: handle string selector in the remove method

## 0.4.0
* edit: switch from acorn to espree
* add: better comments support

## 0.3.5
* add: source field

## 0.3.4
* add: template method

## 0.3.3
* add: unwrap method (e.g. drop iife)

## 0.3.2
* add: is method (you can compare nodes loosely)

## 0.3.1
* add: wrap method (you can wrap the code, e.g. with iife or amd)
* add: minify method (noop, override it to provide extra functionality)

## 0.3.0
* add: beautify method to the class
