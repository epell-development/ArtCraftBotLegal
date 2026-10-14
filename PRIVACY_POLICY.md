# ArtCraft Bot — Privacy Policy

**Effective date:** 14 October 2026  
**Last updated:** 14 October 2026

ArtCraft ("we", "us", or "our") operates **ArtCraft Bot** (the "Bot"), which provides Discord server management and moderation features. This Privacy Policy explains what information the Bot can access, how it uses and stores that information, when it may be disclosed, and how you can request access or deletion.

This policy applies to data processed by ArtCraft Bot. Discord separately processes information under its own [Privacy Policy](https://discord.com/privacy).

## 1. Information We Process

Depending on enabled functionality, server settings, and your interactions with the Bot, we may process:

| Category | Examples | Purpose |
| --- | --- | --- |
| Discord identifiers | User IDs, moderator IDs, server IDs, role IDs, channel IDs, message IDs | Identify users and servers, apply permissions, and associate records with actions |
| Moderation records | Case ID, action type, reason or staff note, moderator ID, action time, whether a direct-message notification was sent, and whether a case was voided | Maintain moderation history, support staff review, and document actions |
| Message information | Message text and edited/deleted message excerpts, attachment filenames, message identifiers, and channel references | Provide configured message event logs, detect protected mentions, and carry out message deletion commands |
| Server activity | Member joins or departures, bans or unbans, and other events supported by enabled logs | Operate staff and security logs |
| Server configuration | Protected user and role IDs, the server ID, and whether mention monitoring is enabled | Preserve administrator settings |
| Information from Discord | Display names, usernames, member/account details, roles, and timestamps made available through Discord | Display commands, check permissions, and generate event or moderation notices |
| Operational diagnostics | Errors and technical events that may include relevant Discord identifiers | Troubleshoot failures, maintain reliability, and investigate abuse |

**Message access:** The Bot has Discord's *Message Content* intent enabled. It may inspect messages necessary for configured features. When event logging is enabled, it may post edited or deleted message excerpts to designated Discord logging channels. These excerpts can remain visible there until those Discord messages are removed.

We do not ask users to provide passwords, payment card details, or government identification through the Bot. Please do not place sensitive information in moderation reasons, commands, or public channels.

## 2. How Information Is Collected

Information may be received when:

- You join, leave, send or edit messages in, or are moderated within a Discord server using the Bot.
- A staff member uses a moderation or administrative command.
- An administrator configures protected mention settings.
- Discord sends the Bot events or information through its API.
- The Bot encounters an error during normal operation.

The information available depends on Discord permissions, enabled intents, server configurations, and the Bot's deployed features.

## 3. Why We Use Information

We process information to:

1. Provide Bot commands, moderation, and community management features.
2. Apply server permissions and prevent unauthorised use of administrative commands.
3. Record and review moderation outcomes, including warnings and staff notes.
4. Identify configured protected mentions and issue temporary warnings.
5. Notify server staff or affected users about relevant events and actions.
6. Detect misuse, maintain security, diagnose faults, and improve reliability.
7. Comply with applicable legal obligations and respond to lawful requests.

We do **not** use Bot data for targeted advertising or sell personal information.

## 4. Where Information Is Stored

The reviewed Bot code writes moderation records to a local JSON file (`moderations.json`) and protected mention settings to a local configuration file (`data/mention_monitor.json`). In addition, event logs and moderation notices may be posted as Discord messages in channels or direct messages.

This is soon to be moved into a proper MariaDB Database hosted on the same server.

The location of the bot's hosting environment is Sydney, NSW, Australia. We do not represent that all data is stored exclusively in Australia. Information sent through Discord is also subject to Discord's infrastructure and practices.

## 5. Who Can Access Information

Information may be accessible to:

- Authorised ArtCraft personnel who maintain or operate the Bot and its stored data.
- Server moderators and administrators with access to Bot commands, moderation history, or designated logging channels, as determined by permissions and configuration.
- Discord, as the platform that carries the relevant messages, events, and interactions.
- Infrastructure or technical service providers involved in operating the Bot, if applicable and subject to their service arrangements.
- Authorities or other parties where disclosure is legally required or reasonably necessary to protect users, security, or legal rights.

Moderation histories and server log messages may remain accessible to authorised staff even after an individual leaves a server.

## 6. Data Retention

The version of ArtCraft Bot reviewed does **not** implement automatic expiry or deletion of stored moderation records or protected mention configurations. Accordingly, these records may be retained until they are manually deleted, corrected, or removed as part of a change to the service.

Voiding a moderation record generally marks it as voided rather than deleting the record. Logs posted to Discord channels or direct messages remain subject to the retention and deletion practices of Discord and the people controlling those destinations. Temporary protected-mention warning replies are configured to disappear after approximately **10 seconds**; this does not automatically delete the underlying message or other logs.

We aim to retain personal information only for as long as reasonably needed for legitimate moderation, operational, security, and legal purposes. We will assess requests for deletion against those needs and applicable law. **A fixed retention period has not been implemented in the current Bot code.**

## 7. Security

We take reasonable steps to protect Bot data through Discord permissions, role-based command restrictions, and controlled access to its operating environment. However, no system is completely secure. Discord channels, local data files, backups, and infrastructure require appropriate administrator safeguards.

If you become aware of a suspected privacy or security issue, please contact us through our official support channels.

## 8. Your Privacy Choices and Requests

You may contact us to:

- Ask what personal information the Bot holds about you.
- Request correction of inaccurate information.
- Request deletion of information that is no longer required, where appropriate.
- Ask questions or raise concerns about how your information is processed.

For requests, provide your **Discord user ID** and enough context to identify the relevant server or moderation record. **Do not send your Discord password or authentication token.** We may need to verify that you are entitled to act for the relevant account.

Some information may need to be retained for legitimate moderation, security, or legal reasons. We cannot guarantee removal of records independently stored or controlled by Discord or a server administrator. Removing the Bot from a server or leaving that server does not by itself trigger deletion of retained records.

## 9. Children and Younger Users

The Bot is intended for people eligible to use Discord under Discord's age requirements and applicable laws. We do not intentionally request sensitive personal information from children. If you believe information relating to a minor has been handled inappropriately, please contact us so the concern can be reviewed.

## 10. International Processing

Because the Bot operates through Discord and may use infrastructure outside your location, information may be processed or accessed internationally. The country of the current Bot host has not been verified from the reviewed project and should be confirmed before making country-specific hosting commitments.

## 11. Australian Privacy Considerations

Individually from ArtCraft, the ArtCraft Server Management Bot operates from Australia. We aim to handle personal information consistently with applicable Australian privacy requirements to the extent they apply to our operations. Nothing in this policy limits statutory rights available to you under applicable law.

## 12. Changes to This Policy

We may revise this Privacy Policy if Bot features, data practices, third-party services, or legal requirements change. We will update the date above and take reasonable steps to notify users of material changes.

## 13. Contact Us

For privacy enquiries, access or deletion requests, and security concerns, contact ArtCraft via:

- **Website:** https://getartcraft.com/
- **Support Discord:** https://discord.gg/artcraft

Please identify your request as **"ArtCraft Bot Privacy Request"** so it can be routed appropriately.

For conditions governing Bot use, see our [Terms of Service](./TERMS_OF_SERVICE.md).
