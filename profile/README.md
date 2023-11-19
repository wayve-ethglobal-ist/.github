## (🌱) Wayve - The ESG funds governing protocol

### Intro 👋

What is Wayve?

Wayve is a protocol that empowers consumer loyalty points with the ability to govern ESG funds.

### Project Description 📔

❗❗ Problem Statement

This project aims to tackle 2 key problems with how Environmental, Social, and Governance (ESG) initiatives are being carried out.

1. Currently, the ESG initiatives being carried out by businesses & corporations are opaque. There is no easy way for the general public to verify and audit the ESG efforts done or the impact they have made.

2. Furthermore, there is a lack of clear open standards to achieve a unified ESG goal. For example, it takes concerted effort to achieve net zero by 2050. Without a unified approach, the good a business makes is gonna be overridden by another business without proper coordination.

✨✨ Vision

Wayve aims to empower consumers with the ability to direct ESG funds towards creating positive impact on the world and society, publicly attest to the impacts of successful ESG initiatives, with open standards and metrics for impact measurement across the value chain, and streamline the gathering, evaluation, and reporting of ESG data in accordance with ESRSs in an appropriate and auditable manner.

✔️✔️ Unique Value Proposition

We duplicate the familiar loyalty points system already present in our daily lives, and putting it onchain as an ERC-20, ensuring interoperability across the Ethereum ecosystem. Account Abstraction enables general consumers to easily vote on the allocation of ESG funds, all while safeguarding private and sensitive user data.

### Key Features 🔑

1. Account Abstraction - Users need not know how to use Ethereum, and theu don't need to pay gas fees to conduct onchain transactions
2. Zero-Knowledge Identity - The protocol is able to identify users without knowing anything personal information about them
3. Token-Bound Accounts - All the loyalty points (ERC-20) is unified and controllable under a single portfolio view within an NFT

### Product Flow ⤵️


### How It's Made 🧰

To achieve the vision, we leveraged several cutting-edge technology provided by our sponsors:

1. **Safe Account Abstraction SDK & WalletConnect SDK & Base Paymaster** - Handles user smart wallet creation and onchain transactions (+ gas sponsors) without the user needing to know how to use Ethereum. On the vendor's side, it enables seamless issuance of loyalty points to consumers, submission of ESG proposals onchain, and publishing loyalty points issuance policy.
2. **Worldcoin & Mina Protocol** - A zero-knowledge proof is generated for user's private and sensitive data alongside its biometrics info (or thumbprint). The proof is then assigned a unique World ID to represent the unique user. Users can then seamlessly confirm onchain transactions with just their thumbprint, without exposing any of their personal information.
3. **IPFS & Filecoin** - The ESG proposals created are stored permanently on a decentralized file storage via lighthouse.storage to ensure permanent accessibility of the proposals.
4. **ERC-6551 Token-Bound Accounts** - Upon user smart wallet creation, a global loyalty card compliant with the ERC-6551 Token-Bound Accounts standard is created, and the loyalty points are transferred under its control. This ensures that all the loyalty points received in this protocol are unified and controllable under a single NFT portfolio view, instead of having a scattered view of all the tokens showing up under the user's smart wallet view.
5. **ENS & Nouns** - To make onchain interactions more fun and friendly, the app supports the display of ENS names and subnames, as well as adopting a Nounish approach to make it more fun to interact with.
6. **Ethereum Attestation Service** - Once the proposals have been successfully executed, results will be periodically submitted onchain for verification by the general public. The general public can then collectively attest whether the ESG initiatives being executed have positively impacted their quality of life.

### The Stack ⚙️


### Deployments

Live Demo


Smart Contracts
Arbitrum:
Base:
Cartesi:
Celo:
Gnosis Chain:
Linea:
Neon EVM:
Polygon zkEVM:
Scroll:

### Getting Started

_We recommend installing Wayve by building from the source code as follows:_

```bash
# Download the source code
git clone https://github.com/wayve-ethglobal-ist/wayve-app
cd wayve-app

# Install dependencies
npm install

# Run app
npm run dev
```
