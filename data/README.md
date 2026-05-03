# Konoha

> **Public Anime Metadata Cache**

This repository is automatically maintained by the [AniSync](https://github.com/yourname/anisync) service. It contains high-fidelity anime metadata aggregated from AniList, TMDB, Jikan, and other sources.

## Data Access

All data is served via the **jsDelivr CDN** for maximum performance:

- **Global Index**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/index.json`
- **Airing Now**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/airing.json`
- **Anime Details**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/anime/{anilist_id}/index.json`
- **Episode Lists**: `https://cdn.jsdelivr.net/gh/AlokRepo/Konoha@main/anime/{anilist_id}/episodes.json`

## Purpose

The goal of Konoha is to provide a standardized, cross-source anime database that can be consumed by applications with zero server-side logic and sub-50ms latency.

---
Maintained by AniSync Pipeline.
