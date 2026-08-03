# DodgEdge — Getting Started

**Quantified Edge & Automated Placement**

DodgEdge calculates the true probability of every match we cover, inverts it into fair odds,
and commits your stake only where bet365 trades above them. Whatever the market offers above
fair odds is the edge. You set the stake once; from there it runs unattended.

## What it does

- **Calculates true probabilities** — our models calculate the true probability of each outcome
- **Exploits the edge** — a bet follows only where bet365's odds exceed fair odds
- **Places and settles** — the bet is placed on your own account at your stake within seconds, and reconciles itself once the result is in

---

## What you need

- A **Windows** PC (Windows 10+) or **Mac** (macOS 12+)
- A **bet365** account

---

## Download & Install

### Windows

1. Go to the [latest release](https://github.com/Dodge97/dodgedge-releases/releases/latest)
2. Download **`DodgEdge-Setup.exe`**
3. Double-click the installer and follow the steps
4. DodgEdge starts automatically — a small icon appears in your **system tray** (bottom-right, near the clock)

> **Windows SmartScreen warning?** Click **More info** → **Run anyway**. This appears because the app is new — it is safe to proceed.

### macOS

1. Go to the [latest release](https://github.com/Dodge97/dodgedge-releases/releases/latest)
2. Download the right DMG for your Mac:
   - **Apple Silicon** (M1/M2/M3/M4): `DodgEdge-...-Apple-Silicon.dmg`
   - **Intel** (2017–2020 models): `DodgEdge-...-Intel.dmg`
   - *Not sure?* Click **Apple menu → About This Mac**. "Chip: Apple M…" means Apple Silicon.
3. Open the DMG and drag DodgEdge into **Applications**
4. Open DodgEdge — if macOS shows a security warning, go to **System Settings → Privacy & Security → Open Anyway**

---

## Setup

When you first open DodgEdge, a setup wizard walks you through:

1. **Create your account** — enter your email address. DodgEdge is invitation-only: the address has to be on the operator's access list, so use the one you signed up with.
2. **Accept the terms** — review and agree to the terms of service
3. **Choose a PIN** — protects your dashboard from others on your computer

After setup, go to **Settings** and connect your **bet365** account — you'll need your bet365 username/password and a stake per bet (minimum €1). Every bet DodgEdge places is for exactly that amount; it never changes on its own, so you always know what's at risk per bet. You can adjust it any time in Settings.

When the connection is saved, click the **play button next to the DodgEdge logo** in the sidebar to start. DodgEdge then places bets automatically.

---

## Keep it running

DodgEdge needs to stay active to monitor markets and place bets. Keep your computer on and don't quit the app. You can close the browser window — DodgEdge runs in the background via the system tray icon.

---

## Updates

When a new version is available, a banner appears in your dashboard:

1. Click **Download**
2. Close DodgEdge (right-click the tray/menu bar icon → **Quit**)
3. Run the new installer — your settings and data are kept

---

## Pricing

DodgEdge is **free to install and use**. Your first **€50 in profit is completely free**.

After that, your **performance fee** applies on new profit only — you never pay on losses. The rate agreed for your account is shown in your dashboard under **Billing** and in the terms you accepted during setup.

---

## Troubleshooting

| Problem | Solution |
|---------|----------|
| **No tray icon visible** | **Windows:** Click the **^** arrow in your taskbar. **Mac:** Check the top-right menu bar. |
| **Dashboard doesn't open** | Go to `http://127.0.0.1:8095` manually |
| **"Connection refused"** | Make sure DodgEdge is running. If just installed, wait a few seconds and refresh. |
| **Won't start** | Try quitting and reopening the app |
| **Forgot your PIN** | On the login page, click **Forgot your PIN?** and enter the email you used during setup. Your PIN resets and all data is preserved. |
| **"This email is not on the access list"** | Your address hasn't been added yet, or you typed a different one. Ask the operator to add it, then run setup again. |
| **"This email is already registered"** | The account exists on another machine. Reinstalling or moving to a new laptop? Ask the operator to re-open your address — you keep the same account and history. |
| **"Registration is currently closed"** | Contact the operator — new registrations may be temporarily paused. |
| **macOS: "not supported on this Mac"** | Make sure you downloaded the correct version (Apple Silicon or Intel). |

---

## Uninstalling

**Windows:** Settings → Apps → Installed Apps → DodgEdge → Uninstall

**macOS:** Drag the app from Applications to the Trash

Your betting data is preserved after uninstalling. To remove everything, also delete:

- **Windows:** `%APPDATA%\DodgEdge\`
- **macOS:** `~/Library/Application Support/DodgEdge/`
