# angular-lodash-string
Angular Lodash provider with underscore.string filter support

>a combination of the following projects:
https://github.com/epeli/underscore.string/issues/285 
https://github.com/tlvince/angular-underscore-string

Assumes [Underscore.string][] (>= v2.x) and lodash have been added to the global scope.

Examples:

```html
{{ name | s: 'swapCase' }}
{{ separator | s: 'join': ['foo', 'bar'] }}
```

[underscore.string]: http://epeli.github.io/underscore.string/

## Install

```bash
(bower) bower install angular-lodash-string
(npm) npm install angular-lodash-string
```

## Usage

Add `lodash.underscore.string` as a module dependency, e.g.:

```js
angular.module('App', ['lodash.underscore.string']);
```
