# Hunch Chat desktop downloads

Hunch Chat for Mac and Windows opens in its own desktop app, with native notifications, file saving and update checks. An internet connection and a Hunch account are required.

[Download the latest release](https://github.com/chastenr/hunch-chat-releases/releases/latest) · [Open Hunch Chat](https://hunchme.vercel.app/chat/)

- **Mac with Apple silicon:** use the `mac-arm64.dmg` installer (M-series processors).
- **Intel Mac:** use `mac-x64.dmg`. Both Mac builds require macOS 13 or later.
- **Windows:** use `windows-x64-setup.exe` on 64-bit Windows 10 or later.

On Mac, open the DMG and drag Hunch Chat into Applications. On Windows, open the setup file and follow its instructions. Quit an existing Hunch Chat installation before replacing it; your account and locally saved drafts remain in its existing profile.

## Signing status

These builds are not Apple Developer ID signed/notarized or Windows Authenticode signed. macOS Gatekeeper and Windows SmartScreen can block or warn about them. Only proceed if you trust the publisher and download. SHA256SUMS.txt verifies file integrity; it is not platform code signing. Windows installation has not been validated on a physical Windows device.

## Updates

Starting with 0.1.10, the app automatically checks at launch and every six hours. Settings offers optional background downloads. You choose when to open the installer; Hunch Chat never silently restarts itself. Older app versions need this installer once to add these controls. Automatic application replacement is not enabled in these unsigned builds.

## Repository contents

This repository distributes desktop installers, release checksums and installation instructions. It contains no application server source, account data, chat messages or server credentials. Release binaries include the desktop client code needed to run the app. No license to redistribute or modify Hunch Chat is granted by making these downloads available. Bundled third-party software retains its own licenses.
