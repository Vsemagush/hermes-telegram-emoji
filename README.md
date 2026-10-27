# Hermes Telegram Emoji

Unofficial community artwork for Telegram custom emoji, inspired by Hermes / Nous and classical imagery. This is not an official or endorsed collection; see [NOTICE.md](NOTICE.md).

13 static PNG images, exactly 100 × 100 pixels, with transparent backgrounds. Stable IDs are **01–11, 13 and 15**; **12 and 14 are intentionally skipped**. The IDs are filenames for review and mapping, not Telegram custom emoji IDs.

[Download all 13 PNGs as a ZIP](dist/hermes-telegram-emoji.zip?raw=true) · [Proposed emoji mappings and file hashes](manifest.json)

## Preview

![All 13 images on white and near-black backgrounds at 100, 32 and 24 pixels](previews/contact-sheet.png)

The PNGs have fixed colours; they are not adaptive emoji. Small details and thin outlines may appear softer at 24 pixels. `masters/` contains the matching processed full-resolution raster artwork, not SVG/vector sources.

## Create a custom emoji set manually

**A Telegram emoji pack has not been published yet.** There is no addemoji link or published custom emoji ID in this repository. Telegram import and real-chat rendering have not been tested here.

1. Download and extract the ZIP, then open the official [@Stickers Mini App](https://t.me/stickers?startapp) in Telegram.
2. Start creating a new **custom emoji** set and select the static image format. Choose emoji, not a regular sticker pack: these exports are 100 × 100 pixels, not 512-pixel stickers.
3. Upload the PNG files as files/originals without resizing or conversion. Follow the Mini App's prompts for the set name and emoji associations; use `proposed_emoji` in the manifest as a starting point, not as a required mapping.
4. Preview a trial image on light and dark themes and in a real message before completing the set. Only after actual publication should the real Telegram set link be added here.

Telegram states that anyone can create custom emoji, while adding and using custom sets generally requires Telegram Premium; free-emoji exceptions and account/client rules may apply. Check the current [official requirements](https://core.telegram.org/stickers#custom-emoji) and [custom emoji documentation](https://core.telegram.org/api/custom-emoji).

## Files

- `exports/telegram/`: the 13 approved transparent PNGs.
- `masters/`: the same 13 approved processed raster masters.
- `previews/contact-sheet.png`: the approved preview.
- `dist/hermes-telegram-emoji.zip`: exactly the 13 numbered PNGs, without documents or source material.
- `manifest.json`: IDs, slugs, relative paths, SHA-256 hashes and proposed Unicode emoji mappings.

No blanket licence to third-party artwork or marks is granted. This repository does not assert ownership of that material.
