# toss-of-coin-contract
This is a simple contract to play a toss of coin game

Brief Description about contract:

mapping: a key-value data holder. You only can give key and get value out of it. 
You can’t get length or last value on this data type. This is why we keep track of id’s of bets with betCounter variable.


events: it basically fires an event when get called.


payable: it is a keyword for functions that contains a transaction in it. That value of transaction assigned to msg.value.


msg.sender: this is the address of the caller account.

Steps to setup 

Step 1 : Run the below command

testrpc --account="0x68faeb324e1b8f67e2e9354ec5b700f8864bb63baacafc8d3f17f3d8b3ae4b6e, 100000000000000000000" --account="0xe12ce5de88bff513d996b6179df6acca20313565704d555ca0b8454fc07e80c5, 100000000000000000000" --account="0xc1d0d2eda09c22b123547a5094f413625a703e410290bf89bbbb60ff910208b8, 100000000000000000000"

Step 2: open new command prompt

Inside TOSS folder run
npm install
Run the attached command screenshot step by step

Step 3: open powershell run the below command

cmd 1: truffle migrate

Open new cmd prompt and run following cmd.

geth attach http://localhost:8545 
<eth.accounts
<eth.coinbase
<web3.fromWei(eth.getBalance(eth.accounts[1]), "ether")
<net.version
<eth.sendTransaction({from:eth.coinbase, to: eth.accounts[1], value:web3.toWei(10, "ether")})
<web3.fromWei(eth.getBalance(eth.accounts[1]), "ether")

control + C & 
 
cmd 2: npm run dev
