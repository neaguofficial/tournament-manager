# Community Draft & Tournament Manager

**Community Draft & Tournament Manager** is a non-commercial tournament organization and matchmaking utility built for our private League of Legends Discord community. 

The tool automates 5v5 custom lobby creation, balances teams based on players' peak ranked tiers, and tracks post-game match statistics to support live community broadcasts.

---

## Core Features

* **Peak-Rank Team Balancing:** Automatically generates balanced 5v5 rosters from registered Discord members using their peak ranked tiers to ensure fair and competitive series.
* **Automated Tournament Lobbies:** Uses official Tournament Codes to spin up 5v5 Summoner's Rift Tournament Draft lobbies and capture match results automatically.
* **Flexible Bracket Formats:** Supports Best-of-3 (BO3) series, 3-team second-chance brackets, and Double Elimination (Winners & Losers Bracket) formats.
* **Live Broadcast & Casting Support:** Pulls post-match statistics (picks, bans, KDA, gold, and damage) to populate live scoreboards and stream overlays for our community casters.

---

## Riot Games API Usage

This project strictly adheres to the Riot Games Developer Policies and uses the following endpoints:

* **`Tournament-v5` / `Tournament-Stub-v5`:** Generating Tournament Codes for custom 5v5 Tournament Draft games and receiving match completion callbacks.
* **`Account-v1` & `Summoner-v4`:** Verifying participant Riot IDs during event sign-ups.
* **`League-v4`:** Retrieving current and peak ranked tier data exclusively for pre-tournament team balancing.
* **`Match-v5`:** Fetching post-match telemetry and summary statistics for tournament standings and broadcast overlays.

---

## Community & Participation

* **Entry Fee:** 100% Free to enter (no buy-ins, entry fees, or virtual currencies).
* **Regions:** Europe Nordic & East (EUN1) / Europe West (EUW1).
* **Official Discord Community:** [Join our Discord Server](https://discord.gg/rCjF7wmeU4)

---

## Legal Disclaimer

*Community Draft & Tournament Manager* is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
