# Install the friends beta

## Download

Get `Code-Valley_0.1.0-beta.2_macOS_arm64.zip` from the [beta.2 release](https://github.com/beapessoa/code-valley-releases/releases/tag/v0.1.0-beta.2). The release also supplies `SHA256SUMS.txt`. No GitHub account or access to the private application source is required to download.

Open the ZIP in Finder, drag **Code Valley.app** into **Applications**, and open that copy. Keep one installed copy. This beta is for Apple Silicon; current native evidence is macOS 26.5.1. The package declares a 15.0 build floor, which is not validation of older systems.

Optional verification in Terminal: run `shasum -a 256` followed by a space and drag the downloaded ZIP into Terminal. Compare the result with the release's checksum before opening it.

## If macOS blocks the first launch

The app is **ad-hoc signed and not notarized**. Apple has not verified this beta for distribution. If you trust this download and choose to proceed, Apple's documented per-app route is:

1. Try opening Code Valley from Applications and read the warning.
2. Open **System Settings → Privacy & Security**, scroll to the blocked app, and choose **Open Anyway**, if offered for Code Valley.
3. Read the confirmation and choose **Open** if you want to allow this app.

This creates an exception for the app. Do not disable Gatekeeper globally or run commands that remove quarantine. If macOS says the app is damaged, will harm your computer, or offers no matching exception, stop and send Bea the exact message. Managed Macs may restrict this route. A downloaded beta.2 installation has not yet been accepted on a tester's Mac; this is a test step, not a guarantee.

[Apple's first-launch guidance](https://support.apple.com/en-gb/102445), checked November 14, 2026.

## Connect Claude Code

1. Choose a cat. At **Connection**, review the displayed settings path and hook changes, then choose **Install**. The app makes a backup and preserves unrelated hooks/settings. Notification permission is optional.
2. Start a **new** Claude Code session in a disposable repository, in terminal or Claude Desktop's **Code** environment. Existing sessions may need restarting; ordinary Claude chat does not connect.
3. Make normal edits. Click the menu-bar cat to open the farm. If the icon is hidden, open Code Valley from Applications again. **Menu → Settings → Integration** and **Logs** help diagnose a missing farmer.

## Harvest and return

Successful edits grow crops; completing a turn harvests mature crops. Look for **Stored in Harvest**, then click the chest or **Harvest**. Three items in any crop mix buy a Garden bush for a free garden slot. Progress is separate for each repository. Older historical harvest totals do not turn into new inventory.

Quit normally, reopen and verify your progress. Saves can take up to two seconds; an abrupt exit can lose the latest unsaved changes.

## Update or remove

There is no automatic updater. Before updating, quit and back up `~/Library/Application Support/app.codevalley.CodeValley` and `~/.codevalley`. Replace the app in Applications, reopen, check **Settings → About**, farms and balances, then use **Integration → Install** if prompted to refresh the hook. Keep the old app and matching backup; ask Bea before a rollback to an older data format.

To remove: disable launch at login if enabled, choose **Settings → Integration → Uninstall**, quit, then move the app to Trash. Unrelated Claude settings remain. Farm data and recovery backups are retained for reinstalling; removing the app does not erase them.

Report problems through the [feedback instructions](README.md#feedback). Do not post the private data directories or Claude settings.
