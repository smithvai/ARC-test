# Arc Test Token (ATT)

This is a standard ERC-20 token smart contract built using Solidity and OpenZeppelin, specifically configured to be deployed on the **Arc Testnet** (Circle's EVM-compatible Layer-1 network).

## Features
- **Standard ERC-20:** Fully compliant with Ethereum-based wallets and decentralized applications (dApps).
- **Ownable:** Secure administrative control allowing only the deployer (owner) to mint new tokens.
- **EVM Compatible:** Smooth deployment on the Arc Testnet.

---

## Contract Details
- **Token Name:** Arc Test Token
- **Symbol:** ATT
- **Decimals:** 18
- **Solidity Version:** `^0.8.20`

---

## Deployment Configuration (Arc Testnet)

To deploy this contract on the Arc Testnet, use the following network specifications in your wallet (MetaMask) or deployment tool (Hardhat/Foundry):

- **Network Name:** Arc Testnet
- **RPC URL:** `https://rpc.testnet.arc.network`
- **Chain ID:** `5042002`
- **Currency Symbol:** `USDC` (Arc uses native USDC for gas fees!)
- **Block Explorer:** `https://testnet.arcscan.app`

---

## How to Deploy via Remix IDE

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file named `ArcToken.sol` and paste the contract code.
3. Go to the **Solidity Compiler** tab, select version `0.8.20` (or higher), and click **Compile**.
4. Switch to your MetaMask wallet and make sure you are connected to the **Arc Testnet** (ensure you have some testnet USDC for gas).
5. Go to the **Deploy & Run Transactions** tab in Remix.
6. Change the Environment to **Injected Provider - MetaMask**.
7. Enter the `initialSupply` (e.g., `1000`) in the deployment input field and click **Deploy**.
8. Confirm the transaction in your MetaMask wallet.

---

## License
This project is licensed under the MIT License.
