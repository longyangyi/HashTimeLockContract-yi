louis@louis-ubuntu-dell:~/HashTimeLockContract-yi$ truffle migrate

Compiling your contracts...
===========================
> Compiling ./contracts/HashTimeLockContract.sol
> Artifacts written to /home/louis/HashTimeLockContract-yi/build/contracts
> Compiled successfully using:
   - solc: 0.5.16+commit.9c3226ce.Emscripten.clang



Starting migrations...
======================
> Network name:    'development'
> Network id:      1621335557793
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x042cb657fc218e799133769ad1be70e2e0b7d6ab8297d3acd654667c7f1ecf97
   > Blocks: 0            Seconds: 0
   > contract address:    0x76E28398a0C0154a1E34ff0a05573603D4832b6e
   > block number:        1
   > block timestamp:     1621335566
   > account:             0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1
   > balance:             99.99549526
   > gas used:            225237 (0x36fd5)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00450474 ETH


   Deploying 'HashTimeLockContract'
   --------------------------------
   > transaction hash:    0x1d1dceabb99006c39c2fac2c0add470ce2ed71460ad529e1ee0f63165b4b3a14
   > Blocks: 0            Seconds: 0
   > contract address:    0x9D9baf837F31C0C34060539Dab5A8bE9e60CaB28
   > block number:        2
   > block timestamp:     1621335567
   > account:             0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1
   > balance:             99.97478414
   > gas used:            1035556 (0xfcd24)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.02071112 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.02521586 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.02521586 ETH










louis@louis-ubuntu-dell:~$ ganache-cli 
Ganache CLI v6.12.2 (ganache-core: 2.13.2)

Available Accounts
==================
(0) 0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1 (100 ETH)
(1) 0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85 (100 ETH)
(2) 0xEd05331Aa0563Dd20e492815f95d5F4bf2Ea89fF (100 ETH)
(3) 0x725b838cf788396b42cc0183395158Cf849D8d12 (100 ETH)
(4) 0x81692518873C7629e2Fe9CbD1e1F6E028933894e (100 ETH)
(5) 0x2feBCdae2b2eaF83E8731DABE7928eef7Bf0E958 (100 ETH)
(6) 0xb45BA935d1bEd61d895673CB79D6b50A2cB7EbE7 (100 ETH)
(7) 0x227c65e73CF1118C0a2E4Cf2EB6eEc34316e325B (100 ETH)
(8) 0x576E2D9Fa25a262AF4254f36698E2a38cfccC3A0 (100 ETH)
(9) 0xb1015Aeeb04F6d9ef3492cDA46283A30aFcb1620 (100 ETH)

Private Keys
==================
(0) 0xab37569222bfd1c8f34650bb37480bbbf124410b1a3d8470582a638d39d6c86e
(1) 0xf4a1ddd0b0e63e86a6c28321ac0cde19409b3955ea1ce0f09db514f43f72ecc9
(2) 0x8189391184dab08404dd324994e5a20ad8ff933d15c0efd5b661ccef6e959204
(3) 0x75d57f9e3bd68c328b94cf7eb066d104b6b68ff9f908177af030a9a3d90fc06d
(4) 0xaa2b39f6c7e986a45fee942f6ead8c2cc05df25de068c7ce6ca18b5ef3d01e47
(5) 0xc6d6dff178f1e4fa3e25b14bf5ee64fa0ddf6d7d91840a0c220cf0d4eb143965
(6) 0xfe549393f9db39ee230a702955886a8a93420cc78800d607fa9aabc374728383
(7) 0xce4d6bdfc742022e4b810b9b49b54f29a7eb819f076f0c46d20722fc0c247100
(8) 0xc0ab0001c1bbae26a1343ab4f47bfdd5a236c7a535ef402e01ffdf6ece2da009
(9) 0x42d887c190519eb0b0d7d122082c4ea8f7dac8346ca9bae32638a68a89d82079

HD Wallet
==================
Mnemonic:      antenna renew certain draw pigeon burger daring one waste defense expect call
Base HD Path:  m/44'/60'/0'/0/{account_index}

Gas Price
==================
20000000000

Gas Limit
==================
6721975

Call Gas Limit
==================
9007199254740991

Listening on 127.0.0.1:8545
eth_blockNumber
net_version
eth_accounts
eth_getBlockByNumber
eth_accounts
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x042cb657fc218e799133769ad1be70e2e0b7d6ab8297d3acd654667c7f1ecf97
  Contract created: 0x76e28398a0c0154a1e34ff0a05573603d4832b6e
  Gas usage: 225237
  Block Number: 1
  Block Time: Tue May 18 2021 18:59:26 GMT+0800 (China Standard Time)

eth_getTransactionReceipt
eth_getCode
eth_getTransactionByHash
eth_getBlockByNumber
eth_getBalance
net_version
eth_getBlockByNumber
eth_getBlockByNumber
net_version
eth_getBlockByNumber
eth_estimateGas
net_version
eth_blockNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0x1d1dceabb99006c39c2fac2c0add470ce2ed71460ad529e1ee0f63165b4b3a14
  Contract created: 0x9d9baf837f31c0c34060539dab5a8be9e60cab28
  Gas usage: 1035556
  Block Number: 2
  Block Time: Tue May 18 2021 18:59:27 GMT+0800 (China Standard Time)

eth_getTransactionReceipt
eth_getCode
eth_getTransactionByHash
eth_getBlockByNumber
eth_getBalance
eth_getBlockByNumber
eth_getBlockByNumber
eth_sendTransaction

  Transaction: 0xcf0c5d2d74bd863a4c649b421e4a708c91eae1c7c42c2b320e872ea97084e5b7
  Gas usage: 42363
  Block Number: 3
  Block Time: Tue May 18 2021 18:59:27 GMT+0800 (China Standard Time)

eth_getTransactionReceipt





louis@louis-ubuntu-dell:~/HashTimeLockContract-yi$ truffle console
truffle(development)> var contract
undefined

truffle(development)> HashTimeLockContract.deployed().then(function(instance){contract= instance;})
undefined

truffle(development)> let result = await contract.newContract.sendTransaction("0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85", "0x66687aadf862bd776c8fc18b8e9f8e20089714856ee233b3902a591d0d5f2925", "0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff", {from: "0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1", value: web3.utils.toWei('10', 'ether')})
undefined

truffle(development)> result.receipt.logs
[
  {
    logIndex: 0,
    transactionIndex: 0,
    transactionHash: '0x7b0fa92a508ae139a00fad34650f476a8020f30a682e112deee44664a01a287d',
    blockHash: '0xdb420eb823c1260dc387c2bc605d4596d3ac207dbe7ffed996408ef455253b82',
    blockNumber: 4,
    address: '0x9D9baf837F31C0C34060539Dab5A8bE9e60CaB28',
    type: 'mined',
    removed: false,
    id: 'log_c0c74164',
    event: 'LogHTLCNew',
    args: Result {
      '0': '0xb63552c6ff936222e485d73f300d0e08ef487690eba066a2b607c05a1fd0b164',
      '1': '0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1',
      '2': '0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85',
      '3': [BN],
      '4': '0x66687aadf862bd776c8fc18b8e9f8e20089714856ee233b3902a591d0d5f2925',
      '5': [BN],
      __length__: 6,
      contractId: '0xb63552c6ff936222e485d73f300d0e08ef487690eba066a2b607c05a1fd0b164',
      sender: '0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1',
      receiver: '0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85',
      amount: [BN],
      hashlock: '0x66687aadf862bd776c8fc18b8e9f8e20089714856ee233b3902a591d0d5f2925',
      timelock: [BN]
    }
  }
]





  Transaction: 0x7b0fa92a508ae139a00fad34650f476a8020f30a682e112deee44664a01a287d
  Gas usage: 134656
  Block Number: 4
  Block Time: Tue May 18 2021 19:04:44 GMT+0800 (China Standard Time)


truffle(development)> web3.eth.getBalance("0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1")
'89971243760000000000'
truffle(development)> web3.eth.getBalance("0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85")
'100000000000000000000'
truffle(development)> web3.eth.getBalance("0x9d9baf837f31c0c34060539dab5a8be9e60cab28")
'10000000000000000000'









truffle(development)> contract.withdraw("0xb63552c6ff936222e485d73f300d0e08ef487690eba066a2b607c05a1fd0b164", "0x0000000000000000000000000000000000000000000000000000000000000000", {from: "0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85"})
{
  tx: '0x21d3361666cc50221416790abd35d236121f8e444c5dbdfc854a6404a4329c15',
  receipt: {
    transactionHash: '0x21d3361666cc50221416790abd35d236121f8e444c5dbdfc854a6404a4329c15',
    transactionIndex: 0,
    blockHash: '0x9d3c674ba28a4ed5879408a0ca79c40378d43feb79d2c0bfcf9b7eeed0820f0c',
    blockNumber: 5,
    from: '0x7a01354de9f3cbfe121cbd2183b6f8bbc9cf1a85',
    to: '0x9d9baf837f31c0c34060539dab5a8be9e60cab28',
    gasUsed: 60168,
    cumulativeGasUsed: 60168,
    contractAddress: null,
    logs: [ [Object] ],
    status: true,
    logsBloom: '0x00000000000000000000800000000000000000000400000000000000000000010000000000000000000000000000000000000000000000000000080000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000004200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000002000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000040000000000000000000',
    rawLogs: [ [Object] ]
  },
  logs: [
    {
      logIndex: 0,
      transactionIndex: 0,
      transactionHash: '0x21d3361666cc50221416790abd35d236121f8e444c5dbdfc854a6404a4329c15',
      blockHash: '0x9d3c674ba28a4ed5879408a0ca79c40378d43feb79d2c0bfcf9b7eeed0820f0c',
      blockNumber: 5,
      address: '0x9D9baf837F31C0C34060539Dab5A8bE9e60CaB28',
      type: 'mined',
      removed: false,
      id: 'log_0638e82b',
      event: 'LogHTLCWithdraw',
      args: [Result]
    }
  ]
}



  Transaction: 0x21d3361666cc50221416790abd35d236121f8e444c5dbdfc854a6404a4329c15
  Gas usage: 60168
  Block Number: 5
  Block Time: Tue May 18 2021 19:10:02 GMT+0800 (China Standard Time)



truffle(development)> web3.eth.getBalance("0x4ab7fCA3bbb0dd145D9715adD1396e8718E9b0C1")
'89971243760000000000'
truffle(development)> web3.eth.getBalance("0x7A01354De9F3CbfE121CBD2183B6f8Bbc9Cf1a85")
'109998796640000000000'
truffle(development)> web3.eth.getBalance("0x9d9baf837f31c0c34060539dab5a8be9e60cab28")
'0'


