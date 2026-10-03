# Sundered Sagas: Endless Frontier — Downloads

Download the game, or run your own dedicated server, from the
[**latest release**](https://github.com/monkzoren/sundered-sagas/releases/latest).

## Play

| Platform | File | Notes |
|---|---|---|
| **Windows** | `*-setup.exe` (or `*.msi`) | Unsigned for now. If SmartScreen warns, choose *More info → Run anyway*. |
| **Linux / Steam Deck** | `*.AppImage` or `*.deb` | AppImage: `chmod +x`, then run. On Steam Deck, use the AppImage and add it to Steam as a Non-Steam Game for Gaming Mode. |

The game installs everything it needs, including its own local server. Choose
**Start local game** to play on your machine (private, or open to friends by IP),
or join someone else's world with **Add server**. Keyboard and mouse or a
controller. The app checks for updates on launch and installs them in the
background.

## Host a dedicated server

- **Windows x64** — `bastion-server-windows-x64.exe`
- **Linux x64** — `bastion-server-linux-x64`

Run it. A config panel opens in your browser, and on first launch it fetches the
game engine once. No Docker, no Node. Then share your `ws://your-ip:3000` address
with players, or join your own from the game with **Add server**.

The server panel tells you about new releases. Turn on **Auto-update** for a
hands-off update that keeps your world. Difficulty, day/night, admins and
database backups are all in the panel, or on the command line
(`bastion-server-… --help`).

Client and server must be on the same release to connect.

> This repo only hosts prebuilt releases. They are published automatically by the
> game's build pipeline, and only the current release is kept.
