TSF Mod v1.30 for CarX Drift Racing Online

1. Removed Auto-Chaser and Auto-Leader, including route recording, route selection and the End stop key.
2. Removed Show Own Hitbox.
3. Rocket League: the car can remain upside down; pitch controls are mirrored when inverted.
4. Player session information distinguishes players already present on arrival from players who join later.
5. Disable Collision now saves each selected player in collisionOffPlayers.
6. Removing a saved collision exception restores collisions; failed restoration is retried.
7. settings.ini reload retries after read failures and reports success only after a successful read.
8. Failed settings saves retry after 5 seconds. Removed the unsafe overwrite fallback; comments and unknown keys are preserved.
9. Input blocking follows a replaced PlayerCarControl instance after vehicle or scene changes.
10. Discord message reads time out after 5 seconds and reconnect instead of waiting indefinitely.
11. Reloading the menu releases the previous menu textures.
12. Heavy Drive skips distant prop checks beyond 30 metres, removes destroyed entries and performs a full rescan every 10 scans.
13. Added and expanded checks for names, gradients, settings persistence and player join tracking. All 24 automated checks passed before publication.

Validation: built from local source commit ad0acfd. The tested build matches the installed DLL byte-for-byte. In-game testing was confirmed by the user; it was not independently repeated during this publication.

Important: requires the separate TSF Mod Loader (d3d11.dll). The loader is NOT included in this release or repository. This update replaces only TSFMod.dll.
