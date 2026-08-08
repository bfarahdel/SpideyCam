# SpideyCam

An AR app that turns your hand into Spider-Man's web shooter.

## Running the App

The app is hosted via GitHub Pages:

**<https://bfarahdel.github.io/SpideyCam/>**

## Instructions

1. Allow camera access when prompted.
2. Show your hand to the camera.
3. Make the web shooting hand gesture to fire a web.
4. **Wipe** a stuck web by waving your hand quickly through it.

| Platform  | Camera        | View     |
| --------- | ------------- | -------- |
| Desktop   | Front    | Mirrored (selfie) |
| Mobile    | Rear | True orientation  |

## Browser Support

Requires a modern browser with:

- ES modules (the app imports MediaPipe from a CDN)
- `getUserMedia` + camera access
- WebGL (for MediaPipe GPU inference)

Works best in recent versions of Chrome/Edge/Firefox on desktop and mobile.
