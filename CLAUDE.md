# stealer-releases

The public download page of Stealer. It holds no code: only this README and the GitHub releases.

## How releases get here

- The code lives in the private `robertoattanasio/stealer` repository.
- Its `npm run release` builds the Windows installer, creates the draft release `v<version>` here, and uploads `Stealer-setup.exe` with the update files.
- The draft is published by hand from GitHub.
- Installed apps update themselves from the latest published release here, through `electron-updater`.

## README

- Written for people who download the app, not for developers.
- The download link points to `releases/latest/download/Stealer-setup.exe`: the installer name must stay the same.
