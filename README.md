# `<cloudflare-video>` 

[![Version](https://img.shields.io/npm/v/cloudflare-video-element?style=flat-square)](https://www.npmjs.com/package/cloudflare-video-element) 
[![Badge size](https://img.badgesize.io/https://cdn.jsdelivr.net/npm/cloudflare-video-element/+esm?compression=gzip&label=gzip&style=flat-square)](https://cdn.jsdelivr.net/npm/cloudflare-video-element/+esm)

A [custom element](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements) 
for the Cloudflare player with an API that matches the 
[`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) API.

- 🏄‍♂️ Compatible [`HTMLMediaElement`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement) API
- 🕺 Seamlessly integrates with [Media Chrome](https://github.com/muxinc/media-chrome)


## Example 

<!-- prettier-ignore -->
```html
<script type="module" src="https://cdn.jsdelivr.net/npm/cloudflare-video-element@1.0/+esm"></script>
<cloudflare-video controls src="https://watch.videodelivery.net/bfbd585059e33391d67b0f1d15fe6ea4"></cloudflare-video>
```

## Installing

First install the NPM package:

```bash
npm install cloudflare-video-element
```

Import in your app javascript (e.g. src/App.js):

```js
import 'cloudflare-video-element';
```

Optionally, you can load the script directly from a CDN using [jsDelivr](https://www.jsdelivr.com/):

<!-- prettier-ignore -->
```html
<script type="module" src="https://cdn.jsdelivr.net/npm/cloudflare-video-element@1.0/+esm"></script>
```

This will register the custom elements with the browser so they can be used as HTML.

## Related

- [Media Chrome](https://github.com/muxinc/media-chrome) Your media player's dancing suit. 🕺
- [`<youtube-video>`](https://github.com/muxinc/youtube-video-element) A custom element for the YouTube player.
- [`<vimeo-video>`](https://github.com/luwes/vimeo-video-element) A custom element for the Vimeo player.
- [`<jwplayer-video>`](https://github.com/luwes/jwplayer-video-element) A custom element for the JW player.
- [`<wistia-video>`](https://github.com/luwes/wistia-video-element) A custom element for the Wistia player.
- [`<videojs-video>`](https://github.com/luwes/videojs-video-element) A custom element for Video.js.
- [`<hls-video>`](https://github.com/muxinc/hls-video-element) A custom element for playing HTTP Live Streaming (HLS) videos.
- [`castable-video`](https://github.com/muxinc/castable-video) Cast your video element to the big screen with ease!
- [`<mux-player>`](https://github.com/muxinc/elements/tree/main/packages/mux-player) The official Mux-flavored video player custom element.
- [`<mux-video>`](https://github.com/muxinc/elements/tree/main/packages/mux-video) A Mux-flavored HTML5 video element w/ hls.js and Mux data builtin.
