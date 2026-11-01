# Decades Mood Mixer

A fun mood-based picker for songs from the 60s, 70s, 80s and 90s — with a strong dose of Aussie classics. No accounts, no backend: ratings and your group live on your own phone.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app (catalogue, styles and code in one file) |
| `manifest.webmanifest` | Lets iPhone/Android install it like an app |
| `sw.js` | Offline support |
| `icon.svg`, `icon-180.png`, `icon-512.png` | App icons |

## Put it on GitHub Pages

1. On github.com, click **+ → New repository**. Name it `decades-mood-mixer`, set it to **Public**, and create it.
2. On the new repo page, click **Add file → Upload files**, drag in all six files above (plus this README), then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/decades-mood-mixer/`.

## Add it to your iPhone Home Screen

1. Open the link above in **Safari**.
2. Tap the **Share** button (square with an arrow).
3. Scroll down and tap **Add to Home Screen**, then **Add**.
4. Open it from the new icon — it runs full screen and works offline once loaded.

## Updating later

1. Upload the changed `index.html` the same way (it replaces the old one).
2. Open `sw.js`, change `dmm-v1` to `dmm-v2` (then `v3`, and so on), and upload it too. This makes phones pick up the new version.
3. On the iPhone, close and reopen the app once or twice.

## Sharing

Tap the green ▶ on any song to open it in the Spotify app. The 😂 Cheeky crates on the Mix tab are themed playlists (Stalker Songs, Cheater Songs and more).

The **Share** buttons use the phone's share sheet (or copy to clipboard). The link carries your settings, e.g. `#o-party-e-2-m-2-s-1`, so your mates open the same picks. Room links carry everyone's name and vibe.

## Notes

- Listen links open a Spotify or Apple Music search for the artist and title.
- Clearing Safari website data will clear your ratings.
