# WindowRotate

Menu bar tool for macOS that captures a chosen window with **ScreenCaptureKit** and shows a live, rotatable interactive preview at **0° / 90° / 180° / 270°**, with optional Accessibility-based click forwarding.

## Download

Latest builds: [Releases](https://github.com/landrufang/WindowRotate/releases)

Current preview: **WindowRotate 1.7.5** (build 13) — `WindowRotate-1.7.5.dmg`

## Requirements

- macOS **14.0** or later
- **Apple silicon (arm64) only** — not a universal/Intel build
- **Screen Recording** permission (required)
- **Accessibility** permission (optional; only for click forwarding)

## Limitations

- This is **not** native foreign-window rotation. The original window stays upright and does **not** reflow its UI.
- Edge tuck moves the source aside for convenience; it is **not** a true hide.
- Protected content may black out; minimized sources pause capture; overlays may not follow.

## Signing / trust

- **Experimental preview build**
- **Ad-hoc signed**, **not** notarized
- Gatekeeper currently **rejects** this build
- Do **not** disable Gatekeeper. Prefer a future Developer ID–signed and notarized release for normal install trust.
- After install, re-grant Screen Recording / Accessibility if needed.
