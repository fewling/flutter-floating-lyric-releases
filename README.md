# Floating Lyrics — Releases

Synchronized song lyrics in a floating window over any app on Android. Follows
whatever is playing, reads local `.lrc` files, searches for lyrics online, and
can translate them with AI.

**[⬇️ Download the latest APK](https://github.com/fewling/flutter-floating-lyric-releases/releases/latest)**
 · [All versions](https://github.com/fewling/flutter-floating-lyric-releases/releases)
 · [Get it on Google Play](https://play.google.com/store/apps/details?id=com.floating.lyrics)

---

## Which download should I use?

**Google Play is the easiest option** — it updates automatically and needs no
extra setup. Use the APKs here if you:

- don't have access to the Play Store on your device,
- want to install a specific older version, or
- prefer to keep the installer file yourself.

## Installing an APK

1. Download the `.apk` file from the [latest release](https://github.com/fewling/flutter-floating-lyric-releases/releases/latest).
2. Open it. Android will ask permission to install from this source — allow it
   for your browser or file manager.
3. Follow the prompts.

On first launch the app asks for **notification access** (to see what's playing)
and **display over other apps** (to draw the overlay). Both are required for the
lyrics window to work.

**The latest release requires Android 7.0 (Nougat, API 24) or newer.**
Historical builds list their own minimum Android requirements in their release notes.

## If you already have the app from Google Play

The archived Play-signed APKs use the same app-signing certificate as Google
Play. A compatible higher build can normally update a Play-installed copy
without uninstalling. Each filename includes the version and build number;
releases with several builds provide a separate APK for each one.

> [!IMPORTANT]
> **Downgrading normally requires uninstalling first**, even when both APKs
> have the same signing certificate. Uninstalling clears local settings and
> saved lyrics. Export any data you need before switching, where possible.

The original **floating-lyrics-6.8.3-63-universal.apk** is a legacy build signed
separately from Play. It remains available for existing users, but it cannot
update a Play-installed copy. For the Play-signed build of that version, use
**floating-lyrics-6.8.3-63-play-universal.apk** instead.

Archived builds are preserved for access to previous versions; compatibility
with current Android versions and online services is not guaranteed. Newly
archived downloads include **.sha256** files for checking file integrity.

## What's in this repository

Release builds and their notes — nothing else. The app's source code lives in a
separate private repository.

## Feedback and bug reports

**For bugs, prefer Settings → Send feedback inside the app.** It attaches
diagnostic details that a written description can't, and that's usually what
turns a vague report into a fix.

For everything else — feature ideas, questions, or a bug you can't report from
inside the app — [open an issue](https://github.com/fewling/flutter-floating-lyric-releases/issues/new/choose).
Play Store reviews are read too.

Issues here are for the app itself. The source code lives elsewhere and is not
public, so please don't expect code-level discussion.

## Changelog

Every release on the [releases page](https://github.com/fewling/flutter-floating-lyric-releases/releases)
carries its own notes.

## License

The application is released under the [MIT License](LICENSE).
Copyright © 2026 Wong Chi Ho Felix.
