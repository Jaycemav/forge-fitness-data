# Catalog workflow

1. The app downloads `catalog/supplements.json` and caches it for local autocomplete.
2. An unknown query can be resolved with AI after a debounce. New candidate names must be classified and deduplicated before being proposed for the catalog.
3. AI-generated health profiles are **drafts**, never automatically published as validated medical advice.
4. Review ingredient identity, evidence, clinical uncertainty, references and URLs before setting a profile to `published`.
5. Never commit API keys, personal intake logs, or identifiable health information.
6. The app must enforce category visibility independently of this public repository. The supplement catalog alone does not grant access to additional categories.
7. GitHub contents are public and can be read by anyone. No license has been added.

This is a read-only distribution catalog, not a user-writable production database.
