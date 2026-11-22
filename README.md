# data — Sekai legacy update feed (fallback)

**Sekai has moved.** The app's home is now
[**ozipoetra/SekaiApp**](https://github.com/ozipoetra/SekaiApp) — downloads,
releases and the current update feed live there.

This repository exists for one reason only: Sekai versions **1.2.0 and
older** still read their update feed from this address
(`raw.githubusercontent.com/ozipoetra/data/main/animesekai.json`). The
`animesekai.json` here mirrors the latest feed from SekaiApp with
`mandatory: true`, so those installs are required to update — and the
update itself points the app at its new home, after which this feed is
never read again. `sponsor.json` is mirrored for the same reason.

**Maintainers:** on every new Sekai release, copy the fresh
`animesekai.json` (and `sponsor.json`, if it changed) from
ozipoetra/SekaiApp into this repo, or old installs stop being pushed
forward.
