# De-Bloat the Brave Browser
A Windows Registry file to disable the bloat in the Brave Browser, including Rewards, Wallet, VPN, AI Chat, etc

This .reg file modifies the Windows Registry to enforce policies for several Brave features, which removes the icons and menu options entirely.

| Feature  | Action |
| ------------- | ------------- |
| Brave Rewards  | Disabled  |
| Brave Wallet  | Disabled  |
| Brave VPN  | Disabled  |
| Tor Private Tabs  | Disabled  |
| Brave AI Chat  | Disabled  |
| Brave Talk  | Disabled  |
| Speedreader  | Disabled  |

## Installation / Usage
- [Download](https://github.com/PixelIndieDev/DebloatBraveBrowser/releases/download/V1/DebloatBraveBrowser.reg) the DebloatBraveBrowser.reg file from this repository.
- Double-click the file to run it.
- Click **Yes** when the User Account Control (UAC) prompt appears.
- Click **Yes** to confirm you want to add the information to the registry.
- Restart Brave for the changes to take effect.

## How to Undo
Change the registry values from 1 to 0 (or 0 to 1, in some cases) or delete the value keys entirely
