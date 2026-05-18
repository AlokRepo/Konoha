# Konoha

> **Public Anime Metadata Cache**

This repository is automatically maintained by the [AniSync](https://github.com/yourname/anisync) service. It contains high-fidelity anime metadata aggregated from AniList, TMDB, Jikan, and other sources.

## Data Access

All data is served via the **jsDelivr CDN** for maximum performance:

- **Global Index**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/index.json`
- **ID Mapping**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/id-map.json`
- **Search Index**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/search.json`
- **Genre Directory**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/genres.json`
- **Release Years**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/years.json`
- **Airing Now**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/airing.json`
- **Library Stats**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/stats.json`
- **Pipeline Status**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/sync-status.json`
- **Anime Details**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/anime/{anilist_id}/index.json`
- **Episode Lists**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/data/anime/{anilist_id}/episodes.json`

## Purpose

The goal of Konoha is to provide a standardized, cross-source anime database that can be consumed by applications with zero server-side logic and sub-50ms latency.

---
Maintained by AniSync Pipeline.
