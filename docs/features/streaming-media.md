# Streaming Media

## Override Native Functions

```js
const player = videojs('my-video', {
    html5: {
    // nativeCaptions: false,
    hls: {
        overrideNative: true
    },
    nativeAudioTracks: false,
    nativeVideoTracks: false
}});
```

The `nativeCaptions: false` will disable native caption feature, and this will make the subtitle not work in IOS.

## DVR

[![Demo Image](../assets/screenshot/videojs-live-ui.png)](https://videojs-http-streaming.netlify.app/?debug=false&autoplay=false&muted=false&fluid=false&minified=false&sync-workers=false&liveui=true&llhls=false&url=https%3A%2F%2Flivesim.dashif.org%2Flivesim%2Fmup_30%2Ftestpic_2s%2FManifest.mpd&type=application%2Fdash%2Bxml&keysystems=&buffer-water=false&exact-manifest-timings=false&pixel-diff-selector=false&network-info=false&dts-offset=false&override-native=true&preload=auto&mirror-source=true)

```js
const player = videojs('my-video', {
    liveui: true
});
```
