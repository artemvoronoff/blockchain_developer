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
