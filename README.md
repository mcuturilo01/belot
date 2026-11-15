# Belot

Bulgarian belot (belot.bg rules) for 4 players on their phones. No app, no account.

**Play:** https://mcuturilo01.github.io/belot/

1. Open the link, enter your name, tap **Create table**.
2. Tap **Copy invite link** and send it to your friends.
3. Everyone picks a seat. Empty seats can be filled with bots.
4. The host keeps the page open during the game.

Practice alone: tap **Practice vs 3 bots**.

## Game server (optional, recommended)

`server/` is a small Cloudflare Worker that runs the table, so phones can switch apps or lose signal
and come back to the same game. Deploy it from the Cloudflare dashboard by importing this repository
with root directory `server`. Until the server address is set in the game, phones connect directly
to each other.
