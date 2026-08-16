# my last little note for you — setup notes

## One single file
Everything — the design, the writing, and the music — is now built into
`index.html`. There's nothing else to attach, upload, or keep track of.
You can email it, AirDrop it, or host it; it'll work exactly the same.

## Deploying (free, no backend)
**GitHub Pages:**
1. Create a new repo (private is fine).
2. Upload `index.html` to the repo root.
3. Settings → Pages → source: `main` branch, root folder.
4. GitHub gives you a live link in a minute or two — that's what you send her.

**Or with zero setup:**
Drag `index.html` onto netlify.com's deploy drop zone for an instant link,
no account required. Or just send her the file directly — opening it in any
browser (even offline, except for the two Google Fonts it loads) plays the
full experience, music included.

## A couple of things worth knowing
- The file is a bit large (~3.5MB) because the song is embedded directly in
  it — that's normal, and it's what makes it a single portable file.
- The floating ♪ control appears once she presses "open this" and the music
  is confirmed playable — no separate step needed.
- It respects "reduce motion" settings for anyone who has that turned on.
- It's responsive — built and checked for mobile-first, since that's almost
  certainly how she'll open it.
- The "read again" button at the end just scrolls back to the top — nothing
  resets or is lost.
