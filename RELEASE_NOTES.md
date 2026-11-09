# WPL Playlist Support for foobar2000 (64-bit)

First community-maintained x64 build of the original [foo_wpl](https://github.com/UrbanCMC/foo_wpl) component.

## What's included
- 64-bit Windows component compatible with foobar2000 v2.x (tested by a user with foobar2000 2.26.1 x64 on Windows 10).
- Import existing Windows Media Player .wpl playlists.
- Export playlists to .wpl and reopen them.
- Existing foobar2000 .fpl support remains unaffected.
- Updated Visual Studio 2022 / C++20 build using a recent foobar2000 SDK and TinyXML-2.
- Safer handling of malformed WPL XML and paths.

## Installation
1. Download **foo_wpl_x64.fb2k-component** from the Assets section below.
2. In foobar2000, open **File > Preferences > Components > Install...**.
3. Select the downloaded .fb2k-component file and restart foobar2000.

## Compatibility and caveats
Tested interactively on foobar2000 2.26.1 64-bit on Windows 10: component installation, importing .wpl, exporting .wpl, and reopening saved .wpl and .fpl playlists all succeeded. Other foobar2000 versions / Windows versions have not yet been tested.

Based on Alexander Gyimesi's original foo_wpl source; third-party SDK and TinyXML-2 retain their respective licenses. See LICENSE and the original repository for attribution.
