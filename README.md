# NextEdge Bank

### Built with Next Js, Hardhat, Solidity, and Tailwind CSS.

### Stack

- Frontend : [Next Js](https://nextjs.org/)
- Smart Contract Lang : [Solidity](https://docs.soliditylang.org/en/v0.8.17/)
- Dev Environment for ETH Software: [Hardhat](https://hardhat.org/)
- Network : [Polygon](https://polygon.technology/)
- Style : [Tailwind CSS](https://tailwindcss.com/)

### Installation

#### Fork The Repo

Click on the Right Side of the Top Bar to After the Watch button. <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/GitHub_Fork_Button.png" width="120px" />

Now It will be available in GitHub Account.

#### OR

#### Clone

- Clone this repo with url

```shell
git clone https://github.com/adimiuprix/nextedge-bank
```

##### Setup

> Install npm dependencies using npm install

```shell
$ npm install && cd nextedge-bank && npm install
```

> Set up environment Variables I already Provided .env.example file.

> Create a .env file in the root directory.

> Set up required environment variables.

```
URL="POLYGON_TESTNET_URI"
PRIVATE_KEY="METAMASK_PRIVATE_KEY"
NEXT_PUBLIC_CONTRACT_ADDRESS="CONTRACT_ADDRESS"
```

> In the Root Directory First Compile Your Smart Contract with This Following Command.

```shell
npx hardhat compile
```

> After Deploy Smart Contract to the Polygon Mumbai Testnet with this command.

```shell
npx hardhat run scripts/deploy.js --network mumbai
```

> Copy Smart Contract Address and replace it in with your "CONTRACT_ADDRESS"

```
NEXT_PUBLIC_CONTRACT_ADDRESS="CONTRACT_ADDRESS"
```

Let's Run this command for dev

```shell
npm run dev
--or--
yarn dev
```
