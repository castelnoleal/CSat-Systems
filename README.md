# CSatS

CSat Systems: tools for operations teams.

## Modules

| Module | What it is |
|---|---|
| **Orbit** | Headset accountability and tracking, 1Password stations and PCs, Teams Tracker, work notes and alarms, accountability forms, and the user database |

## How it is opened

CSatS opens only through the **CSatS portal file** (`CSatS.html`), which admins share with the team. The files in this repository are encrypted. The portal downloads them, unlocks them and starts the app in the browser.

## Layout

| Path | What it is |
|---|---|
| `orbit/app.enc` | The Orbit app, encrypted |
| `orbit/config.enc` | Shared-database settings, encrypted (added from Admin Access → Shared database) |
| branch `csats-data` | Shared data written by the app, encrypted. Do not edit by hand |
