# Hmusic — Music Discovery App

A music browser built on the Shazam Core API: top charts, genre filtering,
artist pages, song details with lyrics, and a persistent audio player that
keeps playing as you navigate.

## What it does

- Worldwide and country-specific top charts
- "Around you" — charts for the listener's own country, resolved by IP geolocation
- Browse by genre (pop, hip-hop, dance, electronic, soul, rock, latin and more)
- Artist pages with discography
- Song details with lyrics and related tracks
- Search across songs and artists
- Audio player with seek bar, volume, shuffle, repeat and next/previous

## Stack

React · Vite · Redux Toolkit (RTK Query) · React Router · Tailwind CSS ·
Swiper · Shazam Core API via RapidAPI

## Running locally

```bash
npm install
cp .env.example .env
npm run dev
```

| Variable | Purpose |
|---|---|
| `VITE_SHAZAM_CORE_RAPID_API_KEY` | RapidAPI key for the Shazam Core endpoints |
| `VITE_GEO_API_KEY` | IP geolocation key, used by the "Around you" page |

## Credit

The app concept and layout follow a publicly published React course build. The
implementation here is my own work.
