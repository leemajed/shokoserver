\# Local ShokoServer Patches



Stable tag:

local-stable-server-mpv-tmdb-settings-userfix-v1



\## Changes

\- FileController.cs: added localhost/admin-only mpv playback endpoint.

\- TmdbMetadataService.cs: tolerate missing TMDB key in dev.

\- TmdbSearchService.cs: return empty results when TMDB is unavailable.

\- SettingsController.cs: guard invalid WebUI\_Settings patch payloads.

\- ShokoJsonSchemaValidator.cs: harden settings validation against JsonReaderException.

\- UserService.cs: fix empty avatar update handling for PUT User/1.

