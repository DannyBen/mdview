# mdview

Minimal Markdown previewer that renders via GitHub's Markdown API and serves a
local HTML file.

## Install

- Put `mdview` in your `PATH` and make it executable.

## Usage

```sh
mdview README.md
```

## Access token (optional)

- Set `GITHUB_ACCESS_TOKEN` if you want to avoid API rate limits.
- A standard GitHub personal access token is fine; no special scopes are needed for public Markdown.
