# Phase 2 GitHub Pages Patch, FrameReady Camera

Last updated: 5 June 2026

## Purpose

This patch optimizes the public GitHub Pages legal/support site for App Review, subscription transparency and user trust.

## Files changed

- `index.html`
- `privacy.html`
- `terms.html`
- `support.html`
- `imprint.html`
- `404.html`
- `assets/style.css`
- `README.md`

## Assets added

- `assets/app-icon.png`
- `assets/app-icon-512.png`
- `assets/app-icon-192.png`
- `assets/apple-touch-icon.png`
- `assets/app-icon-64.png`
- `assets/favicon-32.png`

The actual FrameReady Camera app icon from the Xcode project is now used in the navigation header, footer, home hero section, favicon and Apple touch icon.

## Privacy Policy changes

Added a dedicated section:

`Face Data and Frame Assist`

This section explains:

- what face-related data is processed,
- that it is used only for geometric framing assistance,
- that it is processed locally on device,
- that it is temporary/in memory,
- that it is not uploaded,
- that it is not shared with third parties,
- that it is not sold,
- that it is not used for advertising or tracking,
- that the app does not identify users,
- that the app does not create a faceprint or face template,
- that the app does not infer age, emotion, health, beauty, ethnicity, identity, personality or other personal attributes,
- how recorded videos are retained locally or exported by the user.

## Terms changes

The Terms page now clearly states that FrameReady Camera uses Apple’s standard EULA and links directly to:

`https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`

The page also includes clearer subscription language about auto-renewal, cancellation through Apple, restore purchases, region-dependent prices and trial availability.

## Support changes

The Support page now contains a dedicated Frame Assist support paragraph and links directly to the `Face Data and Frame Assist` section of the Privacy Policy.

## Design changes

The site now uses the real app icon and a more premium legal/support design system while keeping the pages lightweight, static and GitHub Pages friendly.

## App Review use

In App Review Notes, point Apple to:

- Privacy Policy: `https://flinzel.github.io/framereadycamera/privacy.html`
- Face Data section: `Face Data and Frame Assist`
- Terms/EULA: `https://flinzel.github.io/framereadycamera/terms.html`

The exact face data quote can be copied from `APP_REVIEW_NOTES_FACE_DATA.txt`.


## Visual refinement

The home-page hero no longer uses the app icon as an oversized standalone graphic. The icon is now used as a controlled brand element inside a compact trust card, while navigation, footer, favicon and touch icons remain unchanged.
