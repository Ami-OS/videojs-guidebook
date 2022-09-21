# Options

You can set the option on player init:

```js
const examplePlayer = videojs('id', {
    customOptions: 'value'
})
```

And access:

```js
examplePlayer.options().customOptions
```

Or:

```js
examplePlayer.options_.customOptions
```

## Options on plugins

You can pass the options will the `plugins` scope:

```js
const examplePlayer = videojs('id', {
    plugins: {
        myPlugin: {
            customOptions: 'value'
        }
    }
})
```

The `myPlugin` must is the same as the plugin name. Because it will load the plugin at the same time.

It is equivalent to:

```js
examplePlayer.myPlugin({
    customOptions: 'value'
})
```
