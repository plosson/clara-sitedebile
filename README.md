# Clara · vibes

TikTok-style neon site for Clara — dark Gen-Z aesthetic, video vibes feed, Spotify playlist embed.

**Live:** https://clara.sitedebile.fr

## What's included

- **Hero** — Clara intro + profile glass card
- **Video vibes** — vertical muted looping HTML5 demos (public/royalty-free samples, not TikTok)
- **Playlist** — official Spotify embed (swap the playlist ID anytime)
- **About + socials** — Instagram / TikTok / Spotify placeholders

## Redeploy (SiteIO)

SiteIO must be logged in to sitedebile.fr (`siteio status`).

```bash
siteio sites deploy /workspace/clara-site -n clara
```

Or from this folder:

```bash
siteio sites deploy . -n clara
```

## Edit tips

- Social links: update the `href`s in the About section of `index.html`
- Spotify: change the iframe `src` playlist ID (`37i9dQZF1DXcBWIGoYBM5M` → yours)
- Videos: replace the `<video src="...">` URLs with other royalty-free clips

## Stack

Static HTML/CSS/JS only. Hosted via SiteIO on sitedebile.fr.
