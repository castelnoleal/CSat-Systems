# CSatS

Centralized Server Asset Tracking System.

Assets, accountability and team records for operations teams, on one shared server.

## Modules

| Module | What it is |
|---|---|
| **Orbit Workplace** | Headset tracking: inventory, assignments, returns, repairs and the audit log |
| **1Password** | Station codes and PCs per agent, current and previous |
| **Teams Tracker** | Coaches and their teams, with station and accountability progress |
| **Work Notes** | Callbacks, reminders, schedules and tasks, with alarms |
| **Accountability Forms** | Headset forms by wave, team or a hand-picked list, signed online |
| **User Database** | Employee details, wave, coach, PCs and headsets |
| **Custom Tabs** | Tabs built from CSatS data or uploaded files, with tables, summaries, charts, boards and forms |

## How it is opened

CSatS opens only through the **CSatS portal file** (`CSatS.html`), which admins share with the team. The files in this repository are encrypted. The portal downloads them, unlocks them and starts the app in the browser.

## Editing

Use **CSatS Editor.html** (kept outside this repository) to change names, text, colours, menu order and the source, then publish.

## Layout

| Path | What it is |
|---|---|
| `orbit/app.enc` | The CSatS app, encrypted |
| `orbit/config.enc` | Shared-database settings, encrypted (added from Admin Access → Shared database) |
| branch `csats-data` | Shared data written by the app, encrypted. Do not edit by hand |
