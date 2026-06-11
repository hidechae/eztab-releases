# EZTab — Downloads

Desktop builds of EZTab (a cross-platform guitar tablature editor).
Source lives in a private repo; release binaries are published here.

Get the latest installer from [**Releases**](../../releases):
- **macOS** (Intel / Apple Silicon): `EZTab_x.y.z_universal.dmg`
- **Windows** (x64): `EZTab_x.y.z_x64-setup.exe`

## First launch (unsigned app)

The app is **unsigned**, so the OS blocks the first launch.

### macOS
1. Open the `.dmg` and drag **EZTab** to Applications.
2. Try to launch it once (it will be blocked — that's expected).
3. Open **System Settings → Privacy & Security**, scroll down, and click
   **"Open Anyway"** next to the EZTab message.
4. Launch again and choose **Open**.

> On recent macOS, right-click → Open no longer works to bypass this.
> CLI alternative: `xattr -dr com.apple.quarantine /Applications/EZTab.app`

### Windows
If SmartScreen appears, click **More info → Run anyway**.