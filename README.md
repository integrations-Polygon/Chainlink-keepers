# **Chainlink-keepers**

**Chainlink-keepers** repository is a comprehensive codebase that leverages chainlink keepers implementation on polygon. Chainlink keepers automate smart contracts using a secure and hyper-reliable decentralized network that uses the same external network of node operators that secures billions in value.

## **Getting started**

- Clone this repository

```bash
git clone https://github.com/integrations-Polygon/Chainlink-keepers.git

```

- Navigate to `Chainlink-keepers`

```bash
cd Chainlink-keepers

```

- Install dependencies

```bash
npm install

```
or

```bash
yarn

```

### **Deploy your smart contract**

To deploy your smart contract, first you would need to freshly **compile** your smart contract by simply running this command.

```bash
npx hardhat clean

```
and

```bash
npx hardhat compile

```
After that, to actually **deploy** the smart contract run this command

```bash
npx hardhat run --network mumbai ./scripts/keepersdeploy.js

```

### **Verify your deployed smart contract (OPTIONAL)**

It is always a good practice to **verify** your smart contract for future debugging sessions by simple running this command. Add polygnscan api key in hardhat.config file

```bash
npx hardhat verify --network mumbai <deploy-contract-address> <if-any-arguments-seperated-by-space>

```

### **Test Smart contract automation**

- Check chainlink keepers or autmation UI to automate your contract
- Automaion APP: https://automation.chain.link/

### **Contributing**:

If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. We welcome community contributions.
