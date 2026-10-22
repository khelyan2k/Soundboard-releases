# Soundboard

[Français](README.md) · **English**

Soundboard is a free Windows app that plays sounds into Discord, your games and any app that uses a microphone. Your voice, your PC audio and your sounds go out together through a virtual microphone, and you hear everything in your headphones.

**[⬇ Download the latest version](https://github.com/khelyan2k/Soundboard-releases/releases/latest)**

> The app itself is in French for now. This guide uses the French names of buttons and pages, with their meaning in brackets.

---

## Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Setting up Discord (or a game)](#setting-up-discord-or-a-game)
- [Features](#features)
- [Updates](#updates)
- [Uninstalling](#uninstalling)
- [FAQ](#faq)
- [Privacy](#privacy)

## Requirements

- Windows 10 (version 2004 or later) or Windows 11, 64-bit.
- **VB-CABLE**, the free virtual microphone by VB-Audio. No need to look for it: Soundboard offers to install it for you on first launch.

## Installation

1. Open the [releases page](https://github.com/khelyan2k/Soundboard-releases/releases/latest) and download `Soundboard_X.Y.Z_x64-setup.exe` (under **Assets**).
2. Run it. Windows may show "Windows protected your PC": that's normal for a small app without a paid certificate yet. Click **More info**, then **Run anyway**.
3. Follow the installer. It doesn't need administrator rights and creates Desktop and Start menu shortcuts.
4. On first launch, if VB-CABLE isn't there yet, a banner offers **Installer VB-CABLE** (install VB-CABLE):
   - Soundboard downloads the official pack from vb-audio.com and Windows checks its signature;
   - Windows asks for administrator permission (it's an audio driver);
   - in VB-Audio's window, click **Install Driver**;
   - restart your PC if VB-Audio asks you to.
5. You're set. The virtual microphone shows up in Windows as **Soundboard MIC**.

## Setting up Discord (or a game)

1. In Discord: **User Settings** → **Voice & Video**.
2. **Input Device**: pick **Soundboard MIC (VB-Audio Virtual Cable)**.
3. Keep your usual headphones as **Output Device**.
4. In Soundboard, open **Mixage** (mixer) → **Ton micro** (your mic) and pick your real microphone: your voice goes through Soundboard along with the sounds.

Same idea for a game or any other app: pick **Soundboard MIC** as the microphone.

> If Discord cuts or garbles the sounds, turn off its **Noise Suppression** (Krisp) and, if needed, its **Echo Cancellation**: they take music and effects for background noise.

## Features

The app has five pages: **Sons** (sounds), **Mixage** (mixer), **Paramètres** (settings), **Nouveautés** (what's new) and **À propos** (about).

### Your sounds

- Import sounds with the **Importer** button or by dropping them on the window: MP3, WAV, OGG, FLAC, M4A/AAC and AIFF, as many as you want.
- Sort them into categories with your own colors, and find them with the search box.
- Each sound has its own volume (up to 200%), on top of the master volume.
- Several sounds can play at once. When you click a sound that's already playing, you choose whether it restarts, layers on top or stops.
- **Esc** stops everything.

### Player

- Pause and resume where you left off, and a position bar to jump around in the sound.
- Speed from ×0.5 to ×2, adjustable while playing.
- Your choice: the voice keeps its pitch, or gets higher when sped up (and lower when slowed down), like a record.
- Each sound can have its own default speed.

### Your microphone

- Your real mic is mixed with the sounds: Discord gets your voice and the sounds at the same time, with no extra Windows setup.
- Volume, mute button, and a hotkey to mute or unmute.
- **Push-to-talk** on the key of your choice. Sounds always go through.
- Adjustable **noise gate** with a level meter, to cut keyboard and fan noise when you're not talking.

### PC audio

- Send **all of your PC's audio** into the virtual mic, like a stream: music, videos, games.
- Or **only the apps you pick**, among every app that's open. An advanced picker also lets you grab a background program.
- Optional **echo guard**: Discord, plus any apps you add to the list, are left out so people in the call don't hear themselves.
- Separate volume, so music doesn't drown out your voice.

### Mixer

- One channel strip per source (sounds, mic, PC audio) and per output, with live level meters.
- Two outputs, each with its own volume and on/off switch: the **virtual mic** (what Discord hears) and the **headphone monitor** (what you hear).
- In your headphones you can also hear your voice and PC audio: exactly what Discord gets, or all of your PC's audio.
- A **limiter** on each output: no clipping, even with the volume pushed up.
- **Mix profiles** ("Game", "Stream"…) you can switch with one click or a hotkey.

### Hotkeys

- One hotkey per sound, one to stop everything, and more for the mic and profiles.
- Single keys, Ctrl/Alt/Shift combinations, numpad, F13 to F24, side mouse buttons and the mouse wheel.
- They work in-game without blocking the key in the game.

### Everyday use

- Closing the window doesn't quit the app: it stays next to the clock, with a menu to stop everything, turn hotkeys off or quit.
- Option to start Soundboard with Windows, minimized.
- The virtual mic is renamed **Soundboard MIC** automatically, and the useless "CABLE In 16ch" device is hidden.
- Adjustable interface size (100% by default) or automatic based on your screen.
- The **Nouveautés** page lists what changed in each version.

## Updates

Soundboard checks for updates on launch and then every 6 hours. When a new version is out, a banner offers it: one click and it installs itself. You can also check manually in **À propos**.

Your sounds, categories and settings are kept. Every update is signed: the app refuses any file that doesn't come from this repository.

## Uninstalling

1. **Windows Settings** → **Apps** → **Installed apps** → **Soundboard** → **Uninstall**.
2. Tick the option to delete the app data if you also want to erase your sounds and settings.
3. A window offers to **remove VB-CABLE** too. Windows asks for administrator permission, and a restart may be needed for it to disappear completely. Answer **No** if another app uses it.

## FAQ

**My friends can't hear the sounds.**
Make sure Discord uses **Soundboard MIC** as its input device, and that the **virtual mic** switch is on in **Mixage**. Also turn off Discord's noise suppression.

**I can't hear the sounds in my headphones.**
In **Mixage**, turn on the **headphone monitor** and check the selected device.

**The app says VB-CABLE isn't installed.**
Start the installation from the banner, click **Install Driver** in VB-Audio's window, then restart your PC if asked.

**People in the call hear themselves when I send PC audio.**
Turn on the **echo guard** in the **Son du PC** (PC audio) card, or only send the apps you pick.

**A hotkey doesn't work in a game.**
Check that the game or another app isn't already using it. If the game runs as administrator, Windows keeps normal apps from seeing its keys: run Soundboard as administrator too.

**Windows blocked the installer.**
That's SmartScreen: **More info** → **Run anyway**.

## Privacy

Soundboard runs entirely on your PC. It collects nothing, has no account, and sends your sounds and voice nowhere but the virtual mic. It only goes online to check for updates on this repository and, when you ask, to download VB-CABLE from vb-audio.com.

---

VB-CABLE is made by VB-Audio Software (donationware) and downloaded from [their official website](https://vb-audio.com/Cable/). Soundboard is not affiliated with VB-Audio or Discord.
