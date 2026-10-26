# Social Media Preview (Next.js)

A simple Next.js app that embeds the supplied YouTube video and Instagram Reel.

## Requirements
- Node.js 20.9 or later
- Internet connection

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Notes
- YouTube playback is embedded using the YouTube privacy-enhanced player.
- Instagram embeds require Instagram's embed script and may not render for private,
  restricted, or non-embeddable posts. Instagram may require sign-in.
- This app embeds the videos; it does not download or host the media.
