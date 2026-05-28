---
"@geoprotocol/geo-sdk": patch
---

Lower the SDK-enforced minimum voting duration for DAO spaces to match the on-chain `MINIMUM_VOTING_DURATION` of 60 seconds. `MINIMUM_VOTING_DURATION` is now `60` and `MINIMUM_VOTING_DURATION_DAYS` is `1 / 24 / 60`. Previously the SDK rejected anything under 2 days even though the contract allowed it.
