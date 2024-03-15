# **Technical Interview **

<img alt="Solidity" src="https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black"> <img alt="Typescipt" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white">

This repo contains a simple Smart Contract for depositing and withdrawing tokens.

## **Prerequisites**

-   git
-   npm
-   hardhat

## **Getting started**
1.  Clone the repository

```sh
git clone --branch <branch_name> https://github.com/tech-interview/tech-interview.git
```

2.  Navigate to `tech-interview` directory

```sh
cd tech-interview
```

3.  Install dependencies

```sh
npm install
```

4.  Configure project (Will add later when deploying to testnet)

```sh
cp .env.example .env
```

## **Compile Smart Contracts**

To compile every smart contract run the following command in your terminal:

```sh
npx hardhat compile
```



## **Run tests**

To run the tests in the test folder run the following command in your terminal:

Note: Running tests automatically compiles any smart contracts

-   To run all tests
```sh
npx hardhat test
```


## **Deploy to Blockchain Network** (Sepolia)

-   To a specific testnet

```sh
yarn hardhat --network <network-name-in-tsconfig> deploy -- tags <deploy-script-tags>
```

-   To local development network (to test deployment)

```sh
yarn hardhat deploy -- tags <deploy-script-tags>
```
