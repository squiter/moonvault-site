# moonvault-site

Public landing page, blog, and release index for [Moonvault](https://moonvaultrpg.com).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W4189K4X)

Served via GitHub Pages at `moonvaultrpg.com`. GitHub Pages builds the site with Jekyll, while the landing page remains a standalone HTML page. The source project lives in a private repository; this repo holds the public marketing page, Markdown blog posts, public release artifacts, and a machine-readable release endpoint at `/releases.json`.

## Layout

- `index.html` — landing page ("coming soon")
- `blog/index.html` — blog index at `/blog/`
- `_posts/` — published blog posts written in Markdown
- `_drafts/` — unpublished post drafts and the post template
- `_layouts/` — custom Moonvault blog and post theme
- `_config.yml` — Jekyll, permalink, feed, and sitemap configuration
- `releases/index.html` — public releases listing (renders `releases.json` client-side)
- `releases.json` — machine-readable release manifest, updated by the source project's CI on tag push
- `assets/` — icon and shared styles
- `CNAME` — custom domain (`moonvaultrpg.com`)

## Writing a blog post

Copy `_drafts/post-template.md` to `_posts/YYYY-MM-DD-post-slug.md`, replace the front matter, and write the post in Markdown. Published posts are generated at `/blog/YYYY/MM/DD/post-slug/`.

Preview drafts locally with:

```sh
bundle install
bundle exec jekyll serve --drafts
```

The repository's `mise.toml` selects Ruby 3.3.11 when you enter this directory. Make sure mise is activated in zsh once:

```sh
echo 'eval "$(mise activate zsh)"' >> ~/.zshrc
exec zsh
```

If mise asks whether to trust the project configuration, run `mise trust`.

Open `http://localhost:4000/blog/`. Omit `--drafts` to preview only published posts. GitHub Pages runs the production Jekyll build when changes reach the publishing branch.

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
