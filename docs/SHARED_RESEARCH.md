# Shared AI research profiles

The Forge Fitness app looks for `/profiles/<normalized-name>.json` before generating new research. Profiles are explicitly marked `ai_generated_unverified` and are educational, not medical advice.

Public GitHub cannot safely accept anonymous write operations directly from an iPhone app. The writer must run behind a protected server-side service with an authentication mechanism, rate limits, category checks, and safeguards against fabricated sources. **Never put GitHub write credentials or secrets in the mobile app.**

The Forge Fitness v0.3.4 source includes a protected Cloudflare Worker example and documents remaining deployment steps. Automatic cross-user publication is not enabled until that service is deployed. User intake data must never be uploaded here.
