# pf1_for_sts2

A **Pathfinder 1e**-inspired mod for **Slay the Spire 2**.

It brings Pathfinder flavor into STS2: a Fighter-based mod with Pathfinder spells as cards
(Fireball, Acid Arrow, Black Tentacles, Disintegrate, Bull's Strength, and more), new powers and
relics (including a Kineticist with Kinetic Blast and a burn/infusion system), and dice-based
random damage and block.

- **Version:** 1.1.0
- **Languages:** English, Simplified Chinese (简体中文)
- **Affects gameplay:** yes

## Download

1. Open this repository on GitHub and click **Code → Download ZIP** (or clone it with git).
2. Extract the ZIP. You only need the **`pf`** folder, which contains:
   - `pf.dll`
   - `pf.pck`
   - `pf.json`

## Install

1. Find your Slay the Spire 2 install folder. In Steam: right-click the game →
   **Manage → Browse local files**.
2. If there's no `mods` folder there, create one.
3. Copy the whole `pf` folder into `mods`, so it looks like this:

   ```
   Slay the Spire 2/
   └── mods/
       └── pf/
           ├── pf.dll
           ├── pf.pck
           └── pf.json
   ```

4. Launch the game. The mod loads automatically.

## Update / Uninstall

- **Update:** download the latest version and replace the files in `mods/pf/`.
- **Uninstall:** delete the `mods/pf/` folder.

## Notes

- Keep all three files together in one folder named `pf`. Don't rename them.
- If the game fails to load after an STS2 update, the mod may need a rebuild for the new game
  version. Please open an issue.

Author: muoyu
