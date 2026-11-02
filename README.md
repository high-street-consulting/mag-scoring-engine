# MAG Scoring Engine

- Old URL(s):
  - https://products.highstreet.work/NewScoringEngine/
- New URL: https://high-street-consulting.github.io/mag-scoring-engine/
- Migrated: 2026-11-02
- Source: IIS wwwroot folder `wwwroot\NewScoringEngine`
- Framework: ArcGIS Experience Builder 1.16 (developer edition export), build 22

## Changes from original

- `web.config` dropped (IIS-only MIME/cache/rewrite rules; GitHub Pages does not use it)
- `*.map` source maps dropped (0 files)
- empty `.nojekyll` added (skip the Jekyll build on GitHub Pages)

No application code was changed.
