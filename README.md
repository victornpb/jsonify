# jsonify
Convert Javascript Object literals to JSON

Single quotes?
Unquoted properties?
Trailing commas?
Comments?

Just turn this:
```js
/* Javascript object */
{
  foo: 'bar', // comment
  'hello': `world`, // trailing comma?
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

<h1 style="text-align:center;"><a href="https://victornpb.github.io/jsonify/">https://victornpb.github.io/jsonify/</a></h1>

-----------
