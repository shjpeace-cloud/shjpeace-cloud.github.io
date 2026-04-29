# shjpeace-cloud.github.io

Host-level landing page for the GitHub Pages user account `shjpeace-cloud`.

The actual academic website lives at the repo
[`shjpeace-cloud/academic`](https://github.com/shjpeace-cloud/academic),
served at `https://shjpeace-cloud.github.io/academic/`.

This repo only serves a small `index.html` at the host root that redirects
visitors of `https://shjpeace-cloud.github.io/` to `/academic/`. The reason
is that some search-engine webmaster tools (e.g. Naver Search Advisor)
require host-level URL ownership rather than a subpath; placing a
verification file and a redirect here lets us claim the host without
disturbing the actual site URL.
