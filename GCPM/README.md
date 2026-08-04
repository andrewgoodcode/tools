
# GCPM — The Fastest Way to Switch Chrome Profiles on Mac

**GCPM (Google Chrome Profile Monitor) is a free, open-source Mac app that puts every one of your Google Chrome profiles one click away, right from your menu bar.** Pick a profile, and GCPM opens a fresh Chrome window for it instantly — no digging through Chrome's own switcher required.

![GCPM menu bar dropdown showing a list of Chrome profiles](screenshot.png)

## Why GCPM Exists

If you use Google Chrome with more than one profile — a work account and a personal one, separate logins for different clients, or a few Google Workspace identities — switching between them the normal way is slower than it should be. You have to open Chrome, find the profile icon, click through a menu, and wait for the right window to appear. If Chrome isn't already running, it's even more steps.

GCPM was built to skip all of that. It sits quietly in your Mac's menu bar, and switching profiles becomes a two-click habit instead of a small chore you keep putting off.

## How GCPM Helps You

- **One click to any profile.** Click the menu bar icon, click a profile name, and a new Chrome window opens for it — done.
- **Works whether or not Chrome is already open.** GCPM launches Chrome straight into the profile you chose.
- **Always ready.** GCPM starts automatically when you log in to your Mac, so it's there the moment you need it. (You can turn this off if you'd rather open it manually.)
- **Stays out of your way.** No Dock icon, no app window taking up space — just a small icon in the menu bar.
- **Free and open source.** The full source code is public on GitHub, so you — or anyone — can see exactly what it does.

## Who GCPM Is For

GCPM is especially useful if you're:

- A freelancer or consultant who keeps a separate Chrome profile per client
- Someone who keeps work and personal Google accounts strictly separate
- Managing multiple Google Workspace or Gmail identities day to day
- Part of a team where switching Chrome identities is a daily routine

## Is Your Mac Compatible?

GCPM runs on:

- **macOS 13 (Ventura) or later** — including Sonoma, Sequoia, Tahoe, and newer versions.
- **Any Mac** — Apple Silicon (M1 and newer) or Intel. GCPM is a universal app, so it runs natively either way.
- **Google Chrome**, installed and opened at least once (this is what creates the profile data GCPM reads).

No other software, accounts, or sign-ups needed.

## How to Download and Install GCPM

### 1. Download it

[Click to download](https://github.com/andrewgoodcode/tools/raw/refs/heads/main/GCPM/Google-Chrome-Profile-Manager.zip) `GCPM.zip`.

### 2. Unzip it

Double-click the downloaded ZIP file. macOS will unzip it automatically into `GCPM.app`. (If nothing happens, right-click the ZIP file and choose **Open**.)

### 3. Move it to Applications

Drag `GCPM.app` into your **Applications** folder. This isn't strictly required, but it's where Mac apps are meant to live, and it keeps GCPM working reliably.

### 4. Open it (first time only)

Because GCPM is free and independently built, it hasn't gone through Apple's paid app-notarization process — so macOS shows an extra warning the first time you open it. This is completely normal for small, free, open-source apps and isn't a sign that anything is wrong. Here's how to get past it on current macOS:

1. Double-click **GCPM** in your Applications folder.
2. You'll see a message saying Apple couldn't verify the app. Click **Done** (not Move to Trash).
3. Open **System Settings → Privacy & Security**.
4. Scroll down to **Security**. You'll see a note that GCPM was blocked, with an **Open Anyway** button — click it. (Do this within about an hour of the warning, or you'll need to double-click GCPM again to see it once more.)
5. Enter your Mac's password if you're asked for it.
6. Open **GCPM** from Applications one more time. You may see a final confirmation — click **Open Anyway** once more.

That's it. This only happens the first time; after that, GCPM opens normally like any other app.

## How to Use GCPM

1. Look for the GCPM icon in your Mac's menu bar, near the clock in the top-right corner.
2. Click it to see every Chrome profile on your Mac, listed by name.
3. Click a name — a new Chrome window opens for that profile.
4. **Launch at Login** is on by default, so GCPM is always ready. Untick it from the menu if you'd rather start GCPM yourself.
5. To close GCPM, choose **Quit GCPM** from the same menu.

## Frequently Asked Questions

**Is GCPM really free?**
Yes — GCPM is free and open source, with no ads, accounts, or in-app purchases.

**Is GCPM safe to use?**
Yes. GCPM only reads a file Chrome already keeps on your own Mac to get your profile names — it never modifies that file, and the full source code is public so anyone can check exactly what it does.

**Does GCPM collect or send my data anywhere?**
No. GCPM doesn't use the internet at all. Everything happens locally on your Mac.

**Why does my Mac say GCPM is from an "unidentified developer"?**
Because it isn't notarized by Apple — a paid process many free, independent developers skip. See the install steps above for how to open it safely; it's a one-time step.

**Does GCPM support Chrome Beta, Dev, or Canary?**
Not currently — GCPM reads profiles from the standard (stable) release of Chrome only.

**No profiles are showing up — what do I do?**
Make sure Google Chrome has been opened at least once on your Mac. That's what creates the profile data GCPM reads.

**Will GCPM slow down my Mac?**
No — it's a lightweight menu bar utility that stays idle until you click it.

## Get GCPM

**[Download GCPM from GitHub](https://github.com/andrewgoodcode/tools/raw/refs/heads/main/GCPM/Google-Chrome-Profile-Manager.zip)** — free, and takes under a minute to set up.
