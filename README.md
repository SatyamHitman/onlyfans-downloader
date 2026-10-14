# OnlyFans Downloader — Browser Extension for Chrome, Brave & Edge + iPhone & Android App

Save the OnlyFans videos, photos and DMs you already pay for, **DRM-protected PPV included**, processed entirely on your own device.

This is the OnlyFans documentation for [**Fanripper**](https://fanripper.com), a browser extension and an iPhone & Android app that also supports Fansly, JustForFans, privacy.com.br and Fanfix.

⬇️ **[Install](https://install.fanripper.com)** &nbsp;·&nbsp; 📱 **[iPhone & Android app](https://fanripper.com/app)** &nbsp;·&nbsp; 🌐 **[OnlyFans downloader page](https://fanripper.com/onlyfans-downloader)** &nbsp;·&nbsp; 💬 **[Telegram](https://t.me/fanripper)**

---

## The DRM problem, and how it is handled

Most OnlyFans video you pay for (PPV, many feed videos, DM videos) is protected with **Widevine DRM**. A plain downloader grabs the file and gets an encrypted blob that will not play, or falls back to screen recording, which on OnlyFans produces a black screen.

Fanripper handles the protection **on your device**: the video is decrypted locally and saved as an ordinary MP4 at the **highest rendition the manifest carries**, HEVC included. There is **no file-size limit**, because the file streams to disk instead of being held in memory, so multi-gigabyte videos that stall other tools finish here.

Nothing is uploaded and your OnlyFans password is never asked for. It works through the session you are already signed into.

## What it saves

| | |
|---|---|
| **DRM-protected video** | Decrypted on your device, top rendition, any size |
| **Standard video and photos** | Free and unlimited, photos at original resolution |
| **DMs** | Photos and videos from your chats |
| **Stories and highlights** | Yes |
| **A whole profile** | Across 10 surfaces, including paid/PPV, DMs and your own Vault |
| **Filters** | Date, media type and paid-only, before the run starts |
| **Metadata** | Creator, caption, price and post date written into each file |

## Honest limits

Stated here rather than discovered later:

- On protected video you always get the **top rendition**. You cannot deliberately pick a smaller one.
- You **cannot download PPV you have not bought**. It does not bypass a paywall; only content your account can already open.
- You cannot back up **another creator's Vault**, only your own.

## On your phone (iPhone & Android)

Fanripper also runs as an app on your phone. OnlyFans posts, videos and DMs save straight to your iPhone or Android, protected (DRM) videos included, decrypted on the phone itself.

1. Install **Expo Go** (free) from the [App Store](https://apps.apple.com/app/expo-go/id982107779) or [Google Play](https://play.google.com/store/apps/details?id=host.exp.exponent).
2. Open **[fanripper.com/app](https://fanripper.com/app)** on your phone and tap **Open Fanripper in Expo Go**, or scan the code there with your phone's camera.
3. Sign in with your Fanripper email: same account and plan as the extension.

Your phone gets its own device slot, so it never signs out your computer. Downloads run while the app is open, and updates arrive on their own. Guides: [iPhone](https://fanripper.com/blog/onlyfans-downloader-mac-iphone) · [Android](https://fanripper.com/blog/download-onlyfans-videos-android).

## Install the extension (about 60 seconds)

1. Download `fanripper.zip` from [install.fanripper.com](https://install.fanripper.com) or the [main repo's Releases](https://github.com/SatyamHitman/fanripper/releases).
2. Unzip it somewhere permanent.
3. Open `chrome://extensions` and turn on **Developer mode**.
4. Click **Load unpacked** and pick the unzipped folder.
5. Open OnlyFans. A save button appears on content you can already see.

Works on Chrome, Brave and Edge. It is not in the Chrome Web Store because stores remove extensions that work with subscription content.

**Updating:** a load-unpacked install cannot update itself. Fanripper tells you when a new version ships; extract it over the same folder and hit **Reload**. About 15 seconds, and your settings and login are kept.

## Which plan

Photos and standard video on OnlyFans are **free and unlimited**. **Basic** ($5/month) adds DRM-protected video, **Pro** ($8/month) adds whole-profile bulk backup and filters, and **Lifetime** is $99 once. Paid plans are bought inside the extension: crypto (USDT, BTC, ETH, USDC), card, Apple Pay or Google Pay through Telegram Stars, or a gift card. No KYC, and nothing renews by itself.

## Is it safe?

- Runs entirely on your device. Media and your login session never reach our servers.
- **Never asks for your OnlyFans password.** Anything asking you to type your platform password into it is a credential grab, not a downloader.
- Paces requests like ordinary browsing rather than hammering the site.
- The shipped build is flagged by **0 of 63** engines on [VirusTotal](https://www.virustotal.com/gui/file/dd8e3884eebc4052beaf212a09dc09cb324d5b74ac10c71199c3703543b97266/detection).

No tool that talks to a site it does not control can promise you an outcome, and anything claiming "100% undetectable" is bluffing. Local processing, no password, and human-paced requests are the honest version.

## Links

- 🌐 [fanripper.com](https://fanripper.com): all five supported sites
- 📊 [Side-by-side capability comparison](https://fanripper.com/supported-sites)
- 📖 [How to download OnlyFans videos](https://fanripper.com/blog/onlyfans-video-downloader)
- 🔐 [OnlyFans DRM downloader guide](https://fanripper.com/blog/onlyfans-drm-downloader)
- 📦 [Bulk-download a whole profile](https://fanripper.com/blog/bulk-download-onlyfans-profile)
- 💬 [Telegram](https://t.me/fanripper)

## Disclaimer

Fanripper is a personal backup utility for content you have **lawful, paid access to**. It is **not affiliated with, endorsed by, or connected to** OnlyFans or any content platform. No paywall is bypassed. You are responsible for complying with the platform's terms of service and your local law.
