# CC Bot Permission Scope

This document explains the Discord server permissions requested when adding **CC (Community Companion)** to a server, and why the bot may need them.

These permissions support CC's server setup, moderation, role management, and community features. Actual behavior also depends on which features are configured and enabled in a server.

## Requested permissions

| Permission | Why CC may need it |
|---|---|
| **Manage Server** | Access server-level configuration and retrieve invite information used by invite-tracking features. |
| **Manage Roles** | Assign or remove configured member roles, such as welcome and selectable roles. CC can only manage roles below its highest role in Discord's role hierarchy. |
| **Manage Channels** | Create or configure channels and update channel permission overwrites during setup. |
| **Kick Members** | Remove a member from the server when an authorized moderation action calls for a kick. |
| **Ban Members** | Ban members when an authorized moderation action or configured moderation rule calls for a ban. |
| **View Channels** | Access channels in which CC is permitted to view content, so it can operate in the appropriate server areas. |
| **Moderate Members** | Apply or remove timeouts for moderation actions. |
| **Send Messages** | Send bot replies, notices, welcome messages, and other configured community messages. |
| **Send Messages in Threads** | Reply within threads where CC is allowed to participate. |
| **Manage Messages** | Delete messages, including messages removed by moderation or cleanup features. |
| **Manage Threads** | Perform thread-management actions needed by supported features, such as managing or reopening relevant threads. |
| **Embed Links** | Send rich embedded messages for notices, information panels, and other bot responses. |
| **Attach Files** | Include files or attachments in supported messages when a feature requires them. |
| **Read Message History** | Read previous messages where needed for moderation context, message cleanup, or maintaining configured messages. |

## Important notes

- **Permissions are not a guarantee of unrestricted access.** Channel-specific permission overwrites and Discord's role hierarchy still apply.
- CC can only perform actions allowed by Discord and by the permissions it actually has in the server.
- Server administrators should review the requested permissions and only enable the features they intend to use.
- If a feature cannot work, check the bot's server role position and the permissions granted in the relevant channel.
- The requested permission set does not include the **Administrator** permission.

## Scope

This page documents the purpose of the permissions CC requests when installed in a Discord server. It is intended as a reference for server owners reviewing CC's access.

For more information about Discord permissions, see the [official Discord permissions documentation](https://discord.com/developers/docs/topics/permissions).
