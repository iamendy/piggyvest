# PiggyVest [ETHLGHO]

Live Demo - [Watch Video](https://) <br />
Demo Link - [PiggyVest dApp](https://piggyvestdapp.vercel.app) <br />
Slides - [Presentation Slides](https://piggyvestdapp.vercel.app/PiggyVestSlides.pdf)

## ✨ Description

PiggyVest is an open-source widget that allows Africans to save better and earn yield.

We aim to help Africans hedge against hyperinflation by integrating Aave to provide an intuitive interface for saving and easily getting yield on USDT.

![PiggyVest Dashboard](https://piggyvestapp.vercel.app/img/preview.png)

## 💻 How we built PiggyVest

We created and deployed PiggyVest smart contract on ETH Goerli Testnet:

1. PiggyVest 0x23aF55205bdf25C3Cd6153055a926297e848582D - [View on Celo scan](https://celoscan.io/address/0x23aF55205bdf25C3Cd6153055a926297e848582D)

Here are some of the recent transactions on PiggyVest:

1. Savings [View txn on Eth Scan](https://celoscan.io/tx/)

2. Withdraw [View txn on Eth Scan](https://celoscan.io/tx/)

This is an original work by our team. We built our solution using: **`NextJs/Typescript`**, **`Wagmi`**, **`Rainbowkit`**, **`TailwindCSS`** and **`Remix`**

## 🧑‍💻 Instructions for testing locally

\***\* Smart contract \*\***

Note: Recommend using [Remix](https://remix.ethereum.org) for quick smart contract deployment, or alternatively hardhat:

1. Deploy `PiggyVest` on ETH Goerli by running the necessary Hardhat script

\***\* Frontend \*\***

2. Update your deployed `PiggyVest` address on the `packages/react-app/constants/connect.ts file.

3. run `cp .env.example .env`

4. Update the fields on the .env file with your keys

5. Run `yarn dev` to start the DApp on your development environment.

6. You can connect from your favourite wallet and enjoy a world of limitless possibilities.
