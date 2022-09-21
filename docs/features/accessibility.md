# Accessibility

## Disable title attr on UI

By default, when you hover to the UI, that will show a browser level tooltip:

![UI title attributes](../assets/screenshot/ui-title-attributes.jpg)

You can using `noUITitleAttributes` option to control it:

```js
const examplePlayer = videojs('id', {
    noUITitleAttributes: true
})
```
