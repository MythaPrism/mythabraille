# MythaBraille privacy statement

*Effective October 13, 2026 · MythaPrism LLC*

## Short version

MythaBraille collects nothing about you. It has no accounts, no analytics, no cookies, no tracking and no uploads.
Everything you type and every file you export is made on your own device.

## What happens when you use MythaBraille

| | |
|---|---|
| **Network** | Your browser makes one request: the MythaBraille page itself. After that, MythaBraille makes no network requests of any kind. |
| **Your text** | Stays in your browser. It is turned into braille on your device. |
| **Exported files** (3MF, STL, project files) | Made on your device and saved where you choose. They never pass through MythaPrism. |
| **Autosave** | Your current work is saved in your browser's local storage under the name `mythabraille.v1`, on your device only, so a reload does not lose it. It contains your settings and your text. Clearing your browser's site data removes it. |
| **Cookies** | None. |
| **Analytics, ads, trackers, fingerprinting** | None. |
| **Accounts** | None. MythaBraille never asks who you are. |

An automated test in this repository (`test/privacy.test.cjs`) opens MythaBraille, uses it from start to finish
(typing, settings, 2D and 3D, page sizes, export, save) and fails if the browser makes any request other than the page
itself, or stores anything other than the autosave.

## The website or service that delivers the page

To open MythaBraille your browser has to download the page from somewhere. That one request is handled by:

- **mythaprism.com**: served through Cloudflare. Cloudflare and MythaPrism's hosting see the normal details any website
  receives with a request (such as IP address, browser type and time). This is covered by the
  [MythaPrism Privacy Policy](https://mythaprism.com/privacy.html).
- **GitHub Pages**: served by GitHub, under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
  MythaPrism does not receive anything from it.

## Opening MythaBraille from your MythaPrism account

Your free MythaPrism account page has a **Launch** button for MythaBraille. It is only a link to the same page.
MythaBraille does not read your account, and MythaPrism does not record what you make with MythaBraille. Signing in is
never required to use it. You can open it from mythaprism.com/braille.html or GitHub Pages instead.

## Children

MythaBraille collects no personal information from anyone, including children.

## Changes

If MythaBraille ever needs to send or store anything else, this statement will be updated **before** that version is
released, and the change will be listed in the [build notes](https://mythaprism.com/updates.html).

## Contact

support@mythaprism.com · MythaPrism LLC, PO Box 47373, Windsor Mill, MD 21244, USA
