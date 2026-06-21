# Third-Party Notices — ShimejiStudio

ShimejiStudio is a **manager** for Shimeji mascots. It **bundles** the **Shimeji-ee** engine to
animate the mascots on your desktop. ShimejiStudio is **not affiliated with or endorsed by** the
authors of Shimeji-ee or of the original Shimeji.

> ShimejiStudio bundles the Shimeji-ee engine (**New BSD** license). The original Shimeji by
> **Yuki Yamada / Group-Finity** is under the **zlib/libpng** license. ShimejiStudio is not
> affiliated with or endorsed by their authors; all rights to those works belong to their
> respective authors.

## Bundled third-party components

The engine ships inside the installer. The full text of the corresponding licenses is included in
the installer as `engine/licence.txt` (the official license file from the Shimeji-ee distribution).

| Component | File | License |
|-----------|------|---------|
| **Shimeji-ee** (engine) | `engine/Shimeji-ee.jar` | New BSD — © Shimeji-ee Group / Kilkakon |
| Original Shimeji | (historical base) | zlib/libpng — © Yuki Yamada (Group-Finity) |
| i18n classes | (inside the jar) | MIT — © 2016-2017 John O'Conner |
| **NimROD** Look & Feel | `engine/lib/nimrodlf.jar` | LGPL v3 — © Nilo J. González |
| **JNA** | `engine/lib/jna.jar`, `examples.jar` | LGPL 2.1 **or** Apache 2.0 |
| AbsoluteLayout (NetBeans) | `engine/lib/AbsoluteLayout.jar` | CDDL / GPL+CPE (NetBeans) |

### Compliance (summary)
- **New BSD / zlib / MIT**: copyright notices and disclaimers are kept (in `engine/licence.txt`),
  and we do not claim authorship of the original works.
- **LGPL (NimROD, JNA)**: the libraries are included **unmodified**, as **separate, replaceable**
  `.jar` files, and the LGPL text is provided (`engine/licence.txt`) — compliant use (dynamic
  linking, replaceable library).
- **ShimejiStudio's own code is not open source**; this page only covers the redistributed
  third-party components.

## Mascot packs
**Shimeji packs** (frames, config) imported by the user belong to **their respective creators**.
The installer **does not bundle any fan-made pack**; users provide/import their own mascots.
Please credit creators (each pack's "source" field).
