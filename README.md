# Solidity Auction House Simulator

Here​​ are​ t​he ​​instructions ​​to ​​install ​​the​ ​required​​ dependencies ​​and ​​run ​​the auction simulator:

1. Install​​​Node.js

2. Install​​ the​ ​following ​​dependencies ​​for​ ​this​​ project:  
    * Truffle
    * Mocha
    * web3
    * Ethereum​​RPC
    * EthereumJS​​ ABI
    * EthereumJS ​​Utils
    * BigNumber

    To​​ do​​ it​​ all ​​in ​​one ​​line:

    sudo ​​npm​ ​-g ​​install ​​truffle ​​mocha ​​web3​​ ethereumjs-testrpc ethereumjs-abi​​ ethereumjs-util​​ bignumber
3. Get​​ the ​​local​​ test ​​network ​​up​​ and ​​running. <br />
   ​​Make ​​sure ​​to ​​kill ​​any ​​prior ​​testrpc ​​process ​​and modify ​​the ​​gas limit, the ​​test​ ​cases ​​use​ ​a​​ lot ​​of ​​gas!: <br /> testrpc​​ --gasLimit ​​1000000000 ​​&

4. To ​​compile ​​your ​​code ​​and ​​run​ ​the ​​provided​​ test​​files.  
   ​​To​​ run ​​an​​ individual ​​test: truffle​​ test ​​test/ArbitrationTest.sol  
   To​ ​run ​​all​​ tests​ ​that​​ Truffle​​ can​​ find: truffle ​​test  
