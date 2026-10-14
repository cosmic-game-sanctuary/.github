# Cosmic Game Sanctuary (CGS)

**Buy a game once, own it forever. Built natively on Arc Mainnet.**

[**🚀 Live Store (Arc Mainnet)**](https://cgs.blackslate.me) · [**🧪 Free Testnet Twin (With Faucet)**](https://testnet.cgs.blackslate.me) · [**📐 Architecture & Docs**](https://github.com/cosmic-game-sanctuary/CGS-docs)

---

### Why We Exist
Card networks and storefronts (Steam, itch.io, PlayStation, Xbox) can delist games you paid for overnight because you only rent a revocable license. Meanwhile, existing Web3 game stores are too clunky for everyday gamers because nobody wants to buy a separate volatile token just to pay gas for a $2 indie game.

We started **CGS** at ETHOnline 2026 and ported the entire platform to **Arc Mainnet** because Arc uses **US dollar-pegged USDC for both game purchases and ultra-low gas fees (~$0.007)**. That lets us give gamers a familiar Web2 storefront with real on-chain ownership—and lets indie devs keep **95% of their revenue** paid out instantly.

---

### 📦 Repositories

| Repository | Stack | What It Does |
| :--- | :--- | :--- |
| **[CGS-contracts](https://github.com/cosmic-game-sanctuary/CGS-contracts)** | Solidity (Foundry) | Verified Arc Mainnet contracts: `GameRegistry`, unrevocable `GameKey` (ERC-721), and `VaultFactory` per-game revenue split vaults. |
| **[CGS-client](https://github.com/cosmic-game-sanctuary/CGS-client)** | TypeScript / React | Storefront UI with Privy email login, single-token USDC checkout, trial streaming, and publisher dashboard. |
| **[CGS-server](https://github.com/cosmic-game-sanctuary/CGS-server)** | TypeScript / Node | Backend managing **x402** pay-per-minute trials via Circle Gateway and autonomous **ERC-8004** deal-buying agents. |
| **[CGS-docs](https://github.com/cosmic-game-sanctuary/CGS-docs)** | Markdown | System design, contract mechanics, and Arc Mainnet deployment specs. |

---

### ⛓️ Verified Contracts on Arc Mainnet

| Contract | Arc Mainnet Address | Role |
| :--- | :--- | :--- |
| **`GameRegistry`** | `0x864a…4C6c` *(replace with full 0x link to explorer.arc.io)* | On-chain game catalog & pricing |
| **`GameKey`** | `0x3938…11B6` *(replace with full 0x link to explorer.arc.io)* | Unrevocable ERC-721 game license (no burn/pause/admin) |
| **`VaultFactory`** | `0xd2ca…95d0` *(replace with full 0x link to explorer.arc.io)* | Deploys immutable per-game USDC revenue-split vaults |
