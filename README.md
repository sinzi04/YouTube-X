# YouTube X (No-Jailbreak Fork)

A fork of [YouTube-X](https://github.com/PoomSmart/YouTube-X) by [PoomSmart](https://github.com/PoomSmart), adapted to work on **non-jailbroken iOS devices** via sideloading.

No ads. Background playback. No jailbreak required.

## Features

- 🚫 Blocks video ads, feed ads, and Shorts ads
- 🎵 Background playback support
- 📱 Works on stock (non-jailbroken) iOS devices
- 🪶 Lightweight — same core as the original tweak

## Requirements

- iOS 11.0 or later
- A tool that can inject a `.dylib` into an IPA, such as:
  - [eSign](https://esign.yyyue.xyz/)
  - Any other IPA signer with dylib injection support

## Installation

1. Download the latest `.dylib` from the [Releases](../../releases) page.
2. Obtain a decrypted YouTube IPA.
3. Open the IPA in eSign (or your preferred tool) and inject the `.dylib`.
4. Sign and install the app on your device.

## Known Issues

| Issue | Status | Workaround |
|---|---|---|
| Video stops / stuck on loading screen | Investigating | Injecting [YouPiP](https://poomsmart.github.io/repo/depictions/youpip.html) may help — planned to be bundled in a future release |
| Cannot log in to Google account | 🔧 Fix in progress | — |
| Search history resets when app is reopened | 🔧 Fix in progress | — |

Found a different bug? Please [open an issue](../../issues) with your iOS version, YouTube app version, and the signing tool you used.

## Credits

- **[PoomSmart](https://github.com/PoomSmart)** — original author of [YouTube-X](https://github.com/PoomSmart/YouTube-X)
- This fork only adapts the tweak for sideloaded (jailed) environments

## Disclaimer

This project is for educational purposes only. It is not affiliated with, endorsed by, or sponsored by Google or YouTube. Use at your own risk.

## License

Follows the license of the [upstream repository](https://github.com/PoomSmart/YouTube-X).
