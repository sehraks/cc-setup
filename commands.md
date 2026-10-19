# CC Command Guide

This is a public, user-facing overview of CC's Discord slash commands. The exact commands and options shown in Discord may vary with the current deployment, your permissions, server configuration, and feature availability. Use Discord's slash-command suggestions and CC's `/help` command as the source of truth for your server.

## Moderation and staff tools

| Command | Purpose |
|---|---|
| `/kick` | Remove a member from the server, when authorized. |
| `/ban` | Ban a member, when authorized. |
| `/unban` | Remove a ban, when authorized. |
| `/mute` | Apply a timed timeout to a member. |
| `/unmute` | Remove an active timeout. |
| `/warn` | Record a member offense under the server's moderation rules. |
| `/history` | Review a member's recorded offense history. |
| `/removeoffense` | Remove an individual offense record, when authorized. |
| `/clearhistory` | Clear an offense history; use carefully because this is destructive. |
| `/cleanup` | Bulk-delete a limited number of messages, when permitted. |

These commands require appropriate staff roles and Discord permissions. The bot may apply additional protections to staff members.

## Server and member information

| Command | Purpose |
|---|---|
| `/serverinfo` | Show server details and statistics. |
| `/userinfo` | Show information about a member or yourself. |
| `/myroles` | Select or update available personal roles. |
| `/help` | Show help and point to command information. |

## Server setup and controls

| Command | Purpose |
|---|---|
| `/setup roles` | Set up a role picker in the current channel, where available. |
| `/setup colors` | Set up a color picker in the current channel, where available. |
| `/open` and `/close` | Control the bot's configured activity mode, for authorized users. |
| `/chat on` and `/chat off` | Enable or lock supported channel chat behavior. |
| `/moderator grant` and `/moderator remove` | Manage moderator role assignments, when authorized. |
| `/admin grant` and `/admin remove` | Manage admin role assignments, when authorized. |

Some setup and Companion-channel controls are restricted to the server owner or bot owner.

## Temporary rooms

| Command | Purpose |
|---|---|
| `/setroom` | Create or assign a dynamic room. |
| `/removeroom` | Remove a dynamic room. |
| `/listrooms` | List active dynamic rooms. |
| `/roomPermissions` | Configure room permissions. |
| `/roomrestrict` | Restrict a room to selected roles or users. |
| `/unroomrestrict` | Remove room restrictions. |

Availability depends on how the server has configured room features.

## Reminders and social features

| Command | Purpose |
|---|---|
| `/reminder` | Schedule a reminder. |
| `/confess` | Submit an anonymous confession where enabled. |
| `/roast` | Generate a playful roast. |
| `/shawty random` | Retrieve a saved social post, where authorized. |

Use community features respectfully and follow the server's rules.

## Music and media

| Command | Purpose |
|---|---|
| `/spotify` | Use supported Spotify-related search/download functionality. |
| `/youtube` | Use supported YouTube media functionality. |
| `/tiktok` | Retrieve supported TikTok media. |
| `/instagram` | Retrieve supported Instagram media. |
| `/facebook` | Retrieve supported Facebook media. |
| `/lyrics` | Find lyrics for a title and artist. |

Media commands may be limited to designated channels or server Boosters. Availability depends on connected services, platform restrictions, and current service status.

## Guild Panel

CC has a browser-based Guild Panel for supported server settings and bot status. Sign-in uses Discord authorization. You must have the required server permissions and CC must be available to the server. Open the [CC home page](https://sehraks-dc-bot-production.up.railway.app/) to find the current panel entry point.

The old private-token login flow is retired. Do not look for or share panel tokens; use the official Discord sign-in flow.

## Permission reminders

- Only use moderation and server-management commands if you are authorized.
- A command may be hidden or rejected if you lack the required role or Discord permission.
- Channel restrictions, Booster requirements, configuration, and service outages can affect availability.
- Command names and options can change. Use `/help` and Discord's slash-command suggestions for current options.

[Back to the CC overview](README.md)
