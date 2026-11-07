# Magic Card Viewer

Builds of Magic Card Viewer, an app for tuning Commander decks, for Windows and Mac.

## Install on Windows

1. Download `Magic-Card-Viewer-Setup-….exe` from the [latest release](../../releases/latest).
2. Run it. Windows will show "Windows protected your PC", because the app isn't signed with a paid certificate. Click **More info**, then **Run anyway**.
3. It installs in a few seconds, with no admin rights needed, and opens. You'll find it in the Start menu afterwards.

## Install on Mac (Apple Silicon)

1. Download `Magic-Card-Viewer-…-arm64.zip` from the [latest release](../../releases/latest).
2. Unzip it and drag **Magic Card Viewer** into your **Applications** folder.
3. Open it. macOS will say it can't verify the app, because it isn't signed through the paid Apple program. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.
   If macOS says instead that the app "is damaged", run this once in Terminal, then open the app:
   `xattr -dr com.apple.quarantine "/Applications/Magic Card Viewer.app"`

## Updates

After the first install the app updates itself. When a new version is ready, a **Restart to update** button appears in the top bar, and otherwise the update installs the next time you quit.

## AI features

Analysis, deck suggestions and the playtest Coach use [Claude Code](https://docs.claude.com/en/docs/claude-code) on your computer with your own Claude account. Install it, then run `claude` once in a terminal to log in. Everything else works without it.
