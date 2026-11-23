# Birthday for Adem

An intimate, single-page birthday story built with React, Vite, TypeScript, Framer Motion, and Lucide React.

## Assets

The supplied `assets/image.jpeg` and `assets/voice.ogg` files are bundled directly by Vite. To use the requested names, you can replace those files or update the imports in `src/App.tsx`. Optional background music should be placed at `public/assets/music.mp3`; the experience works without it.

## Run

```bash
npm install
npm run dev
npm run build
```

Music is optional and may be omitted. Add it as `public/assets/song.mp3`. The opening button is the user gesture that unlocks audio playback in mobile browsers. The voice message controls show the real duration, seek position, play/pause state, and only open the final surprise after the recording's `ended` event.
