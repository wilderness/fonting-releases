# Fonting 0.4.0-beta.7

Fonting helps you discover, organize, preview, and compare typefaces on your Mac.

## What's new in 0.4.0-beta.7

- Fonting is now signed by Geoform LLC with an Apple Developer ID certificate and notarized by Apple for direct download. The app and DMG include notarization tickets for offline verification.
- The universal installer supports Apple silicon and Intel Macs running macOS 13 or newer.

## Library and specimen tools


- Scan & cleanup helps organize your library using font names, metadata, and local letterform analysis. Review results, research unresolved foundries, and undo the last scan. Included for verified beta users now; planned as a paid feature after beta.
- Automatic Serif and Sans Serif collections appear for every user and stay in sync with imports, classification changes, and cleanup results. Serif also includes slab serif fonts.
- Foundry grouping recognizes variations such as “and” versus “&” and registered trademark symbols. Local metadata and references identify foundries where possible; uncertain vendor matches are suggestions for review.
- Browse fonts from a collapsible list inside the specimen page, with the same sorting options as the grid. Specimen controls now include line height down to 50%, size up to 240 px, and tracking down to -150. Tight line heights preserve visible letter edges.
- Choose preview text and background colors using an inline spectrum, hex values, or eight preset chips, with a No background option and a subtle tint when both colors match.
- A more compact preview toolbar, cleaner Font Details header, and foundry names beneath specimen titles keep controls organized. Style is the rightmost specimen control.
- Font cells keep their height steady while dragging Size, and long previews clip without a horizontal scrollbar. Variable fonts with weight axes starting at zero, including Garaje, now preview correctly.
- A branded three-second startup screen shows the running version.

Font analysis runs on your Mac without uploading font files or specimens. Unusual or ambiguous fonts may still need manual classification. Research foundry opens a browser search using the font name; it does not automatically resolve every unknown foundry.

Available styles and characters depend on what each website provides. Some sites expose only trial files or limited webfont subsets. If a site does not provide accessible font files, import a file obtained from the foundry.

## Included in the beta

- Import up to five font families through pasted links for free, with all styles in each family. Confirm your email to unlock unlimited link imports during the beta, with no password, payment details, or automatic charges. Fonts already on your Mac and local-file imports do not use this allowance.
- Cloud sync and font-file backup remain separate opt-ins.
- Verified beta access also includes Scan & cleanup. Automatic Serif and Sans Serif collections are available to all users without verification.
- Preview every style at full size, compare fonts side by side or stacked, and try ten square design layouts.
- New beta releases appear in an in-app toast with a Download Update button.

Beta access is not a lifetime purchase of a future paid version. Font licenses are separate from access to Fonting.

## Download and install

**macOS 13 or newer. One universal download supports Apple silicon and Intel Macs.**

[Download Fonting for Mac (0.4.0-beta.7)](https://github.com/wilderness/fonting-releases/releases/download/v0.4.0-beta.7/Fonting-0.4.0-beta.7-universal.dmg) · [ZIP alternative](https://github.com/wilderness/fonting-releases/releases/download/v0.4.0-beta.7/Fonting-0.4.0-beta.7-universal.zip)

Open the DMG and drag Fonting to Applications. For an update, quit Fonting first and replace the existing app; your library is stored separately.

This beta is **Developer ID signed and Apple notarized**. Open Fonting from Applications and confirm the standard first-launch prompt if macOS asks. Your existing fonts, collections, and settings remain in their separate library folder.

## Font licenses

Importing, previewing, converting, downloading, or installing a font does not grant a font license. Obtain the rights required for your intended use and comply with the font's terms. Free and open-source fonts also have license terms. Fonting does not authorize unlicensed use. See [Legal Disclaimer](LEGAL.md). Bundled open-source font licenses are included in the app.

Beta software can contain bugs. Keep independent backups. [Report a bug](https://github.com/wilderness/fonting-releases/issues) with your macOS version, Fonting version, and steps to reproduce; do not attach private fonts or account credentials.
