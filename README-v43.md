# PlotMines UI v43

SHA-1: `2d51e4e433b98e8f8379dcb2d845b91dd581623e`

Preserves v42's bright UI and all 938 existing non-metadata entries byte for
byte. Adds six version-specific beacon beam fragment shaders to hide only
the vertical beam, including its opaque inner and translucent outer layers.
Beacon block textures, models, lighting and gameplay rewards are unchanged.
Beam suppression applies wherever this resourcepack is active.

Verification: 81 GPU checks against nine actual Mojang shader interfaces,
unchanged active uniforms, positive-control drawing and alpha/blending cases;
JSON/PNG/model/font/reference validation; 5,611 cumulative local menu/fallback
and permission checks with zero failures. The unchanged UI assets also retain
v42's 55,044 synthetic GPU checks. Actual Minecraft client rendering and
client-specific crash reproduction remain unverified; bots only acknowledge
resourcepack protocol messages.

Native panels/cosmetic models require matching plugin capability hashes for
this exact ZIP. Missing capability uses native fallback. Publishing this file
does not deploy or configure the production server. Keep v42 and earlier ZIPs
for rollback; no existing ZIP has been replaced.
