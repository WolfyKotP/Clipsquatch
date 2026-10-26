# Clipsquatch

A lightweight clip recorder and screenshot tool for Windows: an always-on replay buffer that
saves the last moments of your game with one key, plus screenshots, uploads and an editor.

This page only hosts the installers. Get the newest one from
**[Releases](https://github.com/WolfyKotP/Clipsquatch/releases/latest)**.

## Install

1. Download `Clipsquatch_x.y.z_x64-setup.exe` from the latest release.
2. Run it. Windows may say **"Windows protected your PC"** because the installer isn't code
   signed by a paid certificate: click **More info**, then **Run anyway**.
3. Clipsquatch starts in the tray. Launch a game and press **Alt + \\** to save a clip.

Needs Windows 10 or 11 (64-bit). Everything it needs is in the installer.

## Updates

Clipsquatch checks for new versions by itself. When one is out, an **Update** button appears at
the top of the app: click it and it downloads, installs and restarts.

Every update is signed. The app checks the signature before installing anything and refuses a
download that wasn't signed with Clipsquatch's own key.

## Your data

Settings, API keys and your library details stay on your PC (`%APPDATA%\Clipsquatch`). Clips are
only uploaded when you choose to, to the host you pick. The app talks to GitHub only to check
for updates.

## Found a problem?

Open an [issue](https://github.com/WolfyKotP/Clipsquatch/issues) with what you did, what you
expected and what happened. Settings, General, **Open data folder** has `clipsquatch.log`,
which helps a lot (check it for anything private before sharing).
