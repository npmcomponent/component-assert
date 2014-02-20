*This repository is a mirror of the [component](http://component.io) module [component/assert](http://github.com/component/assert). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-assert`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# assert

  C-style assertion lib.

## Example

  With custom assertion message:

```js
var assert = require('assert');
assert(expr, 'oh no it broke');
```

  Or auto-generated assertion message in
  browsers that support `Error.captureStackTrace()`:

```js
var assert = require('assert');
assert(user.name == 'Tobi');
```

## License

  MIT