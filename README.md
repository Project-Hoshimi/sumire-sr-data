# sumire-sr data

Unofficial game data used by the [sumire-sr](https://github.com/project-hoshimi/sumire-sr)
private-server project: master-data tables and blobs, diaries, and scrubbed
captured RPC responses.

This repository is **not affiliated with, endorsed by, or supported by**
QualiArts, Bandai Namco, or the IDOLY PRIDE rights holders. Game data and
captures remain the property of their respective owners; use them only if you
are entitled to the underlying game data in your jurisdiction.

Account identifiers in `captures/` are synthetic placeholders. Do not add real
account tokens, Firebase UIDs, user ids, player names, emails, or IP addresses.

Fetch it into a public clone with `npm run data:fetch` (see the server repo's
`DATA_VERSION` for the pinned tag), then run the database migrations and master
seed.
