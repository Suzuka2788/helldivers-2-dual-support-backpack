# Suzuka's Dual Support Backpack AIO

Carry a second supported support weapon in your backpack slot in Helldivers 2. Pick up a second weapon while slot 3 is occupied, then press **4** to draw the backpack weapon. Pressing **4** again while holding it leaves it selected. The AIO also provides guarded empty-tube dropping and cleanup for supported disposable weapons, and limited ammo refill fixes.

## Download and install

Download **v1.0.2 with native backpack HUD** or the optional **v1.0.1 No HUD version** from [the latest release](https://github.com/Suzuka2788/helldivers-2-dual-support-backpack/releases/latest). The No HUD variant leaves the ordinary game HUD intact but disables the experimental backpack support-weapon bar and low-ammo color override. It has passed offline checks but has not had a separate in-game acceptance test. The previous v1.0.1 release remains available.

Requires **Bingus Shared Loader v15 or newer (API 1)**. Quit the game, disable previous AIO versions and the five separate feature mods, install **one** ZIP, deploy, and restart. Both new variants and earlier AIO releases use the same mod GUID; do not enable them together.

## Current limitations

- Ammo refill supports only verified weapons and conditions. Backpack magazine refill is limited to recognized magazine weapons and a slot-3 refill that leaves the backpack weapon unchanged. GL-52 round-by-round refill covers four verified combinations and can run once per game launch.
- Allow empty disposable weapons to finish dropping before switching.
- Multiplayer performance depends on the game, host, and other mods. A recent session with the v1.0.2 candidate was reported smooth, but a stable 144 FPS is not guaranteed.
- Not every weapon, lobby, or long-session combination has been tested.

Logs are under `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs`. To roll back, quit the game, disable this package, deploy and restart, then enable the earlier v1.0.1 release alone.

v1.0.2 uses five game Lua resources byte-for-byte identical to the game-tested `144fps-guest-wait-fix-test` candidate. This public repository contains the README and release ZIPs; GitHub's auto-generated source archive does not contain the local development source.
