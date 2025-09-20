<div align="center">
  <img src="./assets/cha-ching-logo-green.png" alt="Cha-Ching Logo" width="300"/>
  <h1>⚡️ Cha-Ching 🚀</h1>
</div>

**Cha-Ching** is all about engagement. Our goal is to help GitHub organizations involve builders by transforming activity into meaningful point-based rewards. 

Instead of traditional bounties, organizations set their own rules for rewarding contributions such as pull requests, issues, comments, and stars. Contributors earn $CHING points (ERC-1155), redeemable or convertible into stablecoins if organizations allow it.

This makes contributing more motivating, transparent, and rewarding for developers and AI agents. Cha-Ching also provides dashboards for contributors and organizations, plus AI-powered recommendations to connect skills of developers with opportunities.

<em>No middlemen. No spreadsheets. No manual work. Just seamless, **verifiable rewards** for real contributions.</em>

## 🧠 How does it work

Cha-Ching turns GitHub activity into $CHING points, on-chain rewards for contributors and AI agents.

🏛️ **For GitHub Organizations**

1.	**Install the Cha-Ching GitHub App**

    Choose the repositories you want to track contributions on.

2.	**Create a Bounty Campaign**
    
    Define a time window (e.g., 30 days) and set custom reward rules like:
    - "Merged PR = 100 $CHING"
	- "Comment on issue = 10 $CHING"
	- "Star repo = 5 $CHING"

3.	**Define Reward Points & Conversion Policy**

    Set how many $CHING points will be distributed during the epoch (e.g., 1,000,000 points. Optionally, describe your own redemption policy (e.g., “1,000 $CHING = $10 USDT”).

    > 💡 No real funds are required. The policy is informational and defined by each Org.

4.	**Cha-Ching Tracks Contributions Automatically**
    
    When a contributor performs a matching action (like submitting a PR or commenting), Cha-Ching:
	- Captures the event via GitHub Webhooks
	- Signs a metadata object
	- Stores it on Filecoin via the Synapse SDK as verifiable proof

5.	**Distribute Rewards**

    At the end of the epoch:
	- The Org can airdrop points to contributors (if authorized), or
	- Contributors can claim manually via GitHub login + WalletConnect


🧑‍💻 **For Contributors**

1.	**Contribute Freely**
    
    Open pull requests, comment on issues, star repos — no signup or wallet needed upfront.

2.	**Earn $CHING Automatically**

    If your activity matches an org’s rules during an active epoch, you earn $CHING points.

3.	**Claim Your Points**

    After the epoch ends, log in with GitHub and connect your wallet to claim your rewards.

4.	Use Your Points

    Depending on the org’s policy, $CHING can be:
	- Redeemed for stablecoins using a third-party solution 💸
	- Used as contributor karma 🏅
	- Showcased as part of your verifiable open-source portfolio 📜


> 🔐 All contributions and point awards are signed and stored on Filecoin for auditability, transparency, and decentralized verification.


## 🗂️ Cha-Ching Repositories Structure

* Backend: https://github.com/AxLabs/cha-ching-backend
* Frontend: https://github.com/AxLabs/cha-ching-app
* Contracts (ERC-1155): https://github.com/AxLabs/cha-ching-contracts

## 💡 Tech Stack

👉 **Next.js 15** – Frontend framework <br>
👉 **NextAuth.js** – GitHub OAuth authentication <br>
👉 **shadcn-ui** – Beautiful components <br>
👉 **Hardhat/Foundry** – EVM smart contract toolkit <br>
👉 **Node.js** – Backend API server (NestJS) <br>
👉 **Probot** – GitHub bot for automations <br>
👉 **pnpm workspaces** – Monorepo dependency management <br>
👉 **MongoDB** - NoSQL DB for fast queries <br>
👉 **Synapse SDK (Filecoin)** - TypeScript interface for interacting with FilecoinWarmStorage <br>

---

## 🌍 Live Demo

It's not yet live, sorry!

👉 But, stay tuned: **[https://cha-ching.it](https://cha-ching.it)**

---

## 🪙 License

Apache License 2.0. See `LICENSE` for details.

---

### 💬 Questions or Ideas?

Open an issue – let’s build together!

---

> Let’s engage and reward builders with **Cha-Ching**! 💸✨
