# AuctionNFT Smart Contract

Contract is deployed on Goerli Network at address : 0x5cc4B132b9e18e446b45c9f9CFd02423aDafFE69

## Steps 

1. Clone the project into your local.

2. Open terminal, navigate to root folder and run
```
npm install
```

3. Create a .env file in the root folder and add variables 
```
GOERLI_PRIVATE_KEY={YOUR_PRIVATE_KEY}
GOERLI_RPC_URL={YOUR_GOERLI_RPC_URL}
ETHERSCAN_API_KEY={YOUR_ETHERSCAN_API_KEY}
```

4. Pass the Auction Time , Minimum bid, NFT Name, NFT Symbol, Base URL for Metadata, Max supply of tokens in the constructor in 
       deploy/deploy-auctionNFT.ts 
       
5. To compile , run
```
npx hardhat compile
```

6. To deploy on local network run
```
npx hardhat deploy --tags auction 
```

7. To deploy on Goerli network run
```
npx hardhat deploy --tags auction --network goerli
```



