# Forge Fitness Data

Shared **read-only supplement discovery catalog** for the Forge Fitness app.

## Current data

- [Supplement index](catalog/supplements.json) — names and aliases for fast autocomplete. Entries are **not** medically reviewed research profiles.
- [Profile schema example](schemas/profile.example.json) — proposed format for evidence-linked content.
- [Catalog workflow](docs/CONTRIBUTING.md) — AI draft, review and publishing rules.

## How search is intended to work

The app downloads the index, caches it on-device, and filters matches on each keystroke. For unknown names, a separately configured AI service may suggest candidates; these must be classified and reviewed before entering the shared catalog. Research must not be represented as clinically verified unless its sources and claims have been checked.

**No individual health logs, API keys, or user information belong in this public repository.** This repository intentionally has no software/content license. Public visibility does not mean public permission to reuse the original contents.

Health information here is educational and is not medical advice.
