# QXP Economy & Tactical Syndicate Framework

A high-fidelity, tactical roleplay economy simulation bot built for Discord using **Discord.js v14** and **Node.js**. The application features an advanced continuous compounding credit engine, custom alphanumeric network identities, tiered banking infrastructures, live world market clock cycles, and real-time transaction tracking through an autonomous AI Sentinel module.

## 🛠️ Core Technical Features

*   **Mandatory Network Registration:** Restricts global economic loops via an identity firewall until an operative registers an explicit alphanumeric user ID.
*   **Venture Debt & Credit Expansion:** Implements an advanced time-delta mathematical calculator approximating real-time interest compounding (`F = P * e^(r*t)`) dynamically on state interaction without cron dependency.
*   **Progressive Banking Infrastructure:** Features 10 progressive structural upgrade tiers scaling storage limits up to $5 Billion, concluding with absolute PvP robbery immunity at Level 10.
*   **Corporate Alliances (Crews):** Multi-tenant server-wide gang mechanics providing progressive labor yield multipliers based on collaborative player roster density.
*   **Dynamic Heartbeat Events:** Probability matrix running on a 5% trigger interval that overrides global asset volatility and modifies live server wages/corporate income.

---

## 💻 Command Dictionary Layout

### 🆔 Identity & Dossier Portal
*   `/profile register <id>` - Claims and registers a unique alphanumeric identifier (3-30 characters) globally.
*   `/profile view [target]` - Pulls a secure cryptographic dossier containing net worth, system entry date, bank level, active reputation buffs, and command statistics.

### 💼 Commercial Infrastructure & Banking
*   `/economy balance` - Inspects current liquid wallet cash alongside secure bank vault reserves.
*   `/economy work` - Shift deployment allowing operatives to harvest wages (Subject to Overtime chance and Global Multipliers).
*   `/economy deposit <amount|all>` - Routes cash away from unbanked exposed state into vault storage.
*   `/economy withdraw <amount|all>` - Liquidates secure bank vault assets back to physical cash.
*   `/economy upgrade_bank` - Upgrades infrastructure level to scale vault caps and reduce credit risk.

### 📉 Illicit Speculation & Open Markets
*   `/heist hack` - Active mainframe minigame bypass. Bypassed automatically if a user holds a primed `Quantum Decryptor` hardware module.
*   `/heist rob <target>` - Launches a high-risk PvP ambush against a target's unbanked wallet liquidity. Locked out if the target holds a Level 10 Vault.
*   `/blackmarket shop` - Opens terminal catalog for illicit asset modules (EMP Grenades, Decryptors, Burner Phones).
*   `/blackmarket buy <item> [amount]` - Purchase underground assets (Applies 20% flat discount to users with Syndicate Outlaw status).
*   `/blackmarket use <item>` - Primes an inventory element for the next operational run.
*   `/crypto market` - Displays a paginated global live cryptographic ledger covering 50 indexed assets.
*   `/crypto portfolio` - Evaluates personal asset tokens against real-time market trends.
*   `/crypto buy <coin> <amount_type> [custom_amount]` - Market-filled asset purchasing (Applies 50% gas subsidy to Global Regulators).
*   `/crypto sell <coin> <amount_type> [custom_amount]` - Liquidates asset tokens back into wallet cash.

### 🏦 Venture Financing & Capital Loans
*   `/credit status` - Inspects live outstanding loan liability, current interest tracking, and credit rating.
*   `/credit borrow <amount>` - Draws capital funding down from the network (Capped dynamically by bank capacity; accrues compounding interest).
*   `/credit repay <amount>` - Settles outstanding principal and interest balances to clear active asset locks.

### ⚙️ Server Control & Administration
*   `/setup event_channel <channel>` - Restricts global macro-economic financial world alerts to a designated server channel.
*   `/setup starting_cash <amount>` - Sets default wallet boundaries ($100 to $1,000) for uninitialized operatives.
*   `/staff-menu status` - Executive portal inspecting memory load (RAM), gateway latency, and database connectivity.
*   `/staff-menu economy <target> <account> <action> <amount>` - Executive ledger balance overrides.
*   `/staff-menu security audit <target>` - Exposes historical background records compiled by the AI Sentinel logger.
*   `/staff-menu security ban/unban <target>` - Revokes or reinstates a network user's command interaction capability.
