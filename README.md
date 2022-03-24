# eth_requestAccounts with MetaMask example

This is a quick fork of [demo-code-snippets](https://github.com/rsksmart/demo-code-snippets) to demo the usage of the `eth_requestAccounts` method implementation.

Original [EIP-1102](https://eips.ethereum.org/EIPS/eip-1102).

web3.js entry on [eth_requestAccounts](https://web3js.readthedocs.io/en/v1.2.7/web3-eth.html#requestaccounts):

> It doesn’t work if you’re connected to a node with a default Web3.js provider. (WebsocketProvider, HttpProvidder and IpcProvider) This method will only work if you’re using the injected provider from a application like Status, Mist or Metamask.

## Install

`npm i`

## Run

`npm run start`

## Use

Open `localhost:3000`. Hit **Connect MetaMask**.