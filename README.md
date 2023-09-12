# Swisstronik Challenge #1 [learnweb3]
Swisstronik is hosting weekly challenges throughout September. This straightforward Hardhat project is designed to guide you in creating a basic smart contract for message setting and retrieval. Dive into deploying your contract and interact with it using scripts & SwisstronikJS.

## Installation
```
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox
npx hardhat compile
npx hardhat run scripts/deploy.js --network swisstronik
npx hardhat run scripts/setMessage.js --network swisstronik
npx hardhat run scripts/getMessage.js --network swisstronik
```

## Smart Contract Deployed
```
0xBe386760c7dA48c16E358317C754F586A21ed5ae
```