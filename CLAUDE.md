# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

This repo hosts the legal pages of the Evolife Android game (`Lootvoet/evolife`) on GitHub Pages: static, self-contained HTML (inline CSS, no build step, no JS).

- `index.html` is the privacy policy (https://lootvoet.github.io/evolife-privacy/), the URL Google Play requires. Its Markdown source is `docs/release/privacy-policy.md` in the `evolife` repo.
- `terms.html` is the terms of service (https://lootvoet.github.io/evolife-privacy/terms.html), entered in Play Console under the trader-status section and linked from the app's Settings. Its Markdown source is `docs/release/terms-of-service.md` in the `evolife` repo.
- Keep each page and its Markdown source in sync, and bump the "Last updated" date in both whenever the wording changes. The two pages link to each other in their footers.
- Both pages must match what the app actually does: no server, progress stored on-device only, Google AdMob rewarded ads (with GDPR/UMP consent), Google Play Billing for in-app purchases. If the app adds an SDK or starts collecting data, update the privacy policy and the Play Console Data safety form together. If purchases, the subscription or the ads change, check the terms of service too.
- Preview locally by opening the HTML files in a browser.
