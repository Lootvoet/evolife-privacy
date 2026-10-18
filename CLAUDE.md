# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

This repo is just the hosted privacy policy for the Evolife Android game (`Lootvoet/evolife`): a single static, self-contained `index.html` (inline CSS, no build step, no JS), served as the public privacy-policy URL that Google Play requires.

- The Markdown source of the same text is `docs/release/privacy-policy.md` in the `evolife` repo. Keep both in sync, and bump the "Last updated" date in both whenever the wording changes.
- The policy must match what the app actually does: no server, progress stored on-device only, Google AdMob rewarded ads (with GDPR/UMP consent), Google Play Billing for in-app purchases. If the app adds an SDK or starts collecting data, update this page and the Play Console Data safety form together.
- Preview locally by opening `index.html` in a browser.
