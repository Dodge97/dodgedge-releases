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
4. Start DodgEdge from the desktop shortcut or the Start menu — a small icon appears in your **system tray** (bottom-right, near the clock)

> DodgEdge adds itself to your startup programs, so it comes back on its own after a restart.

> **Windows SmartScreen warning?** Click **More info** → **Run anyway**. This appears because the app is new — it is safe to proceed.

### macOS

DodgEdge runs on **Apple Silicon** Macs (M1 and later). Not sure which you have?
Click **Apple menu → About This Mac** — "Chip: Apple M…" means Apple Silicon. On an
Intel Mac, ask the operator: a build for it can be made on request.

1. Go to the [latest release](https://github.com/Dodge97/dodgedge-releases/releases/latest)
2. Download `DodgEdge-...-Apple-Silicon.dmg`
3. Open the DMG and drag DodgEdge into **Applications**
4. Open DodgEdge **from your Applications folder**, not from the DMG window — if macOS shows a security warning, go to **System Settings → Privacy & Security → Open Anyway**
5. Eject the DMG once DodgEdge has opened

> The first time you open it, DodgEdge sets itself to start when you log in, so it comes back on its own after a restart. That only works when you start it from Applications, which is why step 4 matters.

---

## Setup

When you first open DodgEdge, a setup wizard opens. After the welcome screen it asks for three things:

1. **Create your account** — enter your email address. DodgEdge is invitation-only: the address has to be on the operator's access list, so use the one you signed up with.
2. **Accept the terms** — review and agree to the terms of service
3. **Choose a PIN** — protects your dashboard from others on your computer

After setup, go to **Settings** and connect your **bet365** account. You'll need:

- your bet365 **username and password**
- your **country**
- a **stake per bet** — the minimum for your currency is shown under the field. Every bet DodgEdge places is for exactly that amount; it never changes on its own, so you always know what's at risk per bet. You can adjust it any time in Settings.

Saving the connection opens a bet365 window and signs in, to check that the login works. If bet365 asks something first — a cookie notice, a verification step, a "confirm you're not a robot" box — finish it in that window; DodgEdge carries on by itself the moment you're in.

When the connection is saved, click the **play button next to the DodgEdge logo** in the sidebar to start. DodgEdge then places bets automatically.

---

## The bet365 window

While DodgEdge runs, it keeps its own browser window open with bet365 signed in. That window *is* the bot — it's where your bets are placed, and you can watch it work.

- **Leave it open.** You can minimise it or move it to another desktop, but if you close it, no more bets are placed.
- **Don't sign out in it**, and don't place bets by hand in that window.
- **Do help it when it asks.** Sometimes bet365 puts something in the way that only a person can clear. DodgEdge then shows a banner on your dashboard — *"Finish the bookmaker login in the browser window"* — and waits about three minutes. Click into the bet365 window, finish what it's asking, and DodgEdge takes over again on its own.

Your own bet365 account stays yours: you can use bet365 normally in your regular browser, on your phone, whenever you like.

---

## Keep it running

DodgEdge needs to stay active to monitor markets and place bets. Keep your computer on and don't quit the app.

You can close the **DodgEdge dashboard tab** whenever you like — DodgEdge keeps running in the background via the system tray icon, and you can reopen the dashboard from there. Leave the **bet365 window** open, though (see above).

DodgEdge starts automatically when you log in, so a restart brings it back by itself. It does not reopen after you quit it deliberately — start it again from the desktop shortcut (Windows) or Applications (Mac).

---

## Updates

When a new version is available, a banner appears in your dashboard:

1. Click **Download**
2. Close DodgEdge (right-click the tray/menu bar icon → **Quit**)
3. Install it — your settings and data are kept:
   - **Windows:** run the new installer
   - **macOS:** open the DMG, drag DodgEdge into **Applications** and choose **Replace**, then start it from Applications

---

## Pricing

DodgEdge is **free to install and use**. Your first **€50 in profit is completely free**.

After that, your **performance fee** applies on new profit only — you never pay on losses. The rate agreed for your account is shown in your dashboard under **Billing** and in the terms you accepted during setup.

---

## Troubleshooting

| Problem | Solution |
|---------|----------|
| **Banner: "Finish the bookmaker login in the browser window"** | bet365 is asking something DodgEdge can't answer for you. Switch to the bet365 window, finish the step (verification, a robot check, a notice), and DodgEdge continues by itself. If you miss it, it tries again on its own. |
| **No bets, and no bet365 window** | The bot isn't started: click the **play button next to the DodgEdge logo**. If it is started, quit DodgEdge from the tray and open it again. |
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

On macOS, also remove the start-at-login entry:
`~/Library/LaunchAgents/io.dodgedge.app.plist`
(The Windows uninstaller removes its own startup entry for you.)

Your betting data is preserved after uninstalling. To remove everything, also delete:

- **Windows:** `%APPDATA%\DodgEdge\`
- **macOS:** `~/Library/Application Support/DodgEdge/`
