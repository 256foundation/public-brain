# 256Brain

The 256 Foundation's public mining knowledge archive.

## Collections

- [POD256 transcripts](sources/pod256/README.md): episodes published from October 7, 2024 through October 7, 2026, organized by year and episode. Includes readable transcripts, original publisher files, an episode index, and source metadata.

## Updating POD256

Run from the repository root with Python 3.9+ and curl:

```sh
python3 scripts/download_pod256.py --start 2024-10-07 --end 2026-10-07
```

Omit the date arguments to select the past two years ending today. The downloader records episodes without published transcripts as gaps in the index and manifest. See the collection's README for refresh and reproduction options.

## Provenance

POD256 documents come from the publisher's public RSS feed and transcript URLs. Source URLs and SHA-256 checksums are recorded in the collection manifest. Machine transcripts retain the publisher's wording; project names, technical terms, quotations, and speaker identities need verification against the audio when accuracy matters.

This repository does not assign a new license to the publisher's source material.
