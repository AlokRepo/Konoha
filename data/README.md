# Konoha

> **Public Anime Metadata Cache**

This repository is automatically maintained by the [AniSync](https://github.com/yourname/anisync) service. It contains high-fidelity anime metadata aggregated from AniList, TMDB, Jikan, and other sources.

## Data Access

All data is served via **GitHub Raw** (jsDelivr limit exceeded):

- **Global Index**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/index.json`
- **ID Mapping**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/id-map.json`
- **Search Index**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/search.json`
- **Genre Directory**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/genres.json`
- **Release Years**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/years.json`
- **Library Stats**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/stats.json`
- **Anime Details**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/anime/{anilist_id}/index.json`
- **Episode Lists**: `https://raw.githubusercontent.com/AlokRepo/Konoha/main/data/anime/{anilist_id}/episodes.json`

## Credits & Sources

This database is made possible by the incredible APIs and datasets provided by:

- **[AniList](https://anilist.co)** - Primary metadata and discovery.
- **[TMDB](https://www.themoviedb.org)** - High-fidelity 4K images and episode data.
- **[Jikan](https://jikan.moe)** - MyAnimeList (MAL) metadata bridge.
- **[AnimeThemes](https://animethemes.moe)** - OP/ED video and music links.
- **[Manami Project](https://github.com/manami-project/anime-offline-database)** - Comprehensive ID mapping.

Please support these projects as they are the backbone of the anime developer community.

---
Maintained by the **AniSync Pipeline**.  
*Disclaimer: This repository is a community cache and does not host any video files.*
