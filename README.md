[![Swift Version](https://img.shields.io/badge/swift-5-lightgrey.svg)](https://swift.org/)
[![macOS Version](https://img.shields.io/badge/macOS->=26.0-lightgrey.svg)](https://www.apple.com/macos/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-lightgrey.svg)](https://www.gnu.org/licenses/gpl-3.0)
<p align="center">
  <br>
  <img src="Nocturnal/Assets.xcassets/AppIcon.appiconset/Icon-App-256x256@1x.png" alt="icon" height="145">
  <h3 align="center">Nocturnal</h3>
  <p align="center">
    Have more control over your screen at night
  </p>
</p>

### About

Nocturnal is a menu bar app for macOS that allows you to go the extra mile in controlling your display settings to reduce strain on your eyes. It includes darker than dark dimming, Night Shift fine tuning, multi-monitor support, and the ability to turn off Touch Bar on Macbook Pro.

This fork is a modified version of the original GPLv3 project. The original copyright notices and GPLv3 license are preserved, and this fork marks its Apple Silicon/macOS 26 changes in the source history.

<p align="center">
<img src="Docs/Images/Nocturnal-Screenshot.png" alt="icon" height="350">
</p>

### System Requirements

Nocturnal is now configured for Apple Silicon Macs and macOS 26.0 or later. It requires a Mac that supports [Night Shift](https://support.apple.com/en-us/HT207513#requirements).

### Installation

Download the latest build from this repository's GitHub Releases, or build the app from source with Xcode.

Development builds are signed for local testing. Public distribution builds should be signed with a Developer ID certificate and notarized before being shared broadly.

### Build and Run

Resolve Swift Package Manager dependencies in Xcode, then build MASShortcut with Carthage and open the project.

```bash
XCODE_XCCONFIG_FILE="$PWD/Carthage.xcconfig" carthage bootstrap --platform Mac
open Nocturnal.xcodeproj
```

### License and Source

Nocturnal is distributed under the GNU GPLv3. If you redistribute binaries, provide the corresponding source code and keep the GPLv3 license with the release.
