# Learning-by-example (#1) Web3js return struct
Learning by example(#1): Web3js return struct

We created a smart contract in the folowing link:
https://github.com/javaditco/learning-by-example-1-smartcontract-return-struct- 


After the deployment of the above smart contract you need a code to connect it.
Requerments:
1. An account on private network, Ropsten, Rinkeby or main network (the network you deployed the contract) with a few ether
2. Web3 library to link in this code

Set following variable in the code before running:
1. myAccountPass: your Ethereum account password on which network you deployed the contract
2. myAccount: account address
3. SmartContracat: smart contract address, you get after the deployment
4. replase (ws://127.0.0.1:8546) with the node address you connet and its port. If you prefer to use the http connetion replace its code line with (var web3 = new Web3(new Web3.providers.HttpProvider("http://127.0.0.1:8546"));) and set the IP and port according your Ethereum Node configuration.
