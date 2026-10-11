# token-goblin-update-feed
Version-only update metadata for Token Goblin.

- `beta/stable.json`: public-download beta channel for clients starting at 1.3.1.
- `private-testers/stable.json`: legacy channel for older private-download clients.

[Download Token Goblin](https://github.com/cmike-1011/token-goblin-downloads/releases).
No GitHub account or GitHub App is required for the public downloads. Older
clients need one direct download to migrate to the public channel.

The schema's `private_testers` identifier is retained for parser compatibility;
it is not an access restriction. This repository contains metadata and download
instructions only. Application source remains private. Publish packages before
advancing their platform entries. No automatic installer execution is provided.
