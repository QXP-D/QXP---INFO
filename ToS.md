### 2. `PRIVACY_POLICY.md`
*A formal regulatory policy declaration detailing data ingestion scopes to meet Discord Developer Policy section 3 requirements.*

```markdown
# Privacy Policy for QXP Network Application

**Effective Date:** June 7, 2026

This Privacy Policy explains how the QXP Application ("the Bot", "we", "us") collects, processes, stores, and protects data gathered from Discord users and servers ("Guilds"). By adding the Bot to your server or interacting with its features, you explicitly agree to the processing behaviors outlined in this document.

## 1. Data We Collect
To provide a secure and functional text-based economy simulation game, the Bot collects and logs the following minimal categories of data:
*   **User Identifiers:** Discord User IDs (`userId`), Usernames, and custom text strings provided voluntarily by the user during profile registration (`networkId`).
*   **Guild Identifiers:** Discord Server IDs (`guildId`) and Channel IDs (`eventChannelId`) used to localize configuration settings and economic balances per server.
*   **Game Telemetry State:** Numeric representations of fictional balances (virtual wallet, virtual bank, virtual inventory item counts, virtual business levels, and user-initiated command usage count analytics).
*   **Security Logs:** Timestamps and technical execution text records regarding internal command failures, transaction histories, or bot-level disciplinary flags managed by our automatic script loggers.

## 2. What We Do NOT Collect
*   We **never** read, log, cache, or store human conversational text messages within your channels.
*   We **never** process or request personal real-world information, including names, emails, passwords, location data, or payment information.
*   The Bot operates entirely on explicit Slash Command interactions.

## 3. How We Use Data
Collected data is used solely to facilitate gameplay mechanics within your specific Discord server:
*   Tracking simulation progression (saving virtual cash and items).
*   Enforcing game constraints (cooldown limits, loan compounding debt, and server ban states).
*   Routing randomized world event messages to designated text channels specified by server admins.

## 4. Data Retention & Deletion
*   **Retention:** Data profiles are stored persistently within an encrypted MongoDB database to maintain your progression across active gaming sessions.
*   **Automated Purges:** If the Bot is kicked or removed from a Discord server, the server-wide configurations are retained but remain inert. 
*   **Manual Deletion Requests:** Any user can request the permanent and absolute erasure of their financial profiles from our database infrastructure by contacting the development team directly or submitting an account reset inquiry via our dedicated support channels. Deletion requests are fulfilled within 72 hours.

## 5. Third-Party Sharing
We do not sell, trade, rent, or lease any portion of user data to third-party ad networks, data brokers, or monetization networks. Data is strictly processed via our secure hosting environments (Render) and database backends (MongoDB Atlas).

## 6. Contact & Support
For data privacy inquiries, access requests, or emergency deletion requests, please contact the development staff directly via the official QXP support server network link displayed on the application profile card.
