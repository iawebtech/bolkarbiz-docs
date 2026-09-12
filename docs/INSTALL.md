# Install Bolkar BIZ

Same Bolkar BIZ account on every device. After install, sign in (or create a shop) and data can sync when the device is online.

Minimum: **2 GB RAM** (4 GB better), **~200 MB** disk, plus space if you use on-device AI models.

---

## Android

1. Open [Bolkar BIZ on Google Play](https://play.google.com/store/apps/details?id=com.iawebtech.bolkar).
2. Tap **Install**.
3. Allow camera / microphone only if you use barcode, photos, or voice.
4. Sign in and complete shop setup.

**Needs:** Android 7.0 or later.

**Use it for:** pocket billing, stock checks on the shop floor, voice commands while serving a customer.

Package ID: `com.iawebtech.bolkar`

---

## iOS (iPhone / iPad)

1. Open [BolkarBIZ on the App Store](https://apps.apple.com/in/app/bolkarbiz/id6760892724).
2. Tap **Get** / **Install**.
3. Sign in with the same account as Android or desktop.

**Needs:** iOS 14 or later.

**Use it for:** owner dashboard on the go, approvals, viewing reports, taking orders.

---

## Windows

1. Download [BolkarBIZ-Setup.exe](https://bolkarbiz.com/downloads/desktop/latest/windows/BolkarBIZ-Setup.exe).
2. Run the installer. Windows SmartScreen may ask you to confirm **More info → Run anyway** (signed builds still sometimes trigger this on first download).
3. Finish setup and launch **Bolkar BIZ** from the Start menu.

**Needs:** Windows 10 or 11, 64-bit.

**Use it for:** main billing counter, keyboard + scanner, end-of-day reports, staff training on a large screen.

Uninstall: Windows **Settings → Apps → Bolkar BIZ**.

---

## macOS

1. Open [BolkarBIZ on the Mac App Store](https://apps.apple.com/in/app/bolkarbiz/id6760892724?platform=mac).
2. Click **Get**.
3. Open **Bolkar BIZ** from Applications.

**Needs:** macOS 11 Big Sur or later. Apple Silicon and Intel.

**Use it for:** back-office (catalogue, reports, staff), and a quiet billing desk.

---

## Linux — Snap Store (recommended on Ubuntu and friends)

Works on Ubuntu, Fedora, Debian, Pop!_OS, KDE Neon, Manjaro, elementary, and other distros with [snapd](https://snapcraft.io/docs/installing-snapd).

```bash
sudo snap install bolkarbiz --edge
bolkarbiz
```

Store page: https://snapcraft.io/bolkarbiz

The first public revision is on the **edge** channel. When a stable channel release is published, you can use:

```bash
sudo snap install bolkarbiz
```

Update:

```bash
sudo snap refresh bolkarbiz
```

Remove:

```bash
sudo snap remove bolkarbiz
```

---

## Linux — AppImage (any distro, no store)

1. Download [bolkarbiz-linux.AppImage](https://bolkarbiz.com/downloads/desktop/latest/linux/bolkarbiz-linux.AppImage).
2. Make it executable and run:

```bash
chmod +x bolkarbiz-linux.AppImage
./bolkarbiz-linux.AppImage
```

**Needs:** typical GTK 3 desktop (Ubuntu 20.04+ or equivalent). Fuse/`libfuse2` may be required for AppImage.

**Use Snap** if you want automatic updates from the store. **Use AppImage** if you cannot install snapd.

---

## Driver app — Android only

For pickup and delivery staff. This is **not** the full Bolkar BIZ POS. It is a separate app: **Driver - For BolkarBIZ**.

1. Open [Driver - For BolkarBIZ on Google Play](https://play.google.com/store/apps/details?id=com.bolkarbiz.driver&hl=en_IN).
2. Install on the rider’s Android phone.
3. Sign in with the **driver / delivery** login the shop owner created in Bolkar BIZ (not the owner POS login).
4. Accept assigned **pickup** and **drop** jobs, update status on the road.

**Needs:** Android. There is **no** iOS, Windows, macOS, or Linux driver app.

Package ID: `com.bolkarbiz.driver`

The shop still runs Bolkar BIZ (Play Store / desktop) to create jobs and assign drivers.

---

## ChromeOS

On a Chromebook with Play Store:

1. Install [Bolkar BIZ from Google Play](https://play.google.com/store/apps/details?id=com.iawebtech.bolkar).
2. Pin it to the shelf for a counter device.

---

## After install (all platforms)

1. Open the app and **sign in** or **create shop**.
2. Follow [Getting started](GETTING-STARTED.md).
3. Optional: enable camera, mic, Bluetooth printer in OS settings when you actually use those features.

Help: https://bolkarbiz.com/support · support@bolkarbiz.com
