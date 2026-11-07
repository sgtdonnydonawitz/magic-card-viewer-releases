# Magic Card Viewer


## Install

1. Download `Magic-Card-Viewer-…-arm64.zip` from the [latest release](../../releases/latest). It needs an Apple Silicon Mac.
2. Unzip it and drag **Magic Card Viewer** into your **Applications** folder.
3. Open it. macOS will say it can't verify the app, because it isn't signed through the paid Apple program. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.
   If macOS says instead that the app "is damaged", run this once in Terminal, then open the app:
   `xattr -dr com.apple.quarantine "/Applications/Magic Card Viewer.app"`

After the first launch the app updates itself. When a new version is ready, a **Restart to update** button appears in the top bar, and otherwise the update installs when you quit.

## AI features

Analysis, deck suggestions and the playtest Coach use [Claude Code](https://docs.claude.com/en/docs/claude-code) on your Mac with your own Claude account. Install it with `npm install -g @anthropic-ai/claude-code`, then run `claude` once to log in. Everything else works without it.
