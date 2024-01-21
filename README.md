# PiggyVest [ETHLGHO]

Live Demo - [Watch Video](https://drive.google.com/file/d/1nsJecAsWC1_jTUkeqEWH6t98Xni9B4sd/view) <br />
Demo Link - [PiggyVest dApp](https://piggyvestdapp.vercel.app) <br />
Slides - [Presentation Slides](https://piggyvestdapp.vercel.app/PiggyVestSlides.pdf)

## ✨ Description

PiggyVest is an open-source widget that allows Africans to save better and earn yield.

We aim to help Africans hedge against hyperinflation by integrating Aave to provide an intuitive interface for saving and easily getting yield on USDT.

Users on-ramp fiat, then save and earn in USDT thereby helping them hedge against inflation.

![PiggyVest Dashboard](https://piggyvestdapp.vercel.app/img/preview.png)

## 💻 How we built PiggyVest

We created and deployed PiggyVest smart contract on ETH Goerli Testnet:

1. PiggyVest 0x23aF55205bdf25C3Cd6153055a926297e848582D - [View on Eth scan](https://goerli.etherscan.io/address/0x23aF55205bdf25C3Cd6153055a926297e848582D)

Here are some of the recent transactions on PiggyVest:

1. Savings [View txn on Eth Scan](https://goerli.etherscan.io/tx/0x1856c51aa13fba9ed301c57b83086b8ed9e4bf61ad5e8d36b5e7ae681138e948)

2. Withdraw [View txn on Eth Scan](https://goerli.etherscan.io/tx/0xc8679506fb0e84575b0ed6117a89d27f7dd391fd97c8a9a2ca429712ab1cf742)

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
