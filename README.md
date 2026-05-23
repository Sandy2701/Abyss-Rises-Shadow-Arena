# Abyss Rises: Shadow Arena

An original browser action RPG inspired by dark fantasy arena combat. It uses HTML, CSS, and JavaScript only, so it can run from VS Code without downloading game-engine packages.

## Run In VS Code

1. Open this folder in VS Code:
   `C:\Users\Sande\Documents\Codex\2026-05-23\i-want-you-to-create-a`
2. Make sure Node.js is installed.
3. Open the VS Code terminal.
4. Run:

   ```powershell
   npm start
   ```

5. Open this address in your browser:

   ```text
   http://localhost:5500
   ```

## Run With VS Code Debug

1. Open the Run and Debug panel.
2. Choose `Launch Abyss Rises`.
3. Press `F5`.

VS Code will start the local server and open the game in Chrome.

## Controls

- Move: `W`, `A`, `S`, `D` or arrow keys
- Attack: left mouse button
- Dash: `Space`
- Skill one: `Q`
- Skill two: `E`
- Ultimate: `R` when Fury reaches 100%
- Pause: `Esc`
- Sound: `M`

You can also use the on-screen action buttons.

## Files

- `index.html`: game layout and overlays
- `styles.css`: responsive interface and visual styling
- `game.js`: gameplay, combat, enemy waves, leveling, loot, and rendering
- `dev-server.mjs`: local static server
- `.vscode/tasks.json`: VS Code server task
- `.vscode/launch.json`: VS Code browser launch setup

## Notes

This is not a copy of Darkness Rises and does not use its assets, characters, names, or code. It is a new, playable dark fantasy arena game made to capture a similar hack-and-slash feeling in a lightweight web project.
