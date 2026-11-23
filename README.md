# Birthday for Adem

An intimate, single-page birthday story built with React, Vite, TypeScript, Framer Motion, and Lucide React.

## Assets

The supplied `assets/image.jpeg`, `assets/voice.ogg`, and `assets/Richy Mitch & The Coal Miners - Evergreen (Lyrics).mp3` files are bundled directly by Vite. The experience works without the optional song if you remove its import from `src/App.tsx`.

## Run

```bash
npm install
npm run dev
npm run build
```

Music is optional and may be omitted. The opening button is the user gesture that unlocks audio playback in mobile browsers. The voice message controls show the real duration, seek position, play/pause state, and only open the final surprise after the recording's `ended` event.
