# PlotMines UI v42

SHA-1: `23d933b694a588c336f3e4362b4f7cd6ad62c0bc`

Preserves the existing bright design and v41 version-specific shader overlays.
Adds six native inventory panel sizes, a separate panel font, corrected live
title depth, missing main-menu and backpack button frames, and cosmetic models.

Automated verification: 55,044 synthetic GPU checks across nine Mojang client
shader interfaces and GUI scales1–4; JSON/PNG/model/font/reference validation;
5,518 menu/fallback checks on a local Paper-compatible server. Bots acknowledge
pack protocol messages and do not download or render the pack. Full Minecraft
client rendering and client-specific crash reproduction remain unverified.

New panels and cosmetic item models require the matching plugin capabilities
to be configured with this exact SHA-1. A missing capability uses native
fallback. Publishing this file does not deploy or configure a server plugin.

Keep v41 and earlier files for rollback; no old ZIP has been replaced.
