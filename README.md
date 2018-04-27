# jsonify
Convert Javascript Object literals to JSON

Single quotes?
Unquoted properties?
Trailing commas?
Comments?

Just turn this:
```js
/* Hi */
{
  foo: 'bar', //see
  'hello': `world`, //trailing comma?
}
```

Into this:
```json
{
    "foo": "bar",
    "hello": "world"
}
```

-----------

<h1><a href="https://victornpb.github.io/jsonify/">https://victornpb.github.io/jsonify/</a></h1>

-----------
