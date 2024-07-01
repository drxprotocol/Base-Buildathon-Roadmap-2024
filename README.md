# Base Buildathon Roadmap 2024

# Drake Exchange Base Buildathon Roadmap 2024

## Before the Buildathon: 2023/03/01 - 2024/06/01

For a year leading up to the Buildathon, Drake developed the core aspects of the protocol in stealth. This included the on-chain smart contract architecture, core trading logic, risk control, automation, oracle implementation, trading frontend UI integration, and the counterparty liquidity vault.

## During the Buildathon:  2024/06/01 -  2024/06/30

### Tokenized Funding Rate Vault Development

We have developed and deployed the smart contracts for our tokenized funding rate vault. Additionally, we have automated the on-chain process for opening and closing positions on Base Sepolia.

### Coinbase Smart Wallet and Paymaster Integration

We developed the integration for multiple types of wallet connections, including EOA wallets and AA wallets. We prioritize the Coinbase Smart Wallet as the first suggested option, allowing users to easily create an account and enable gas-free trading through the Coinbase Paymaster.

### Paper Trading Competition

**Social Trading with Frame integration**

To make trading more social and interactive during the Paper Trading Competition, we implemented features such as a boost to PnL based on the PnL of users you have referred, as well as a leaderboard so users can see where they rank compared to others.

On top of the leaderboard and referral boost, we implemented Farcaster Frames, so that users can easily share their PNL, referral, and feedback stats to Farcaster in a fun and interactive way.  The initial Farcaster Frame shows the overall leaderboard, then any user can click “Check my Drake Rank” to see what their paper trading competition stats are.  

### User feedback Iteration

Shortly after we launched the paper trading competition we began to receive user feedback on X, which we were able to quickly implement to increase the amount of tradable liquidity as well as the risk limit controls.

### Base Ecosystem Partnerships

We have spoken with multiple protocols and communities on Base to solidify partnerships moving forward.  For example, we will be implementing swaps through a few prominent Base AMM protocols to source liquidity for our collateral swap feature.  We will also be using a novel implementation of an ERC404 protocol’s technology that recently launched on Base.  This will allow us to automatically mint and burn VIP NFTs that represent a user’s trading activity on Drake while unlocking special trading benefits.

### Smart contracts bug fixes and improvement (with Dedaub)

We completed our first audit with Dedaub and addressed all the issues noted in our contracts by the auditor. We have improved the design of our Earn Vault and funding & borrowing fee structure, enhancing the safety of our model.

## After Buildathon → Mainnet launch target @ 2024/08/01

We will continuously improve our product based on the feedback collected during the paper trading competition between June 28th and July 28th.

We plan to integrate Chainlink Data Stream into our trading logic once it goes live on Base, anticipated by the **end of July**. Chainlink Data Streams offer low-latency off-chain market data that can be verified on-chain, providing us with on-demand access to high-frequency market data through a decentralized and transparent infrastructure. Drake will be the first-tier perpetual protocol to integrate with Chainlink’s low-latency oracle on base.

Following the deployment of the Low Latency Oracle on the mainnet, we will conduct a private beta using real funds on the mainnet, with a target launch date of August 1st. Participants in the paper trading competition during the testnet phase will be whitelisted for the private beta. Additionally, we are collaborating with various protocols and communities on Base to whitelist their holders and users for the private beta. Participants in the private beta will receive boosted rewards and benefits in the future developments of Drake's platform.

We also have plans to work with prominent NFT platforms/communities on Base to develop and launch a collection for Drake users, similar to the Blueberry Club for GMX.  The Drake name pays homage to the Drake Equation, which a probabilistic argument used to estimate the number of active, communicative extraterrestrial civilizations in the Milky Way Galaxy.  Therefore, the NFT collection will be alien themed, allowing us to create lore and many fun and interactive ways for the community to engage with and expand on the lore.

We have other community building and engagement opportunities planned for the future such as AMAs, X Spaces with other Base projects/communities, more trading competitions, and X/Farcaster thread contests.

# Reference material:

Smart contract deployment history reference:

Refer to the history of [deployed.json](https://github.com/drxprotocol/drake-exchange/blob/main/doc/deployed.json), which records the addresses of smart contracts we deployed or upgraded during the Buildathon. The deployment dates and contract content can all be verified on Base Sepolia.

Smart contract development reference:

Refer to the history of [contracts](https://github.com/drxprotocol/drake-exchange/tree/main/contracts) to track our smart contract development progress during the Buildathon. You can also verify this by comparing it with our on-chain deployment history.
