# HubFolks — app releases

Installers for the HubFolks apps: desktop (macOS and Windows) and Android. The apps update themselves once installed.
Desktop and Android are released separately, with their own version numbers: desktop releases are tagged `v<version>`, Android releases `android-v<version>`.

## Download

**Desktop**: latest release: **[Releases → Latest](https://github.com/hubfolks/hubfolks-releases/releases/latest)**

- **macOS** (Apple Silicon and Intel): `HubFolks-<version>.dmg`
- **Windows** (64-bit): `HubFolks-<version>.exe`

**Android** (tablets and phones, Android 7.0 or later): **[HubFolks.apk](https://github.com/hubfolks/hubfolks-releases/releases/download/android-latest/HubFolks.apk)**, always the latest version.

## First launch

**macOS**

Since version 0.1.3, the macOS app is signed and notarized by Apple: it opens without any warning.

1. Open the `.dmg` and drag **HubFolks** into **Applications**.
   - If macOS asks for an administrator password, your account is not an administrator (common on company Macs). Drag **HubFolks** into the **Applications** folder of your home folder instead: in Finder, **Go → Home** (⇧⌘H), then open **Applications**. HubFolks runs and updates the same way from there.
2. Open HubFolks.
3. Updates install automatically: HubFolks offers **Restart now** when one is ready. If you installed 0.1.2 or earlier, install the latest `.dmg` once by hand.

**Windows**

The Windows build is not signed yet, so Windows shows a warning the first time.

1. Run `HubFolks-<version>.exe`.
2. If "Windows protected your PC" appears, click **More info**, then **Run anyway**.
3. Updates install automatically: HubFolks offers **Restart now** when one is ready.

**Android**
1. On the tablet or phone, download **[HubFolks.apk](https://github.com/hubfolks/hubfolks-releases/releases/download/android-latest/HubFolks.apk)**.
2. Open it. If Android asks, allow your browser to **install unknown apps**, then tap **Install**.
3. Updates: when a new version is available, HubFolks shows **Update available**. Tap **Download**, then open the downloaded file and tap **Update**.

## Sign in

On first launch, choose **Sign in** or **Create an account**: your browser opens the HubFolks site. Once you are signed in, come back to the app; your groups, notes and songs sync automatically.
