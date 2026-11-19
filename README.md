# Mo’s birthday

Private birthday website with 18 voice recordings, photos, and an intro video.

## Run locally

```sh
python3 -m http.server 8765 --bind 127.0.0.1 --directory docs
```

Open http://localhost:8765/. Click the play button to start the intro with sound.

The static website lives in `docs/`. Recording metadata is in `docs/samples.json`.
Temporary editing files, removed photos, unused drafts, and the original full recording are excluded from Git.
GitHub Pages publishes the site from `docs/` on `main`.
