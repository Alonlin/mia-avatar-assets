# mia-avatar-assets

Public reference images for the **Mia** streaming-avatar demo built on the
[Vivix Streaming Avatar API](https://platform.vivix.ai/doc/overview/introduction).

These have to live at a public HTTPS URL because Vivix fetches the source image
**server-side** when a session is created — there is no image-upload endpoint, and
`data:` URLs and `localhost` are rejected (`20016 source image is inaccessible`).
Vivix re-hosts the image on first use, so it only has to be reachable at that moment.

| File | Size | Use |
|---|---|---|
| `avatars/mia-front.png` | 768 × 1376 | `avatars[].visual.source_images[].url` — front view, half body |
