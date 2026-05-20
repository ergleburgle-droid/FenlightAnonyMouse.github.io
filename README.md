https://FenlightAnonyMouse.github.io/packages

# FenLightAM

A Kodi video addon providing access to content via Easynews and Debrid cloud services (Real-Debrid, Premiumize, AllDebrid, TorBox, etc.) with metadata from TMDb, Trakt, OMDb, and IMDb.

This is a community-maintained fork continuing development after the original author stepped away.

## Install

Add `https://fenlightanonymouse.github.io/packages` as a Kodi zip source, then install from zip.

## Required Setup After Install

The addon requires you to supply your own API credentials. None are bundled.

### TMDb (mandatory - without this nothing works)

1. Create a free account at [themoviedb.org](https://www.themoviedb.org/)
2. Go to **Settings > API** and request an API key (free for personal use)
3. In FenLightAM go to **Settings > Accounts > TMDb API Key** and paste your v3 API key

### TMDb Lists (optional - only needed for TMDb list features)

On the same TMDb API settings page, copy the **API Read Access Token (v4 auth)** (the long JWT string) and paste it into **Settings > Accounts > TMDb Read Access Token**.

### Trakt (optional)

The default Trakt app credentials bundled with the addon may no longer be active. If Trakt authentication fails:

1. Register a free app at [trakt.tv/oauth/applications](https://trakt.tv/oauth/applications)
2. Set redirect URI to `urn:ietf:wg:oauth:2.0:oob`
3. Paste your Client ID and Secret into **Settings > Accounts > Trakt Client / Trakt Secret**

### Debrid Services (optional)

Authenticate via **Settings > Accounts** for whichever service(s) you subscribe to (Real-Debrid, Premiumize, AllDebrid, TorBox, etc.).

## Changelog

See `packages/fen_light_changes` or the in-addon **Tools > Changelog** menu.
