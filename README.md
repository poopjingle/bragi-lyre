# Lyre Offerings to Bragi: Android app

This folder is the installable version of your practice app. It has everything the Claude version has, plus a microphone tuner with a needle, and it works offline once installed. Your progress is stored on the phone.

## What's in the folder

| File | What it is |
| --- | --- |
| index.html | The app |
| manifest.webmanifest | Tells Android the app's name, icon and colors |
| sw.js | Lets the app open without internet |
| icon-*.png | App icons |

## Live address

**https://poopjingle.github.io/bragi-lyre/**

The site is published by GitHub Pages from the `gh-pages` branch. To update the app later, change the files on `gh-pages` (and on `main`, to keep them matching).

## Install it on your Android phone

1. Open **https://poopjingle.github.io/bragi-lyre/** in **Chrome**.
2. Tap the **⋮** menu, then **Add to home screen** (it may say **Install app**). Confirm.
3. Open the app from your home screen. The first time you tap **Start tuner**, allow microphone access.

## Using the tuner

- Pluck one string at a time and let it ring. The tuner shows the nearest string, how many cents off it is, and whether to tighten or loosen.
- If a string is far off, tap that string in the grid to lock the tuner onto it.
- A green dot marks each string that held in tune. **Reset checklist** clears them for the next session.
- **Reference tones** plays each target note if you prefer tuning by ear.

## Moving progress between versions

The Claude link saves progress to your Claude account; this app saves it on your phone. To carry progress across, open **Plan**, copy the progress code in one version, and load it in the other.

## Updating the app

When the files on `gh-pages` change, the app picks up the new version the next time you open it with internet.
