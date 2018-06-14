A solidity application built from https://medium.com/@merunasgrincalaitis/the-ultimate-end-to-end-tutorial-to-create-and-deploy-a-fully-descentralized-dapp-in-ethereum-18f0cf6d7e0e

- To generate build.js before uploading to IPFS, type the following command:
    '''webpack '''
- Having issues producing the build.js file through webpack (It's a webpack issue). I downloaded the build.js file from the repo https://github.com/merlox/casino-ethereum and moved on with the tutorial
- Having issues downloading web3, web3-eth
- Contract Address 0xcac001343018c5f727c3ae35494e79e30b551f71
- Website Published to QmVfZQtGQE9de769XiM4VzrHwhNedVw6dmTwTNdjvXfmdc: /ipfs/QmVsv97KsTvDR9hGGaYq2gV9JP3ZSbWkbKCbQe8QurfYXR. Visit gateway.ipfs.io/ipns/QmVfZQtGQE9de769XiM4VzrHwhNedVw6dmTwTNdjvXfmdc to view 



https://ethereum.stackexchange.com/questions/26900/how-to-get-the-json-interface-abi-in-new-remix-ide-version


ABI Code
'''
[{"constant":false,"inputs":[],"name":"generateNumberWinner","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"numberOfBets","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"player","type":"address"}],"name":"checkPlayerExists","outputs":[{"name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"kill","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[],"name":"resetData","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"name":"","type":"address"}],"name":"playerInfo","outputs":[{"name":"amountBet","type":"uint256"},{"name":"numberSelected","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"name":"numberWinner","type":"uint256"}],"name":"distributePrizes","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"name":"numberSelected","type":"uint256"}],"name":"bet","outputs":[],"payable":true,"stateMutability":"payable","type":"function"},{"constant":true,"inputs":[],"name":"owner","outputs":[{"name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"minimumBet","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"maxAmountOfBets","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"uint256"}],"name":"players","outputs":[{"name":"","type":"address"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"totalBet","outputs":[{"name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"inputs":[{"name":"_minimumBet","type":"uint256"}],"payable":false,"stateMutability":"nonpayable","type":"constructor"},{"payable":true,"stateMutability":"payable","type":"fallback"}]
'''