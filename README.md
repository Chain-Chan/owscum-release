# ONE WORLD Launcher

Optional client mods for the **ONE WORLD** SCUM server (in-game panel and more), installed and removed by a small
Windows launcher. Downloads: **[Latest release](https://github.com/Chain-Chan/owscum-release/releases/latest)**.

## Install (3 steps)
1. Download `OneWorldLauncher-<version>.zip` from the latest release. Right-click it → Properties → tick **Unblock** → OK.
2. Unzip it anywhere (for example your Desktop).
3. Double-click **`ONE WORLD Launcher.cmd`** and choose `[1] Play ONE WORLD`. Keep the window open while you play.

## ⚠️ BattlEye
`[1]` starts SCUM **without BattlEye** and with mods loaded. Use it **only** for the ONE WORLD server.
**Never join any other server from that game.** For normal play use `[2] Play normal`: it removes every mod file and
starts SCUM through Steam with BattlEye. Mods are also removed automatically when the game closes.

## Is it safe?
- No installer, no admin rights, no Windows setting is changed. It only writes `dwmapi.dll`, `UE4SS.dll`,
  `UE4SS-settings.ini`, `Mods\` and `Content\Paks\~mods\` inside the SCUM folder, plus `%LOCALAPPDATA%\OneWorldLauncher`.
- Every download is listed in a signed manifest (ECDSA P-256) with its SHA-256; anything that does not match is refused.
- The scripts are plain text (PowerShell) — open them and read them.
- Check your download against `SHA256SUMS.txt` in the release: `Get-FileHash .\OneWorldLauncher-<version>.zip`
- VirusTotal: <!-- owner: paste the VirusTotal link for each release here -->

## Credits
- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT License, Copyright (c) 2022 Narknon) — downloaded by the launcher
  directly from its official GitHub release (v3.0.1, SHA-256 pinned). `UE4SS-settings.ini` here is its stock file with
  some settings changed.
- SCUM is a game by Gamepires / Jagex. This project is not affiliated with them and contains none of their files.
