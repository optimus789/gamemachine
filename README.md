# Game Machine
It provides a competitive and fun experience while using blockchain and NFTs to create a meaningful use case. Both the games provide a gaming experience with good sound effects and also you can earn some extra perks by burning your NFTs. A simple user interface makes it more entertaining. This project focuses on the utilities of the NFTs in a simple game. 
### Clone the repo and do the following steps

```
% npm i
% npm run start:dev
```

### How it's made
It is made using the Meter testnet Blockchain, IPFS, Tableland and EthersJs. Perks like speed boosters for Crypto Chicken Run and score multiplier for Symbals are being implemented through burning. We have used expressJS as backend and simple HTML/CSS and Js in the frontend. Stored the blockchain data like scores and levels on Tableland.

Our motive behind this was to develop a conversion engine that will be provided as a service to web2 games and its developer and they would be able to easily implement web3 features in their games. 

URL: https://gamemachine-meter.herokuapp.com

Crypto Chicken Run smart contract link: https://scan-warringstakes.meter.io/address/0xC1271a285b123778D9C5E14c64bcaE4ed12A4934

Symbals Game Smart contract link: https://scan-warringstakes.meter.io/address/0xcf9ed05F066D7Be08308720cCbEf8886d6456605

Both smart contracts are deployed on Meter Testnet Network


- Game with boost enabled after burning the nft
![Game with boost enabled after burning the nft](/game1.png)

- Profile nft page with burning function transacted on Meter Testnet
![Profile nft page with burning function transacted on Meter Testnet](/game2.png)