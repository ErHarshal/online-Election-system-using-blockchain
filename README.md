# online-Election-system-using-blockchain
this is an online election system demo project using blockchain


step 1 :  start any blockchain network or ganache or local geth node, on 127.0.0.1:8545 which is default port for ganache
          and local geth node.

step 2:  after that if you are not using same port then change it in truffle-config.js

step 3:  after that you open terminal type command
          truffle compile ---> which will create the build folder in which contract json file gets created.
          truffle migrate ---> which will deploy the contract on blockchain and add 
          contract address in Election.json file.
        
step 4:  copy the contarct address from Election.json file and paste it into the voting.html file.

step 5: now open the voting.html file you will see the two candidate and voters account now you can vote candidate 1 
        candidate 2.
