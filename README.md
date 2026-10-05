# Turntable

A Spotify-connected turntable. The record spins while you listen, swaps when the song changes, and the background follows the album colors. Add notes, framed images, clocks and a little character to the page.

## Run it

Serve the folder over HTTP (Spotify needs a real address):

```
python -m http.server 8000
```

Open `http://127.0.0.1:8000/`.

## GitHub Pages

1. Push this folder to a repository.
2. Settings → Pages → deploy from the `main` branch, root folder.
3. Use the Pages address (e.g. `https://you.github.io/turntable/`) as the redirect URI.

## Connect Spotify

1. Create an app at https://developer.spotify.com/dashboard and select Web API.
2. Add the redirect URI shown on the page (the exact page address).
3. Paste the app's Client ID into the page and connect.

Apps in development mode only work for accounts added under User Management.

## Files

- `index.html` — the whole app
- `assets/buddy/` — character animations (idle, walk, dance, jump, sit, hang)
 