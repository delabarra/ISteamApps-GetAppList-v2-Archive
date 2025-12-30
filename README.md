# ISteamApps-GetAppList-v2-Archive

This repository preserves a static snapshot of the Steam application catalog in [appList.json](appList.json).

Originally, this dataset was available from Valve's Web API endpoint:

https://api.steampowered.com/ISteamApps/GetAppList/v2/

As of December 29, 2025, requests to this endpoint fail with:

```
Not Found
Method 'GetAppList' not found in interface 'ISteamApps'
```

This repository therefore provides a static snapshot for archival and reference purposes only.

## View Online

- Raw archive of `appList.json`:

	https://raw.githubusercontent.com/delabarra/ISteamApps-GetAppList-v2-Archive/refs/heads/main/appList.json

## Contents

- File: `appList.json`
- Format:

	```json
	[
		{ "appid": 10, "name": "Counter-Strike" },
		{ "appid": 20, "name": "Team Fortress Classic" }
	]
	```

Note: This snapshot is a flat array of app objects (different from the legacy API shape that wrapped data under `applist.apps`).

## Notes and Attribution

- Data originally sourced from Valve's Steam Web API (`/ISteamApps/GetAppList/v2/`).
- This dataset is provided for archival, research, and educational purposes only. Respect Valve's terms and applicable laws.

If the official API becomes available again, consider refreshing the dataset directly from the source to ensure the most current and complete app list.

