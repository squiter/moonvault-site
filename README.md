# moonvault-site

Public landing page and release index for [Moonvault](https://moonvaultrpg.com).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W4189K4X)

Served via GitHub Pages at `moonvaultrpg.com`. The source project lives in a private repository; this repo holds the public marketing page, the public release artifacts, and a machine-readable release endpoint at `/releases.json`.

## Layout

- `index.html` — landing page ("coming soon")
- `releases/index.html` — public releases listing (renders `releases.json` client-side)
- `releases.json` — machine-readable release manifest, updated by the source project's CI on tag push
- `assets/` — icon and shared styles
- `CNAME` — custom domain (`moonvaultrpg.com`)

## releases.json shape

```json
{
  "schema_version": 1,
  "latest": "v1.21.4",
  "releases": [
    {
      "version": "v1.21.4",
      "published_at": "2026-06-01T00:00:00Z",
      "notes": "Changelog excerpt...",
      "assets": {
        "macos": { "url": "https://github.com/squiter/moonvault-site/releases/download/v1.21.4/Moonvault_x64.dmg", "size": 0 },
        "windows": { "url": "https://github.com/squiter/moonvault-site/releases/download/v1.21.4/Moonvault_x64_en-US.msi", "size": 0 },
        "linux": { "url": "https://github.com/squiter/moonvault-site/releases/download/v1.21.4/moonvault_amd64.AppImage", "size": 0 }
      }
    }
  ]
}
```
