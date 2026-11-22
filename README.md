# Berufsfeuerwehr NRW – Discord Bot & Dashboard

Node.js 20+ Discord bot with an Express dashboard.

## Railway variables
Set `DISCORD_TOKEN`, `DISCORD_CLIENT_ID`, `DISCORD_CLIENT_SECRET`, `DISCORD_GUILD_ID`, `SESSION_SECRET`, `ADMIN_USER_IDS`, `PUBLIC_BASE_URL`, `WEBSITE_URL`, and `DISCORD_REDIRECT_URI`. The redirect URL must exactly match the Discord Developer Portal OAuth2 redirect.

Enable the Server Members and Message Content privileged intents in the Discord Developer Portal. Invite the bot with `bot` and `applications.commands` scopes and permissions for messages, embeds, moderation, role management, and channel creation as required.

## Resident registry (fictional RP data only)
- `/einwohner-anmelden` lets a member create or update their own fictional character record.
- `/einwohner-suchen name:` is restricted to the role configured as `police` in the dashboard.
- Set the Police role in Dashboard → Rollen → Polizei-Rolle, then save.
- Store only fictional RP names, dates, addresses and phone numbers. Do not enter real personal data.

## Run
`npm install && npm start`
