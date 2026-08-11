# 🥀 Delusions Don't Make Consensus

![A wilted rose with layered petals rendered in Bitcoin's signature orange](og-image.png)

An argument about Bitcoin's failed BIP-110 soft fork, and what it has in common with Thomas Jefferson and James Monroe.

BIP-110 needed 55% miner signaling to activate. It got 2.53% — and even that wasn't a broad coalition, it was effectively one mining pool's default setting. The resulting minority chain split off, mined exactly two blocks in fifteen hours, and stalled while the main network moved on. This piece isn't a technical post-mortem of the code. It argues that plenty of technically fluent people supported BIP-110 anyway, because expertise doesn't protect anyone from conviction outrunning its actual backing — the same pattern behind Jefferson's agrarian idealism and Monroe's toothless Doctrine. What actually earns the word "delusional" here isn't the proposal's underlying grievance (real, and still defensible) but what happened once the fork lost: CSAM accusations, Flat Earth talk in the same Discord channels, a BIP editor removed over how the proposal was pushed through, and a pivot toward abandoning Bitcoin's miners entirely rather than accepting the numbers.

The piece is built around direct quotes from Jameson Lopp, Michael Saylor, Adam Back, Jason Hughes, Luke Dashjr, Samson Mow, and David Schwartz, three inline charts (signaling vs. threshold, block-height divergence, the difficulty-adjustment blowout to 6.3 years), and roughly 50 sources organized into four rose-themed groups at the bottom of the page.

The hero image and favicon are the same illustration: a wilted, multi-layered rose bloom with petals rendered in Bitcoin's signature orange (#F7931A), drooping on a dried stem — original vector art, procedurally generated, not a stock photo. It's meant to sit at the top of the page as the thesis, not the decoration.

## Deployment

Static site, no build step. Push the contents of this repo to a GitHub Pages–enabled repository (root or `/docs`, either works) and it's live. Everything — HTML, favicons, SEO files, and the article itself — is a flat file at the repo root; no subfolders to reorganize. Google Analytics (GA4, Consent Mode v2) is wired in with a cookie banner; update the measurement ID in `index.html` if you're forking this for a different property.

## License

MIT — see `LICENSE`.
