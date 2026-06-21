# ShimejiStudio — Releases

**ShimejiStudio** is a **Windows** app that manages a library of **Shimeji** desktop mascots,
previews them in an animated gallery, and brings them to life on your desktop (via the bundled
**Shimeji-ee** engine).

> This repository hosts the **downloadable builds only** (installer). The source code is not public.

## ⬇️ Download

Head to **[Releases](../../releases)** and grab the latest `ShimejiStudio-<version>-setup.exe`.

### Install
1. **Java is required** (the Shimeji-ee engine runs on Java): install a **JRE 8+** if you don't
   have one. The app detects it on first launch (otherwise, point it to your Java once).
2. Run the installer. It installs **per-user** (no admin rights); your mascots, settings and logs
   live next to the executable.

## ✨ At a glance
- Animated gallery with **Group** mode (one shared process for many mascots) and **Solo** mode
  (a dedicated process per mascot, with adjustable size).
- Import mascots from a **folder** or a **`.zip` / `.rar`** archive — the app auto-detects and
  sorts every pack inside.
- Organize your collection into **folders** (drag & drop), credit each mascot's source, and check
  for updates from within the app.

## 📄 Credits & licenses
ShimejiStudio **bundles** the **Shimeji-ee** engine (**New BSD** license). The original Shimeji by
**Yuki Yamada / Group-Finity** is under **zlib/libpng**. ShimejiStudio is **not affiliated with or
endorsed by** their authors. See [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md); full license
texts ship inside the installer.

Imported **mascot packs** belong to their respective creators — please credit them.
