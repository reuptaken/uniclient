# uniclient2

Node.js util to watch your (or someone else) profit/loss on Uniswap market in real time. 

uniclient2.js is rewritten from scratch, using ethers.js instead of web3.js (so you have to install ethers.js)

Edit file to add your ETH address and two nodes (which can can be the same) 

    let providerCurrent = new ethers.providers.JsonRpcProvider(); //provider for "old" blocks
    let providerArchive = new ethers.providers.JsonRpcProvider(''); //provider for current blocks, has to keep at least biteSize blocks

    const myAddress = ''; // put your address here

Usage:

```./node uniswap2.js TOKEN```

IANAD (I'm not a developer), so use with care.
