# Subtitles

## Save subtitle settings

By default, subtitle settings are not saved, so if you reload the page, all settings will reset to default.

Using the `persistTextTrackSettings` option to control it:

```js
const examplePlayer = videojs('id', {
    persistTextTrackSettings: true,
});
```
