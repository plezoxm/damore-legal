# Privacy Policy — Damore Bot

_Last updated: 31 May 2026_

This Privacy Policy explains what data **Damore Bot** ("the Bot", "we", "us") collects,
why, how it is stored, and your choices. By using the Bot you consent to the practices
described here. The Bot runs inside Discord and is also subject to
[Discord's Privacy Policy](https://discord.com/privacy).

## 1. Who controls the data

The Bot is operated by its developer(s). Each server's administrators act as the
controllers of data generated on their own server. Questions or requests can be sent
via the support server (see §8).

## 2. What we store

The Bot stores the **minimum data needed to provide its features**. Data is keyed by
Discord IDs (which are not secret) in the form `guildId:userId`.

| Data | Examples | Why |
|------|----------|-----|
| Identifiers | Discord user IDs, server (guild) IDs, role IDs, channel IDs | To attribute XP, balances, and settings to the right user/server |
| Leveling | XP totals per server | Levels, ranks, leaderboards, level roles |
| Economy | Coin/bank balances, daily streaks, inventory, businesses, stock holdings, farm/market/auction state, jail status | To run the virtual economy & games |
| Profiles | Optional self-provided bio, status, pronouns, birthday (MM-DD), location, favorite games | The `!profile` feature (only what a user chooses to enter) |
| Moderation | Warnings, mutes/bans/kicks history, the moderator who acted, reasons, timestamps | Moderation history & accountability tools |
| Activity | Per-server "last seen" timestamps, hourly message counts, voice activity minutes | Welcome-back messages, hourly stats, voice XP |
| Missed pings | For the Welcome-Back feature: who mentioned an offline user, the channel, a link, a timestamp, and a short snippet (≤200 chars) of the message | To show a returning member the pings they missed |
| Server config | Channels, roles, thresholds, toggles, custom coin emoji, automod word list | To remember each server's setup |
| Premium/trial | Whether a server is whitelisted/subscribed, trial start, and which user started a trial | Access control & one-time trial enforcement |
| Game stats | GeoGuessr streaks, which photos a user has seen | To run the geo game without repeats |

We do **not** intentionally store full message history. Messages are processed
**transiently** for automod (banned-word checks) and for the message edit/delete logs
(which forward the relevant content to a server-configured log channel chosen by that
server's admins). The only message content we persist is the short Welcome-Back ping
snippet described above.

## 3. What we do NOT do

- We do **not** sell, rent, or trade your data.
- We do **not** use your data for advertising.
- We do **not** collect payment card details inside the Bot. Any subscription billing
  is handled by the external payment provider shown at checkout.
- We do **not** request message content beyond what the listed features require.

## 4. Discord intents / permissions

To function, the Bot uses Discord Gateway intents including server members, message
content, presence, and voice state. These are used only to power the features above
(e.g. presence is used for "last seen"/welcome-back; message content for automod and
XP). The Bot only acts within servers it has been invited to.

## 5. Data retention & deletion

- Configuration and user records persist while the Bot is in your server so features
  keep working between sessions.
- **Server owners** can wipe their server's economy data via `!setup` → Economy →
  *Reset entire economy*, and can disable features that collect activity data.
- **Users** may request deletion of their data, and **server owners** may request
  deletion of their server's data, by contacting us in the support server (§8). We will
  remove the requested records within a reasonable period, except where retention is
  required to enforce these terms (e.g. one-time trial abuse prevention) or by law.
- Transient data (e.g. caches) is cleared automatically over time or on restart.

## 6. Security

Data is stored on the host operating the Bot. We take reasonable measures to protect
it, but no system is perfectly secure. Discord IDs are not confidential by nature.

## 7. Children

The Bot is not directed to anyone under Discord's minimum age requirement. We do not
knowingly collect data from such users; if you believe we have, contact us for removal.

## 8. Contact & requests

For privacy questions, data access, or deletion requests, contact us in the support
server: **https://discord.gg/weUh7cRrVa**

## 9. Changes

We may update this Policy. Material changes will be announced in the support server
where reasonably possible. Continued use after changes constitutes acceptance.
