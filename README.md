# My React dApp

This monorepo was designed to provide a developer-friendly experience to Alephium ecosystem newcomers. It is split into 2 parts:

- app: contains the React frontend part of the dApp
- contracts: contains the dApp contracts

It uses **yarn workspaces** to manage both app and contract projects from the monorepo root.

To get started quickly, follow these steps:

## Set up a devnet

Start a local devnet for testing and development. Please refer to the [Getting Started documentation](https://docs.alephium.org/full-node/getting-started#devnet).

## Install an Alephium wallet

Download an [Alephium wallet](https://alephium.org/#wallets), connect to it to your devnet and import this mnemonic to have 4,000,000 token allocated for your addresses:

```
vault alarm sad mass witness property virus style good flower rice alpha viable evidence run glare pretty scout evil judge enroll refuse another lava
```

## Install dependencies

```
yarn install
```

## Compile the contracts

```
yarn compile
```

## Deploy the contracts

```
yarn deploy
```

## Build the contracts package

```
yarn build:contracts
```

## Run the app

```
yarn start
```

## More

You could use yarn workspace to run commands in the contracts or app directory.

```
yarn <my-contracts|my-dapp> <command>
```
