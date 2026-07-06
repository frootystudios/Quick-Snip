# Quick Snip — Privacy Policy

**Effective date:** July 6, 2026
**Publisher:** Frooty Studios
**Contact:** <support@frootystudios.com>

## The short version

Quick Snip captures, annotates, and saves screenshots entirely **on your own
device**. It has **no servers, no accounts, and no analytics**, and it never
sells or shares your data. Your screenshots and settings stay on your computer.
The one exception: if you uninstall, your browser opens a short, **optional and
anonymous** feedback form (see "Uninstall feedback" below) — nothing is sent
unless you choose to submit it.

## What the extension handles (and where it stays)

- **Screenshots you capture.** When you capture a visible area, a selected
  region, or a full page, the image is created locally in your browser. The most
  recent captures (currently the last 10) are stored in your browser's local
  extension storage (`chrome.storage.local`) on your device so you can view,
  edit, copy, share, or download them from the extension's library. This data
  is stored **only locally** and is never sent anywhere.
- **Your settings.** Your preferences (image format, JPG quality, auto-download)
  are stored locally in the same way.
- **Downloads you initiate.** When you download a screenshot, your browser saves
  it to your Downloads folder. This happens only when you choose to download or
  when you have enabled auto-download; the file is written locally by your
  browser.

That is the complete list of data the extension handles. It does **not** collect
or transmit your browsing history, cookies, passwords, or personal information. A
screenshot naturally contains whatever was on your screen when you captured it —
that image is created and kept **on your device** and is never uploaded anywhere.

## What Quick Snip does NOT do

- ❌ It does **not** collect or store personal information.
- ❌ It makes **no network requests** — there is no backend or remote server.
- ❌ It contains **no analytics, telemetry, trackers, or advertising**.
- ❌ It does **not** sell or share any data with third parties.
- ❌ It does **not** require an account or sign-in.
- ❌ It does **not** use your data for any purpose unrelated to taking and
  managing your screenshots.

## Permissions and why they are needed

The extension requests only what it needs to capture and save screenshots. None
of these permissions are used to collect or transmit your data:

- **`activeTab` + `scripting`** — to capture the current tab and inject the
  capture UI (region overlay, notifications) **only when you start a capture**.
  The extension does not run on pages you don't capture.
- **`tabs`** — to capture the visible tab, open the screenshot library, and
  coordinate the capture flow.
- **`downloads`** — to save screenshots to your Downloads folder when you
  download them.
- **`storage` + `unlimitedStorage`** — to keep your recent screenshots and
  settings on your device (screenshots are large, so the default quota is
  lifted).
- **`offscreen`** — an internal, local helper used to reliably save large
  screenshots. It performs no network activity.

## Data retention and control

- Screenshots are kept only on your device, and only the most recent ones (the
  library holds up to 10 at a time).
- You can delete any screenshot from the library at any time.
- **Uninstalling the extension removes all of its stored data** from your
  browser.

## Uninstall feedback (optional)

When you uninstall Quick Snip, your browser opens a short feedback form so you
can (optionally) tell us why you left. This form is **optional and anonymous** —
we do not ask for your name, email, or any personal information. It is hosted on
**Google Forms**, so if you choose to submit a response it is sent to Google
Forms and handled under Google's privacy policy. You can simply close the page to
send nothing.

## Children's privacy

Quick Snip is a general-purpose utility and does not knowingly collect any
information from anyone, including children under 13.

## Changes to this policy

If this policy changes, the updated version will be posted at this same location
with a new effective date. Material changes will be reflected before they take
effect.

## Contact

Questions about this policy or the extension? Contact us at
<support@frootystudios.com>
