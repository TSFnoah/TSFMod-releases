1. Rocket League handling: reduced wobble, kept the car level without input, and expanded nose-up pitch to 60 degrees while retaining 30 degrees nose-down.
2. Discord Rich Presence now sends from one worker thread, refreshes every 6 seconds with at least 5 seconds between updates, and retries after connection errors.
3. Settings are written atomically; `settings.ini` edits apply live after about one second, and the Force direction slider is saved.
4. Per-player Disable Collision settings are saved by player ID and reapplied when that player is encountered again.
5. Added “No pushback from other players”: cars may still touch, but other players will not push or spin the local car.
6. Added optional `tsfmod` room-marker publishing, controlled by `publishPresence`.
7. Kino Discord override is controlled by `kinoDiscordOverride`; no Kino or KSL files are included in this release.
8. Requires the separate TSF Mod Loader for CarX Drift Racing Online. The loader is not included in this repository or release.
