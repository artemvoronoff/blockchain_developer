# blockchain_developer


listunspent

[
 {
 "txid" : "e787a27bda32c8b54ee501be46d2cfcd47c1566c8ef6ee339bdb7cd5c82b701c",
 "vout" : 0,
 "address" : "2Mzxx8wGAmQQyCCrb2vXP4yxaYY9s9nepfy",
 "account" : "public faucet test",
"redeemScript": "0014c794ee65db89222f408dfe1728d214f2496d7a72"
 "scriptPubKey" : "a91454ad1e8953876c90d3fc15798c687835ab3d3aee87",
 "amount" : 0.05000000,
 "confirmations" : 12
 "spendable": true,
 "solvable": true,
 "safe": true
 }
...
]




gettxout "txid" n

Args{
"tdid" (string, required) the transaction id
"n" (numeric, required) vout number

To get the 0th index of the tdix e787..

gettxout e787a27bda32c8b54ee501be46d2cfcd47c1566c8ef6ee339bdb7cd5c82b701c 0















##OUTPUT OF SIMPLECHAIN.JS
 blockchain.chain
[
  Block {
    hash: '65c66909752f02cedf6a72a61b0ad0237c0a9d69799cb6b2778cae084effe44e',
    height: 0,
    body: 'First block in the chain - Genesis Block',
    time: 0,
    previousBlockHash: ''
  },
  Block {
    hash: '294875132b9a2c306f76d3a1c48903f6cd75d9b66f8c1532fd280737296bfadb',
    height: 0,
    body: 'test',
    time: 0,
    previousBlockHash: '65c66909752f02cedf6a72a61b0ad0237c0a9d69799cb6b2778cae084effe44e'
  },
  Block {
    hash: 'dc06a3b1da8f8c8cb828d850070ba18be325164b4fed4b1f0a0eccd6cc0b9b86',
    height: 0,
    body: 'test 2',
    time: 0,
    previousBlockHash: '294875132b9a2c306f76d3a1c48903f6cd75d9b66f8c1532fd280737296bfadb'
  }
]
