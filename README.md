# Steam App List V2 — Snapshot

This repository preserves a static snapshot of the Steam application catalog in [appList.json](appList.json).

Originally, this dataset was available from Valve's Web API endpoint:

https://api.steampowered.com/ISteamApps/GetAppList/v2/

As of December 29, 2025, that endpoint appears to be unavailable. This repo exists for archival and reference purposes only.

## Contents

- File: `appList.json`
- Format (typical structure):

	```json
	{
		"applist": {
			"apps": [
				{ "appid": 10, "name": "Counter-Strike" },
				{ "appid": 20, "name": "Team Fortress Classic" }
			]
		}
	}
	```

## Notes and Attribution

- Data originally sourced from Valve's Steam Web API (`ISteamApps/GetAppList v2`).
- Valve, Steam, and all related marks are trademarks of Valve Corporation. This repository is unaffiliated with Valve.
- This dataset is provided for archival, research, and educational purposes only. Respect Valve's terms and applicable laws.

If the official API becomes available again, consider refreshing the dataset directly from the source to ensure the most current and complete app list.

