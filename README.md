<div align="center">
  <img src="logo.png" alt="HackZen logo" width="150" />
  <h1>HackZen</h1>
  <p><strong>Geometry Dash, but make it zen.</strong></p>
  <p>Clean tools. Smooth UI. Zero boring menus.</p>
  <p>
    <a href="https://geode-sdk.org/install"><img src="https://img.shields.io/badge/Install-Geode-7c5cff?style=for-the-badge" alt="Install Geode" /></a>
    <a href="https://github.com/Nail120212/HackZen/releases"><img src="https://img.shields.io/badge/Download-HackZen-25d695?style=for-the-badge" alt="Download HackZen" /></a>
    <img src="https://img.shields.io/badge/version-v2.0.0--alpha-f5c451?style=for-the-badge" alt="HackZen v2.0 Alpha" />
  </p>
</div>

HackZen is a themeable Geometry Dash mod menu with a draggable round logo, fast practice tools, replay bots, Groq/OpenRouter AI autoplay, HUD controls, custom themes, and a whole lot of tiny quality-of-life wins.

> **Alpha heads-up:** HackZen v2.0 is still being tuned. Back up your settings, expect a few rough edges, and do not use gameplay-changing tools for legitimate leaderboard submissions.

## Install in two minutes

1. Install [Geode](https://geode-sdk.org/install) for your Geometry Dash version.
2. Open the [HackZen Releases page](https://github.com/Nail120212/HackZen/releases).
3. Download `ianangelo.cheatmenu.geode` from the latest release.
4. Drop it into your Geode `mods` folder.
5. Launch Geometry Dash and tap the round HackZen logo in a level.

No compiler. No SDK setup. No source archive. Just install Geode, drop in HackZen, and play.

## The v2.0 layout

HackZen keeps things simple: five big tabs on the left, quick sub-tabs across the top, and the controls where you actually expect them.

- **Main** — Cheats, Speed, and Click.
- **Player** — Respawn, Practice, and Visuals.
- **Bots** — Bot, AI, and Models.
- **Misc** — Tools and About.
- **Settings** — HUD, Labels, Theme, Options, and Icon.

## Features, explained one by one

### Main → Cheats

- **Noclip** — Ignore collision so you can test a route without instantly exploding.
- **Infinite Jump** — Jump again when you need a little extra control.
- **Safe Mode** — Keeps assisted completions marked as practice-style activity.
- **Unlock Icons** — Lets you preview and use locked icon options locally.
- **Auto Kill** — Ends the run at your chosen percentage when enabled.
- **Noclip Acc Limit** — Stops a noclip run when accuracy drops under your limit.
- **Show Hitboxes** — Makes collision boxes visible for testing tight timings.
- **No Death Effect** — Removes the death effect clutter.
- **Noclip Flash** — Adds a visual signal when noclip blocks a hit.
- **Hide UI** — Clears extra interface elements for a cleaner view.

### Main → Speed

- **Speedhack** — Adjust the game speed from slow practice pacing to faster testing.
- **Only In Levels** — Keeps speed changes out of menus and non-level screens.
- **Presets** — Jump between common speed values instead of dragging forever.
- **FPS Cap** — Cycle through Off, 60, 120, 144, 240, and 360 FPS targets.

### Main → Click

- **Swift Click** — Hold the screen and let HackZen repeat jump input at your chosen CPS.
- **Auto Click** — Set a hold timer and release timer for repeat input without button mashing.

### Player → Respawn

- **Instant Restart** — Restart immediately instead of waiting through the normal death delay.
- **Respawn Delay** — Add a small delay when instant restart feels too aggressive.
- **Confirm Restart** — Ask before restarting so accidental taps do not wipe a run.
- **Confirm Exit** — Ask before leaving a level.

### Player → Practice

- **Auto Practice** — Automatically start levels in Practice Mode.
- **Checkpoint tools** — Add checkpoints while Practice Mode is active.
- **Restart / Practice shortcuts** — Get the common practice actions without hunting through menus.
- **Reset Stats** — Clear the current run statistics when you want a fresh test.

### Player → Visuals

- **Show Hitboxes** — Keep collision data visible while testing.
- **Hide UI** — Reduce screen noise.
- **No Death Effect** — Keep the screen readable during repeated attempts.
- **Noclip Flash** — See exactly when a collision was blocked.

### Bots → Bot

- **Record** — Capture your inputs for the current level.
- **Replay** — Play the saved macro back automatically.
- **Stop** — End recording or playback immediately.
- **Clear** — Remove the current macro.
- **Save** — Store one replay file per level name.
- **Folder** — Open or view the folder where macros live.
- **Auto Save** — Save recordings automatically when the level ends.

### Bots → AI

- **Groq support** — Use a Groq API key and let a chat model plan gameplay actions.
- **OpenRouter support** — Use OpenRouter models as an alternative provider.
- **Provider switcher** — Pick Groq or OpenRouter without changing the menu.
- **Reflex Assist** — React locally to nearby hazards while the model plans ahead.
- **Non-blocking planning** — The level keeps running while the next AI plan is generated.
- **Paste / Test** — Paste your key and check the provider connection.
- **API-key privacy** — Keys stay in local mod save data; never post them in screenshots, issues, or commits.

AI mode uses your own provider quota. Groq keys start with `gsk_`; OpenRouter keys start with `sk-or-`. OpenRouter also supports a free-model-only filter.

### Bots → Models

- **Auto (fastest)** — Let HackZen choose a fast available chat model.
- **Live model list** — Load the models currently offered by your provider.
- **Model pages** — Browse long model lists without a giant dropdown.
- **Free-only filter** — Show OpenRouter models marked `:free`.
- **Custom model ID** — Type a model ID when you already know exactly what you want.
- **Fallback** — If a selected model disappears, HackZen switches back to Auto.

### Misc → Tools

- **Pause In Menu** — Pause gameplay, music, and effects while the menu is open.
- **Reset Music Vol** — Put music volume back to 100%.
- **Reset SFX Vol** — Put effects volume back to 100%.
- **Reset All** — Reset HackZen settings while keeping API keys and selected models.
- **Close button** — Always get back to the level quickly.

### Misc → About

- **Version info** — See the installed HackZen version.
- **Mod identity** — HackZen keeps the stable Geode ID `ianangelo.cheatmenu` so updates stay connected to the same install.
- **Quick help** — Read the basic logo, drag, AI, and practice reminders in-game.

### Settings → HUD

- **FPS** — Show current frames per second.
- **Clock** — Show the current clock.
- **Level Timer** — Track play time.
- **Deaths / Hits** — See deaths and blocked hits.
- **Accuracy** — Track noclip accuracy.
- **Frames** — Count frames during the run.
- **Best %** — Show your best progress.
- **CPS** — Display click speed.
- **Progress %** — Show level progress.
- **Level Name** — Show the current level name.
- **Attempts** — Show attempt count.

### Settings → Labels

- **Cheat Label** — Show a small assisted-gameplay status label.
- **Speed Label** — Show the active speed value.
- **AI / bot status** — See whether HackZen is recording, replaying, thinking, or using Reflex Assist.

### Settings → Theme

- **Classic** — The familiar Geometry Dash look.
- **Crimson** — Red-to-black energy.
- **Blurple** — Purple-to-blue glow.
- **Noir** — Black-to-white minimal mode.
- **Custom gradient** — Choose both gradient colors yourself.
- **Gradient direction** — Switch between horizontal, vertical, and diagonal.

### Settings → Options

- **Glassy** — Give panels a softer glass-like finish.
- **Light Animations** — Toggle the small UI movement effects.
- **Sidebar Icons** — Show or hide the left-side tab icons.
- **Outline Glow** — Add extra edge contrast around the menu.
- **Menu opacity** — Tune how transparent the menu feels.
- **Menu scale** — Make the whole interface smaller or larger.

### Settings → Icon

- **Show Icon** — Show or hide the round in-level logo.
- **Auto Hide Icon** — Fade it away when you are not using it.
- **Lock Icon** — Stop accidental dragging.
- **Hide Menu Button** — Hide the extra menu button when you want only the logo.
- **Pause In Menu** — Keep the pause behavior synced with the floating icon.
- **Drag to move** — Drag the round HackZen logo; tap it to open the menu.

## AI and privacy, no weird stuff

AI Autoplay is opt-in. HackZen sends approximate gameplay state and nearby object data to the provider you choose so it can request button actions. Your API key is stored in the mod's local save data and sent to that provider for authentication. Use a key you can revoke, keep your provider quota in mind, and do not share it publicly.

HackZen is not affiliated with RobTop Games, Geometry Dash, Geode, Groq, or OpenRouter.

## Compatibility

HackZen v2.0.0 Alpha targets Geometry Dash 2.2081 and is built with Geode SDK 5.11.2. Check the [Geode install page](https://geode-sdk.org/install) for current compatibility before updating the game.

## License and source availability

HackZen is distributed as an installable Geode package through GitHub Releases. This repository does not publish a source ZIP or an open-source license. Do not redistribute, repackage, or claim the mod as your own.

<div align="center">
  <img src="resources/icon-hackzen.png" alt="HackZen round icon" width="96" />
  <br />
  <sub>HackZen — stay cracked, stay zen.</sub>
</div>
