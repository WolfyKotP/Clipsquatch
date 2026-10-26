# Clipsquatch guide

Everything you need, from installing to sharing. New here? Read **1** and **2**, that's enough to start. The rest is there when you need it.

**Contents**

1. [Install](#1-install)
2. [Your first clip](#2-your-first-clip)
3. [Saving clips](#3-saving-clips)
4. [The library](#4-the-library)
5. [Albums](#5-albums)
6. [Editing a clip](#6-editing-a-clip)
7. [Screenshots and capture tools](#7-screenshots-and-capture-tools)
8. [Uploading and sharing](#8-uploading-and-sharing)
9. [Storage and tidying up](#9-storage-and-tidying-up)
10. [Settings](#10-settings)
11. [Updates](#11-updates)
12. [Something not working?](#12-something-not-working)
13. [Your data and uninstalling](#13-your-data-and-uninstalling)

---

## 1. Install

1. Go to **[Releases](https://github.com/WolfyKotP/Clipsquatch/releases/latest)** and download **`Clipsquatch_x.y.z_x64-setup.exe`** (the numbers are the version). You don't need the `.sig` file; that's for the app's own update checks.
2. Run it.
3. Windows may show **"Windows protected your PC"**. That's because the installer isn't signed with a paid certificate, not because anything is wrong. Click **More info**, then **Run anyway**.
4. Clipsquatch opens. It also puts a green icon in the system tray (bottom right, next to the clock; you may need the **^** arrow to see it). Closing the window keeps Clipsquatch running in the tray, which is what lets it record in the background.

Needs Windows 10 or 11, 64-bit. Everything it needs is in the installer.

> **Antivirus:** a new app that watches the screen and listens for hotkeys can make some antivirus tools nervous. If yours blocks Clipsquatch, allow it there.

---

## 2. Your first clip

1. **Start a game.** Out of the box Clipsquatch records only while a game is running (the box at the top left says *Recording* and the game's name). Not detected? See [Games](#games-not-detected).
2. **Play.** Clipsquatch quietly keeps the last few minutes in memory. Nothing is saved yet.
3. Something good happens: press **Alt + \\** (Alt and the backslash key). The last **30 seconds** are saved as a clip, with a sound and a little popup in the corner.
4. Open Clipsquatch (click the tray icon). Your clip is at the top of **Clips**.

That's it. Everything below is extra.

---

## 3. Saving clips

### Clip keys

| Key | What it does |
|---|---|
| **Alt + \\** | Save the last 30 seconds (change the length in Settings → Recording) |
| **Alt + Shift + \\** | Save the last 3 minutes (a second length) |
| **Alt + ]** | Bookmark this moment: it shows as a marker on the clip's timeline |
| **Alt + [** | Start a full session; press again to save the whole session as one video |

You can add a **third and fourth clip length**, **Clip and share** (save, upload and copy the link in one go) and **Privacy pause** (stop recording instantly, e.g. while you type a password) in **Settings → Hotkeys**. Any key or combination works: click the box, press the keys.

### When it records

**Settings → Recording → When to record**:

- **Games only** (default): starts by itself when a game runs and stops when it closes.
- **Always**: records the desktop all the time.
- **Manual**: only when you press **Start recording**.

**What to record**: *Game window* (only the game, so alt-tabbing never shows your desktop) or *Whole display*.

### Clips never overlap

Press the clip key twice a minute apart and the second clip holds just the new minute, not the same footage again. Clips that follow on from each other show **⛓ linked**: select them and press **Join seamlessly** to make one continuous video with no gap.

### Sound

Game sound and your microphone are both recorded, and the game also gets its own separate track so you can turn your voice down later. Change it in **Settings → Audio**.

---

## 4. The library

The sidebar has **Clips**, **Screenshots**, **Albums**, **Uploads** and **Storage**.

- **Click** a clip to open it in the editor. **Hover** over it to scrub through it.
- **★** stars a clip. Starred clips are never removed by clean-ups.
- **Search** finds clips by name, game, tag, note and (if turned on) what was said in them.
- The chips under the title filter by game, tag or starred.
- **☁ Uploaded** shows only what you've uploaded.

### Quick search

Press **Ctrl + K** anywhere in the app. Type to jump to any clip, album or setting, or to run an action like *New album* or *Clear cache*.

### Selecting many

1. Press **Select**.
2. Click clips to pick them. **Shift + click** picks everything between two clicks. **Select all** picks everything in the current view.
3. The bar at the bottom can **Star**, **Tag**, **Delete**, **Add to album**, **Join seamlessly**, **Make montage** or make a **Share page**.

**Deleting** sends files to the Recycle Bin and shows an **Undo** button for 10 seconds that brings them back with their stars, tags and albums. When some of them are uploaded, you can keep their online copies, or delete them from your account too (Fivemanage and Streamable).

### Notes at a moment

In the editor, **+ Note at this moment** writes a note at the playhead ("1:32 the crash"). Notes show on the timeline, and you can click one to jump there. They're searchable too.

### Other folders

**Settings → Storage → Other folders to show** adds the videos and pictures of another folder (old recordings, a phone backup) to the library. Nothing is moved or copied.

---

## 5. Albums

Albums collect clips and screenshots together. Nothing is moved or copied, so a clip can be in several albums.

1. **Albums** in the sidebar → **New album**, or select clips in the library and press **Add to album…**
2. Open an album to see what's in it. The bar at the top can **Share as a page**, **Rename** or **Delete album** (deleting an album never deletes its clips).
3. To take things out: open the album, **Select**, pick them, **Remove from album**.

**Auto-album rules** (Albums → *Auto-album rules…*) file clips for you, for example *"Clips I star from FiveM → Best of FiveM"* or *"Every clip I save → Everything"*.

**Album pages:** *Share as a page* makes one public page for the album. It keeps the same link and updates by itself when you add uploaded clips to the album or take them out.

---

## 6. Editing a clip

Click a clip to open the editor.

- **Trim:** drag the start and end handles under the video, then **Export** (as a new file, or replacing the original).
- **Bookmarks:** **B** adds or removes one at the playhead, **[** and **]** jump between them. *Cut a clip at each bookmark* makes short clips around them; *Find loud moments* bookmarks gunfire, shouting and laughs.
- **Sections:** slow-motion and speed-ups, zoom, freeze frames, blur an area, mute or bleep audio, sound effects.
- **Captions** from what's said, a **watermark**, and **presets** for sizes such as vertical videos for phones.
- **GIF**, **Montage** (several clips with transitions, titles and music) and **Best of…** (your starred clips from a stretch of time).

Once a week Clipsquatch offers to turn last week's starred clips into a **highlights reel**. Nothing is made unless you say so.

---

## 7. Screenshots and capture tools

The **Capture** tiles in the sidebar (and the tray menu) do the lot. Each one can have a key in **Settings → Hotkeys**; they're off until you set one.

| Tool | What it does |
|---|---|
| **Area** | Drag a box, or click a window, to screenshot it |
| **Window** | Screenshot the window you click |
| **Screen** | Screenshot the screen the mouse is on |
| **Upload** | Screenshot an area, upload it and copy the link |
| **Record** | Record an area or window as a video or GIF; press again to stop |
| **Colour** | Pick a colour from the screen and copy its code |
| **Text** | Copy text from the screen (works offline) |
| **QR code** | Read a QR code on the screen |
| **Pin** | Keep a picture of an area floating on top of everything |

After a screenshot it's **copied** (ready to paste) and saved in **Screenshots**. In **Settings → Screenshots** you can also have it open to draw on, or upload it straight away.

**Drawing on a screenshot:** open it from the library. Arrows, boxes, text, highlighter, blur, numbered steps, pen and crop. Then **Save**, **Copy** or **Upload**.

### Temporary screenshots

For throwaway shots: **Settings → Screenshots → Only keep until restart**, or give **Temporary screenshot of an area** its own key. They show in the library marked **TEMPORARY** and disappear when Clipsquatch restarts. Press **Keep** in the picture editor to save one for good.

---

## 8. Uploading and sharing

### Upload a clip or screenshot

Press **Upload & get link** on a clip (or the link icon on its card). The link is copied, ready to paste into Discord or a chat. Big clips are made smaller first so they fit.

Where things go is set in **Settings → Uploads**:

- **Clips:** catbox.moe (permanent), Litterbox (72 hours), Streamable or Fivemanage (your own accounts, where you can delete them from Clipsquatch too).
- **Screenshots:** a choice of hosts, several needing no account.

Hosts that use your own account need their key or login in **Settings → Accounts**. Each one there shows *Connected* or *Not set up*, with how to get the key.

### The Uploads page

Everything you've uploaded, newest first, in one list. **Open**, **Check** (is it still online?), **Delete** (from your account where the host allows it, or opens the host's delete page), and **Check all links** to tidy away dead ones.

### Online only

When deleting an uploaded clip you can **keep the online copy**: the file leaves your PC but stays in the library as *online only*. Clicking it plays it inside Clipsquatch, full screen, straight from the host. **Save to this PC** brings it back.

### Share pages

Select clips and screenshots → **Share page** makes one public page with all of them that works on phones, and Discord shows a preview of it. Anything not uploaded yet is uploaded first. Your pages are listed on the Uploads page, with *Take down*.

### Discord

Paste a Discord webhook in **Settings → Accounts** (Discord: Server Settings → Integrations → Webhooks → New Webhook → Copy URL). Then links can be posted straight to a channel.

### Auto-upload

**Settings → Uploads → Upload clips automatically**: every clip you save, or every clip you star, optionally only for some games and also posted to Discord. Off unless you turn it on.

### Bringing in uploads from before

On the **Uploads** page or the Screenshots tab, use **Import links**:

- Paste links (page links or direct links, mixed with other text is fine).
- Paste a **vgy.me album** link to bring in a whole album.
- Pick a history file from another uploader.
- **Sync my files** brings in everything on your Fivemanage account.

Nothing is downloaded: they show as online-only cards, each fetching a small thumbnail when you scroll to it.

---

## 9. Storage and tidying up

The **Storage** page shows space used, free space on the drive, and space by game and by month. From there:

- **Free up space:** unstarred clips older than a set age, from one game or all. **Delete them** (Recycle Bin) or **Move to the cloud** (uploaded, then removed from your PC but kept in the library as online only).
- **Biggest files:** your ten largest.
- **Find duplicates:** copies of the same file and the same screenshot saved twice are ticked for you. Look-alikes and clips that share footage are listed for you to judge.
- **Clear cache:** thumbnails, waveforms and other files Clipsquatch makes again whenever needed. It never touches your clips, settings or uploads.

**Automatic clean-up** (Settings → Storage) can keep the clips folder under a size, or remove clips after a number of days. Starred clips are always kept, and it's off unless you turn it on.

**Backup** (Settings → General → Back up) saves your settings, stars, tags, notes, albums and upload links to one file. Keep it somewhere safe; **Restore** brings it back after reinstalling or on a new PC. The clips themselves aren't in it; copy your clips folder for those.

---

## 10. Settings

- **Simple / All settings** (top right): Simple shows the settings most people change. The search box always looks through everything.
- **Accounts:** every login and key in one place.
- A **dot** marks anything changed from the default; hover the row for **↺** to put it back.
- Long explanations show their first line; **?** opens the rest.

Your clips go to **Videos\Clipsquatch** unless you choose another folder (Settings → Storage). Each game gets its own folder inside it.

---

## 11. Updates

Clipsquatch checks for new versions by itself. When one is out, an **Update** button appears at the top: click it, and it downloads, installs and restarts in a few seconds. You can also check in **Settings → General → Updates**.

Every update is signed. Clipsquatch checks the signature before installing and refuses anything that wasn't signed with its own key.

---

## 12. Something not working?

### The clip key does nothing

- Is it recording? The box at the top left must say *Recording*. With *Games only*, it waits for a game.
- **"Alt + \\ is already used by another app"**: another program has that key. Pick a different one in Settings → Hotkeys.

### Games not detected

Add the game in **Settings → Games → Extra games** (the name of its `.exe`), or set *When to record* to **Always**.

### "Recording keeps failing"

Restart Clipsquatch from the tray (right click → Quit, then open it again). If it keeps happening, send feedback (below).

### Clips are blurry or too big

Settings → Recording → **Quality** (Balanced is a good start), **Clip resolution** and **Frame rate**.

### Send feedback

**Settings → General → Send feedback**. Write what happened, then **Copy report** or **Save as a file**, and send it over, or open an [issue](https://github.com/WolfyKotP/Clipsquatch/issues). The report has the app version and the end of its logs; keys, logins and your Windows user name are left out.

---

## 13. Your data and uninstalling

- **Clips:** your clips folder (Videos\Clipsquatch by default).
- **Settings, stars, tags, albums, upload links:** `%APPDATA%\Clipsquatch`
- **Temporary files and the replay buffer:** `%LOCALAPPDATA%\dev.clipsquatch.app` (safe to clear; Clipsquatch makes them again)

Nothing is uploaded unless you upload it, to the host you choose. Clipsquatch only contacts GitHub to check for updates.

**Uninstall** from Windows Settings → Apps → Installed apps → Clipsquatch. Your clips are kept. The uninstaller asks whether to delete the app data as well.
