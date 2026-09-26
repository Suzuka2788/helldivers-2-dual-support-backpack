# Suzuka's Dual Support Backpack AIO

Carry a second supported support weapon in your backpack slot in Helldivers 2. Pick up a second weapon while slot 3 is occupied, then press **4** to draw the backpack weapon. Pressing **4** again while holding it leaves it selected. The AIO also provides a native backpack HUD bar, guarded empty-tube dropping and cleanup for supported disposable weapons, and limited ammo refill fixes.

## Download and install

Download the latest ZIP from [Releases](https://github.com/Suzuka2788/helldivers-2-dual-support-backpack/releases/latest). The current version is **v1.0.1**. Requires **Bingus Shared Loader v15 or newer (API 1)**. Quit the game, install the ZIP, deploy, and restart. Both AIO versions use the same mod GUID; do not enable them together. 

## Current limitations

- Ammo refill supports only verified weapons and conditions. Backpack magazine refill is limited to recognized magazine weapons and a slot-3 refill that leaves the backpack weapon unchanged. GL-52 round-by-round refill covers four verified combinations and can run once per game launch.
- Allow empty disposable weapons to finish dropping before switching.
- Joining another player's multiplayer lobby may cause frame drops before entering a mission; the cause remains under investigation.
- Not every weapon, lobby, or long-session combination has been tested.

Logs are under `%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs`. To roll back, quit the game, disable this package, deploy and restart, then enable the earlier version alone.

v1.0.1 uses five game Lua resources byte-for-byte identical to the game-tested `rc2-shared-scan-key4-idempotent-test` candidate. Its key-4 behavior was confirmed in game on 2026-09-26. This public repository contains the README and release ZIP; GitHub's auto-generated source archive does not contain the local development source.
