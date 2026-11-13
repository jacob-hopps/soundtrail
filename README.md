# Soundtrail

A browser music collecting prototype with worldwide maps, genre chapters, recording previews, and local player progress.

## Play

Open the GitHub Pages site, pick a genre, and allow location. Public walking-network data places nearby drops; use Apple Maps to confirm walking directions. Music previews stream from Apple Music.

## Developer sandbox

Add `?dev=1&player=developer` to the site URL. Controls allow map-click teleporting, teleporting to a selected drop, unlocking chapters, and completing a test chapter. Developer progress uses a separate browser save. Developer mode is a testing convenience, not an authentication boundary.

## Data and services

- Maps: Esri and its attributed data providers; Natural Earth fallback geometry.
- Street graph and map data: OpenStreetMap contributors (ODbL); see on-map attribution.
- Map UI: Leaflet (BSD-2-Clause), license header preserved in the bundled source.
- Audio previews and album artwork: Apple Music/iTunes catalog links. No complete recordings are hosted in this repository.

Saved progress stays in each player's browser. This prototype has no shared leaderboard or server-side account system.
