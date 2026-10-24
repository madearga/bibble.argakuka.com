# bibble.argakuka.com

The website of [Bible.app](https://github.com/madearga/bible-rs-rs), a native
macOS Bible reader. One hand-written `index.html`, no build step, deployed by
GitHub Pages.

## Deploying

Push to `main`. Pages serves the branch root directly; `.nojekyll` keeps it
from processing anything, and `CNAME` pins the custom domain.

## Domain

`bibble.argakuka.com` is a `CNAME` record pointing at `madearga.github.io`.
Pages issues its certificate once the record resolves; HTTPS is enforced in
the repository's Pages settings.
