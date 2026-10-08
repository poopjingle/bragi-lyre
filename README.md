# Lyre Offerings to Bragi: Android app

This folder is the installable version of your practice app. It has everything the Claude version has, plus a microphone tuner with a needle, and it works offline once installed. Your progress is stored on the phone.

## What's in the folder

| File | What it is |
| --- | --- |
| index.html | The app |
| manifest.webmanifest | Tells Android the app's name, icon and colors |
| sw.js | Lets the app open without internet |
| icon-*.png | App icons |

## Put it online (one time, about 10 minutes)

Android installs web apps from a web address, and the microphone needs a secure (https) address. GitHub Pages hosts this for free.

1. Sign in at github.com, or create a free account.
2. Click **New repository**. Name it `bragi-lyre`, choose **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**. Drag in every file from this folder (the files, not the folder itself). Click **Commit changes**.
4. Open the repository's **Settings**, then **Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and **/(root)**, and click **Save**.
5. Wait a minute or two. Your app's address will be `https://YOUR-USERNAME.github.io/bragi-lyre/`.

Note: a public repository means anyone with the address could open the practice plan. Your progress never leaves your phone.

## Install it on your Android phone

1. Open the address in **Chrome**.
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

If you replace any file in the repository later, the app picks up the change the next time you open it with internet.
