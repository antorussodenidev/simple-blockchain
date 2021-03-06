## Simple BlockChain

Project for understanding bitcoin (blockchain) algorithm.

### Installation

```bash
git clone https://github.com/proin/simple-blockchain
cd simple-blockchain
npm install
```

### Run Code

```bash
API_PORT=3000 P2P_PORT=4000 node blockchain.js 
API_PORT=3001 P2P_PORT=4001 PEERS=ws://localhost:4000 node blockchain.js 
```

### API

> http://host:port/blocks

- Show list of blockchain

> http://host:port/mining

- create new block with Proof of Work

> http://host:port/peers/add?peer=ws://localhost:4000

- add peers


### Reference

- https://blog.iwanhae.ga/introduction_of_bitcoin
- https://www.slideshare.net/skimaza/ss-57356762
- https://organicmedialab.com/2014/01/11/virtuous-cycle-of-bitcoin-mining
- https://www.ddengle.com/board_free_voted/160514
