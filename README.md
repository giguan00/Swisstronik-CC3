# Swisstronik code challenge #3

## Task details: Craft an ERC20 contract that mints at least 100 tokens with Hardhat

Try running some of the following tasks:

Deploy Contract
```
0x444F0F5AD075216833F8BfEfAbf7f4c9462f053B
```
Tx Hash Mint
```
https://explorer-evm.testnet.swisstronik.com/tx/0x46f594a811293627da55a57c0b7bc4d505a2e87a81beeb480aa53dd7069eb674
```
Tx Hash Transfer
```
https://explorer-evm.testnet.swisstronik.com/tx/0xefda3234faa4ab0d9d5359630c086b991807a5b43fa008bf0cba8e5631c7a222
```
Tx Hash Burn
```
https://explorer-evm.testnet.swisstronik.com/tx/0x0bab26adfe124cfa96e2bd72edfeca320061ae5be66de86cfafd50dcbef4d30b
```

Function Deploy
```
npx hardhat run scripts/deploy.js --network swisstronik
```
Function Mint
```
npx hardhat run scripts/mint.js --network swisstronik
```
Function Burn
```
npx hardhat run scripts/burn.js --network swisstronik
```
Function Total Supply
```
npx hardhat run scripts/totalSupply.js --network swisstronik
```
Function Transfer
```
npx hardhat run scripts/transfer.js --network swisstronik
```
Function Balance
```
npx hardhat run scripts/balanceOf.js --network swisstronik
```

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
