# LOCKHEAD

LOCKHEAD is a single-file, terminal-themed browser playground. Open `index.html` directly in a modern browser; it has no build step or external dependencies.

## GitHub Pages

The `Deploy LOCKHEAD to GitHub Pages` workflow publishes the static terminal and local catalogue from `main`. Push the workflow, then visit `https://ripepicjm234-hub.github.io/LOCKHEAD/` after deployment. If GitHub does not allow the workflow to enable Pages, select **Settings → Pages → Build and deployment → GitHub Actions** once. `/arch` opens the official ARCH website at `https://arch.wuaze.com/` in a new tab; `/archlocal` opens LOCKHEAD's static, non-proxy catalogue. The full ARCH application requires its own Node.js backend and is not mirrored by GitHub Pages.

## Local server

In VS Code, run the **LOCKHEAD: Serve locally** task to serve the site at `http://localhost:8000/`. It binds to `127.0.0.1` and uses Python's built-in HTTP server.

## Terminal commands

Type `/help` for the complete list. `/about` opens project details; `/version`, `/uname`, `/uptime`, and `/echo` provide basic shell-style commands. `/games` lists the built-in arcade and `/game snake` launches Pixel Snake. `/arch` opens the official ARCH website at `https://arch.wuaze.com/` in a new tab; `/archlocal` opens the local ARCH games catalogue, where games launch directly from their original sites without a proxy. `/archsrc` opens the upstream source on GitHub. Use `/tab` for a blank browser tab or `/open <url>` to open a URL in a new tab.

Use `/stocks` or `/stocks NVDA` for a TradingView chart; other tickers such as `/stocks AAPL` and exchange-qualified symbols such as `/stocks NYSE:IBM` are supported. Charts are informational and prices may be delayed.

The `/hack`, `/ddd`, `/dxd`, `/scan`, `/decrypt`, `/root`, and `/matrix` commands are offline visual effects only. They do not scan devices, access systems, or make network requests. LOCKHEAD is a browser shell emulator, not a Linux host. Command history is stored locally in browser storage. The local ARCH catalogue excludes its proxy and game binaries; see [ARCH-LICENSE](./arch/ARCH-LICENSE) for the upstream catalogue license.
