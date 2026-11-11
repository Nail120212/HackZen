<div align="center">
  <img src="logo.png" alt="HackZen logo" width="152" />
  <h1>HackZen</h1>
  <p><strong>More control. Less menu hunting.</strong></p>
  <p>A Geometry Dash utility menu with practice tools, level controls, bots, AI learning, and a clean themed UI.</p>
  <p>
    <a href="https://geode-sdk.org/install"><img src="https://img.shields.io/badge/INSTALL-GEODE-7c5cff?style=for-the-badge&labelColor=11131a" alt="Install Geode" /></a>
    <a href="https://github.com/Nail120212/HackZen/releases/tag/v2.6.0-alpha"><img src="https://img.shields.io/badge/DOWNLOAD-v2.6--alpha-25d695?style=for-the-badge&labelColor=11131a" alt="Download HackZen v2.6 Alpha" /></a>
    <img src="https://img.shields.io/badge/GEODE-5.11.2-f5c451?style=for-the-badge&labelColor=11131a" alt="Geode 5.11.2" />
  </p>
</div>

> **HackZen v2.6 Alpha is an install-only release.** This public repository contains documentation, artwork, notices, and release links only. No implementation source or source archive is published here.

HackZen puts everyday Geometry Dash tools behind one draggable logo. v2.6 replaces the old online AI model flow with a private, offline learning engine. It watches your play, turns nearby geometry into a compact vision grid, and trains a small on-device brain while keeping the same Level, Tools, Effects, and tips-bubble improvements.

## Install

### Recommended: Geode’s mod browser

1. Install [Geode](https://geode-sdk.org/install) for your Geometry Dash version.
2. Open Geometry Dash and tap the Geode button on the main menu.
3. Search for HackZen in the **Download** tab when the listing is available.
4. Install HackZen and restart the game if Geode asks you to.

### Manual: release package

1. Install Geode first.
2. Download [`ian.hackzen.geode`](https://github.com/Nail120212/HackZen/releases/tag/v2.6.0-alpha).
3. Put the `.geode` file in your Geometry Dash `geode/mods` folder.
4. Launch the game and tap the round HackZen logo.

Geode’s [official FAQ](https://geode-sdk.org/faq) documents both the in-game mod browser and manual `.geode` installation. If a mod prevents startup, use Geode Safe Mode to launch without mods and disable it.

> **Fresh-install note:** v2.6 changes the Geode mod ID to `ian.hackzen`. Older settings under `ianangelo.cheatmenu` are not migrated automatically.

## v2.6 at a glance

<div align="center">
  <img src="resources/icon-home.png" alt="Main" width="44" />
  <img src="resources/icon-user.png" alt="Player" width="44" />
  <img src="resources/icon-layers.png" alt="Level" width="44" />
  <img src="resources/icon-wrench.png" alt="Tools" width="44" />
  <img src="resources/icon-bot.png" alt="Bots" width="44" />
  <img src="resources/icon-ellipsis.png" alt="Misc" width="44" />
  <img src="resources/icon-settings.png" alt="Settings" width="44" />
</div>

- **Main** — Cheats, Speed, Click
- **Player** — Respawn, Practice, Visuals, Effects
- **Level** — Visual, Gameplay, Pause
- **Tools** — Bypass, Creator, Global
- **Bots** — Bot, AI, Vision, Learn, Models
- **Misc** — Tools, About
- **Settings** — HUD, Labels, Theme, Options, Icon

## Features, one by one

<details open>
<summary><strong>Main → Cheats, Speed, Click</strong></summary>

- **Noclip** — Test routes without normal collision stopping the run.
- **Infinite Jump** — Add extra jump control while experimenting.
- **Safe Mode** — Keep assisted gameplay clearly separated from ordinary play.
- **Unlock Icons** — Preview locked icon options locally.
- **Auto Kill** — End a run at a chosen percentage.
- **Noclip Accuracy Limit** — Stop an assisted run below a selected accuracy threshold.
- **Speedhack** — Slow down for practice or speed up for testing.
- **FPS Cap** — Cycle through Off, 60, 120, 144, 240, and 360.
- **Swift Click** — Repeat jump input at a chosen CPS while holding.
- **Auto Click** — Configure hold and release timing.

</details>

<details>
<summary><strong>Player → Respawn, Practice, Visuals, Effects</strong></summary>

- **Instant Restart** — Restart without the normal death delay.
- **Respawn Delay** — Add a controlled delay when instant restart feels too fast.
- **Confirm Restart / Exit** — Prevent accidental actions.
- **Auto Practice** — Start levels in Practice Mode automatically.
- **0% Practice Completion** — Keep practice completion at the starting point.
- **Practice Coins** — Assist with practice coin handling.
- **Show Hitboxes** — Inspect collision areas.
- **Hide UI** — Reduce screen noise.
- **No Death Effect** — Keep repeated attempts readable.
- **No Ghost Trail / No Trail** — Remove visual trails.
- **Always Show Trail / Solid Wave Trail** — Keep trail visuals consistent.
- **No Hide Trigger** — Prevent hide-trigger visual changes.
- **No Robot Fire / No Spider Dash** — Remove selected player effects.
- **No Platformer Jump Animation** — Reduce the platformer jump animation.
- **Mute Death Audio** — Control reward and level audio after death.

</details>

<details>
<summary><strong>Level → Visual, Gameplay, Pause</strong></summary>

- **No Mirror / Instant Mirror** — Control mirror-mode behavior.
- **No Object Glow / No Shaders** — Reduce distracting effects.
- **No Portal Lightning / No Misc. Particles** — Simplify level visuals.
- **Hide Level Complete VFX** — Keep the finish screen cleaner.
- **Show Triggers** — Make trigger objects visible while testing.
- **Always Show Coins** — Keep coins visible.
- **Auto Pickup Coins** — Assist with coin collection.
- **Auto LDM** — Apply low-detail behavior automatically.
- **Auto Song Download** — Manage song availability automatically.
- **Force Platformer** — Force platformer behavior for testing.
- **Freeze Attempts** — Prevent attempt count changes.
- **Stop Triggers On Death** — Stop trigger activity after death.
- **Mute Level SFX** — Silence level sound effects.
- **Random Seed** — Control randomized level behavior.
- **Accurate Percentage** — Improve displayed progress precision.
- **Pause Countdown / Pause During Complete** — Tune pause and completion behavior.

</details>

<details>
<summary><strong>Tools → Bypass, Creator, Global</strong></summary>

- **Character Filter Bypass** — Relax selected character filtering in creator tools.
- **Character Limit Bypass** — Work with larger character counts.
- **Custom Object Bypass** — Relax selected custom-object restrictions.
- **Level Copy Bypass** — Assist with copying levels.
- **No (C) Mark / No Short Numbers** — Adjust selected editor and display markings.
- **Compact Editor Levels** — Reduce editor list clutter.
- **Hide Editor UI** — Clear extra editor interface elements.
- **Free Scroll** — Improve editor navigation freedom.
- **Creator utilities** — Keep level-building helpers grouped away from gameplay controls.
- **Global utilities** — Apply supported settings across the game instead of one level at a time.

These controls are intended for testing, creation, and local experimentation. Availability can vary by Geometry Dash build.

</details>

<details>
<summary><strong>Bots → Bot, AI, Vision, Learn, Models</strong></summary>

- **Record / Replay** — Capture and replay inputs for a level.
- **Save / Folder / Auto Save** — Manage local macros.
- **Engine Play** — Let the local learning engine play after it has learned enough.
- **Reflex Assist** — React locally to nearby hazards while a model plans ahead.
- **AI Vision** — Scan nearby blocks and hazards with sensor rays.
- **Vision overlay** — Show clear paths, blocks, hazards, planned jumps, and status.
- **Watch & Learn** — Observe your own play and train from your real inputs.
- **Learn From Own Play** — Improve from survived engine actions and classify deaths as early, late, or missed jumps.
- **Brain** — Train a compact 152 → 96 → 48 → 1 neural network locally on the device.
- **Train now / Save brain / Reset brain** — Control training without leaving the menu.
- **Show Grid** — Display the occupancy grid used by the learning engine.
- **Reflex fallback** — Use the local spike reflex until the brain has enough samples.

The v2.6 brain stores its data locally in `ai/brain.bin`. No provider key, model download, or internet connection is required. Moves immediately before a death are discarded instead of being copied as good training examples.

</details>

<details>
<summary><strong>Misc and Settings</strong></summary>

- **Pause In Menu** — Pause gameplay, music, effects, and the HUD timer while HackZen is open.
- **Reset Music / SFX Volume** — Restore audio levels to 100%.
- **Reset All** — Reset HackZen settings while keeping provider credentials and model choices.
- **Tips bubble** — Read short contextual explanations for tabs and switches.
- **HUD** — FPS, clock, timer, deaths, hits, accuracy, frames, best percentage, CPS, progress, level name, and attempts.
- **Labels** — Show cheat, speed, AI, and bot status.
- **Themes** — Classic, Crimson, Blurple, Noir, or Custom Gradient.
- **Options** — Glassy mode, light animations, sidebar icons, outline glow, menu opacity, and scale.
- **Floating icon** — Drag the round logo to move it; tap it to open the menu.
- **Icon controls** — Show, hide, auto-hide, or lock the logo.

</details>

## AI privacy

The v2.6 learning engine is local and offline. Gameplay state, occupancy-grid features, training samples, and the saved brain remain in the mod save directory. HackZen does not send gameplay data to a model provider and does not require API keys for its learning features.

HackZen does not include a remote account system or public telemetry service. It is not affiliated with RobTop Games, Geometry Dash, Geode, or Eclipse Menu.

## Compatibility

- Geometry Dash target: **2.2081**
- Geode SDK build: **5.11.2**
- Release: **v2.6 Alpha**
- Geode mod ID: **`ian.hackzen`**

Geode notes that major Geometry Dash updates can require a Geode update. Check the [official Geode install page](https://geode-sdk.org/install) before updating the game.

## Notices and public repository policy

Parts of the private implementation are adapted from [Eclipse Menu](https://github.com/EclipseMenu/EclipseMenu) under the Eclipse Public License 2.0. The attribution and license text are included in this public repository’s notice files.

This repository is the public HackZen landing page. It contains documentation, artwork, notices, and release links only. The implementation source and build repository are private. Do not redistribute, repackage, or claim the mod as your own.

<div align="center">
  <img src="resources/icon-hackzen.png" alt="HackZen round icon" width="96" />
  <br />
  <sub>HackZen — stay cracked, stay zen.</sub>
</div>
