# Thornlight

A gothic botanical skin for the [Video.js v10](https://videojs.org/) player, made for the Video.js Skins Design Challenge.

**Live demo:** https://rkabota.github.io/thornlight/

## The design

Thornlight grew out of Dark Bloom, a gothic botanical clothing label: roses, thorns and candlelight in a deep red palette.

- **The vine:** the timeline is a stem with thorns that turn crimson as it fills.
- **The rose:** the playhead is a rose that opens wider while you scrub.
- **The reliquary:** controls sit in a black-glass plate with a crimson hairline, so icons and digits stay readable over bright and dark footage.
- **The rose window:** the big play button is a gothic rosette that slowly turns and doubles as the loading spinner.

## Usability and accessibility

- Play/pause, ±10 s seek, timeline, current time and duration, mute and volume, playback rate, captions, picture-in-picture and fullscreen.
- Every control is reachable with Tab and shows a bone-and-crimson focus ring. Hotkeys: Space/K play, ←/→ seek 5 s, J/L 10 s, ↑/↓ volume, M mute, F fullscreen, C captions, 0–9 jump.
- Controls are at least 44 px. Container queries drop secondary buttons on narrow players.
- With reduced motion on, rotation, pulsing and fades are turned off. Forced-colors mode is supported.

## Build

The skin is plain HTML custom elements from `@videojs/html` plus one stylesheet (`src/thornlight.css`). The `source/` folder holds the unbuilt files.

```
npm install
npx vite build
```

## License

Apache License 2.0.
