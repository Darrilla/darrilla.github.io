# Darrilla Software

The public website for Darrilla Software at https://darrilla.com, hosted by
GitHub Pages from the `main` branch of this repository.

- `/`: studio home and games.
- `/about/`: studio, mascot, and replayable publisher intro.
- `/chess-clock/`: overview, with `/support/` and `/privacy/` underneath.
- `/arrowzilla/`: overview, with matching support and privacy pages.

The site uses a shared Jekyll layout and CSS, with no external fonts, trackers,
or client-side framework. Existing Chess Clock URLs and Google verification
files are retained. `CNAME` and `_config.yml` use `darrilla.com`.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000. For a static build, use
`bundle exec jekyll build`.

## Assets and copy

The mascot and Chess Clock icon come from the chess-clock app. The red panda
illustrations and publisher intro come from ArrowZilla. Website copies are
optimized for size; the app repositories remain the source for the originals.
The ArrowZilla illustrations are labeled as artwork rather than screenshots.

ArrowZilla is described as in development; add store links when available.
Its privacy page covers the current prototype. Review that policy when adding
analytics, ads, purchases, or online services.
