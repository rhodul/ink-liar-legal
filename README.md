# ink-liar-legal

Legal documents for **Ink Liar**, an Android game published by Rastislav
Hodul via the Google Play Store (package `com.gnugu.tapthecolor`).

The documents here are published via GitHub Pages at:

**<https://rhodul.github.io/ink-liar-legal/>**

## Contents

- [`privacy-policy.md`](privacy-policy.md) — rendered at
  [`/privacy-policy.html`](https://rhodul.github.io/ink-liar-legal/privacy-policy.html).
  This is the URL registered with the Google Play Console for the App
  listing.
- [`index.md`](index.md) — minimal landing page served at the site root.

## Why a separate repo?

The Ink Liar application code lives in a **private** repository. GitHub
Pages on the free plan requires a public repository to host pages, so
this small sidecar repo exists purely to host the legal documentation
that the Play Store listing links to.

When the App's data flows change (new SDK, new analytics, new
permissions), the policy here must be updated in lockstep with the App's
own **Data Safety** questionnaire answers in Play Console. The public-
facing policy has a single source of truth here; the App repo simply
references this URL.

## Updating the policy

1. Edit `privacy-policy.md`.
2. Bump the **"Last updated"** line in the header to today's date.
3. Commit and push.
4. GitHub Pages rebuilds automatically in ~60 seconds.
5. Verify the rendered output loads at
   <https://rhodul.github.io/ink-liar-legal/privacy-policy.html>.

If the change was triggered by a change to the App itself (new SDK,
etc.), the App's private repo also needs an update to the
`notes/store-listing.md` "Data Safety" block — do both in the same
work session so the public policy and the Play Console structured
answers stay aligned.

## License

Copyright © 2026 Rastislav Hodul. All rights reserved.
