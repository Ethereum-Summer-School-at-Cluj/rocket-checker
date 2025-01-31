# Rocket check

## Introduction

Welcome to our complex supply chain project using NFTs for product authentication on Polygon. This project leverages the power of blockchain technology to ensure the authenticity of original products, such as Jordan shoes, tees, and more. By using NFTs, we can uniquely identify each product and provide a transparent, immutable record of its origin and ownership.

## Features

- **NFT-Based Authentication**: Each product is represented by a unique NFT, ensuring its authenticity.
- **Polygon Blockchain**: Utilizes Polygon for a secure and decentralized system.
- **Smart Contracts**: Implements smart contracts to automate and secure the supply chain processes.
- **Transparency**: Provides an immutable and transparent record of each product's history.
- **Scalability**: Designed to handle complex supply chains with multiple stakeholders.

## Smart contract addresses

Rocket Token: 0x25f21b90Ed59436887aC0912fa8BDC74522852DE https://amoy.polygonscan.com/address/0x25f21b90Ed59436887aC0912fa8BDC74522852DE

Marketplace: 0x8866D7ae8d3EBD4BeC425d4C6bdd12046552eC22 https://amoy.polygonscan.com/address/0x8866D7ae8d3EBD4BeC425d4C6bdd12046552eC22

Producer: 0x26fBF69006140C993D8C2081403f00A8Bf4B42e7 https://amoy.polygonscan.com/address/0x26fBF69006140C993D8C2081403f00A8Bf4B42e7

itemManager: 0x68891bc14675156A64F2e26E806511053A80eA3b https://amoy.polygonscan.com/address/0x68891bc14675156A64F2e26E806511053A80eA3b

providerManager: 0x7cFfC6Ab80C4953DD3cCceeDED0D400D86f95a01 https://amoy.polygonscan.com/address/0x7cFfC6Ab80C4953DD3cCceeDED0D400D86f95a01

 
## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- NPM or Yarn
- Forge
- Metamask or any Polygon-compatible wallet

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/siposeduard/rocket-check.git
   cd rocket-check
   ```

2. **Install Dependencies**

   ```sh
   npm install
   ```

   or

   ```sh
   yarn install
   ```

3. **Compile Smart Contracts**

   ```sh
   forge build
   ```

4. **Deploy Smart Contracts**

   Ensure you have a Polygon wallet (like Metamask) connected to the desired network (e.g., Mumbai Testnet or Polygon Mainnet).

   ```sh
   forge script script/Counter.s.sol --rpc-url RPC --private-key PRIVATE_KEY
   ```

5. **Test Smart Contracts**

   ```sh
   forge test
   ```

## Project Structure

- `scripts/`: Contains deployment and interaction scripts.
- `test/`: Contains test cases for the smart contracts.
- `src/`: Contains the smart contracts written in Solidity.

## Rocket Crew :rocket:

**Georgiana Balea** aka Georgi the Rocket SpaceMarket Engineer [gitHub](https://github.com/GeorgianaBalea)|[Twitter](https://x.com/BaleaGeo)

**Cristea Octavian** aka Tavi the Rocket Validation Engineer [gitHub](https://github.com/octavi42)|[Twitter](https://x.com/octavicristea)

**Tudor Pintea** aka Tudor the Rocket Data Engineer [gitHub](https://github.com/tudorpintea999)|[Twitter](https://x.com/iwantanode)

**George Pop** aka George the Rocket Marketing Researcher [gitHub](https://github.com/Geo01230)
 
**Sipos Eduard** aka Edi the Rocket CI Engineer [gitHub](https://github.com/siposeduard)|[Twitter](https://x.com/SiposEduard1)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Thank you for using our complex supply chain solution. Together, we can ensure the authenticity and integrity of products in the marketplace.
