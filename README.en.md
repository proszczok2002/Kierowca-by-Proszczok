# Kierowca by Proszczok

[Polski](README.md) · [Official website](https://proszczok.pl/kierowca/?lang=en) · [Contact and issues](https://github.com/proszczok2002/Kierowca-by-Proszczok/issues)

An NVDA add-on that routes synthesizer speech or application audio through Virtual Audio Cable to a TeamTalk microphone or another communication app. Start or stop routing with **NVDA+Shift+Alt+K**.

## Download

**Current version: 1.78.**

[Download the latest add-on from proszczok.pl](https://proszczok.pl/kierowca/Kierowca%20by%20Proszczok.nvda-addon)

GitHub is the project's showcase, release history and contact point. Downloads and the updater use **proszczok.pl**. The download link always serves the latest version; GitHub does not provide update packages.

## Features

- Routes NVDA speech, music and application audio to a communication app's input.
- Saves source and target choices and identifies devices by name.
- Announces start and stop with speech and tones.
- Provides an optional status banner and audio-stream monitoring.
- Remains off after restarting NVDA until manually enabled.
- Requests consent before an update and separately before restarting NVDA.
- Includes a Support menu with PayPal, Revolut and the author's website.

## Requirements and installation

Windows, NVDA 2023.1 or later, installed Virtual Audio Cable, and TeamTalk or another communication app. Typical routing requires two separate virtual cables.

1. Download the `.nvda-addon` file from the official website.
2. Open it, confirm installation and restart NVDA.
3. Open **NVDA → Tools → Kierowca by Proszczok → Ustawienia… (Settings)**.
4. Select the source and target, then press **NVDA+Shift+Alt+K**.

## Example: Line 1 → Line 3 → TeamTalk

Set NVDA's output to the Line 1 playback endpoint. Select Line 1 recording as the source in Kierowca and Line 3 playback as the target. In TeamTalk, select Line 3 recording as the microphone and keep playback on headphones or speakers.

Kierowca's output and TeamTalk's microphone must use **the same cable number**. Kierowca does not change TeamTalk's microphone selection.

## Contact

[Ask a question, report a bug or request a feature](https://github.com/proszczok2002/Kierowca-by-Proszczok/issues/new/choose).

Issues are public. Include the add-on and NVDA versions, your cable setup and steps to reproduce. Remove private information from log excerpts before posting.

[Changelog](CHANGELOG.md) · [Release announcements](https://github.com/proszczok2002/Kierowca-by-Proszczok/releases) · [Privacy policy](https://proszczok.pl/privacy.html)

## Support the author

[PayPal](https://paypal.me/proszczok) · [Revolut](https://revolut.me/r_rosiejka) · [Author website](https://proszczok.pl/)

## Repository contents

This public repository contains documentation, release information and issue forms. It does not contain development sources or installer copies. Project sources are maintained separately. The downloadable NVDA package includes modules needed to run the add-on; keeping sources out of this repository does not conceal the contents of that package.
