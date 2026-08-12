# The Black Door Society

A premium, zero-build horror-author landing page designed to convert readers into free and paid Patreon community members.

## Current build
The public experience is intentionally self-contained in `index.html`:
- no paid site builder
- no framework or build step
- no external font/CDN dependency
- responsive literary-horror design
- free-membership-first conversion path
- paid membership tiers and Midnight Manuscript experience

## Connect Patreon
Near the bottom of `index.html`, replace:

```js
const PATREON_URL='';
```

with Jeff's real Patreon creator URL. Every membership CTA will then open Patreon in a new tab. Until that is connected, buttons display a clear "not connected yet" message rather than sending readers to a bad link.

## Hosting
Recommended production host: Cloudflare Pages. Connect this GitHub repository, use `main` as the production branch, and use no build command. The output/root directory is the repository root.

The hosting architecture is intended to remain $0/month aside from an optional custom domain.

## Next assets to add
- real author portrait
- real book title and cover
- Patreon URL
- Amazon author/book links
- custom domain

## Kindle Unlimited guardrail
Do not distribute the same digital ebook through the site or Patreon while that title is enrolled in KDP Select/Kindle Unlimited. The membership experience is structured around community, creative process, readings, eligible bonus/alternate material, cover decisions, and behind-the-scenes access instead.
