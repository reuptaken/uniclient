# uniclient

Node.js util to watch your profit/loss on Uniswap market in real time. It loads all past transactions first and then watches the market for new events, refreshing every 10 seconds.

Edit file to add your ETH address and node 

    const myAddress = ''; // put your address here
    const contract = new web3.eth.Contract(Uniswap.abi, exchangeAddress);

Usage:

```./node uniswap.js TOKEN```

IANAD (I'm not a developer), so use with care.
