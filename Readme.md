*This repository is a mirror of the [component](http://component.io) module [yields/to-element](http://github.com/yields/to-element). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-to-element`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# to-element

  get a `Node` from `value`.

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/to-element

## Example

```js
toElement(document.body);
toElement(dom('.baz'));
toElement($('.baz'));
toElement({ el: query('.baz') });
toElement('<div class=baz>');
toElement('.baz');
```

## API

#### toElement(value)

  get a `Node` from `value`.

## License

  MIT
