# offirlaufer.com

The publisher site for **Chronicle / כרוניקל**, served by GitHub Pages at
<https://offirlaufer.com> (`CNAME`).

| path | source of truth |
| --- | --- |
| `index.html` | `docs/play/landing_page.html` in the Chronicle repo |
| `privacy/index.html` | `docs/play/privacy_policy.html` in the Chronicle repo |

**Nothing syncs these automatically.** Both are hand-copies, which is how the
live policy once sat a day behind a correction with nothing reporting the gap.
Publish the policy with `tools/publish_privacy.sh` in the Chronicle repo rather
than by editing here; it refuses to run against uncommitted source and records
the originating SHA in the commit message.

The repo is public because GitHub Pages on the free plan requires it. It holds
no secrets and no user data — the app sends nothing anywhere.

Renamed in purpose on 2026-11-12, when the site grew a landing page and the
policy moved from the root to `privacy/`. The old
`offirlaufer.github.io/chronicle-privacy/` now redirects to the custom domain.
