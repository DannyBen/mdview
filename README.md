# mdview

![repocard](repocard.svg)

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

## Server

- Uses Ruby's built-in `-run -ehttpd` server by default.
- Server reference list (if you want to swap it): https://gist.github.com/willurd/5720255
