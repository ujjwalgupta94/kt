# Mint

Q. Token is mintable ?

means token owner can create some tokens.

Q. Token is nonmintable ?

means token owner can not create more token. It is fixed.

In case of matic

## Mintable

Predicate as well as child chain can create token

## NonMintable

Only predicate & child manager will be able to create token. So when user submits, the predicate increase the value & child manager does the same after events from predicate.

# POS Withdraw

1. user burn the amount & get a tx hash. This is done on matic chain. After some checkpoint is submitted on rootchain contract. Rootchain has block data and can tell - any transaction was in which block. 

2. After checkpoint is submitted, user can withdraw money by supplying tx hash. WithdrawManager is called which will compare the txHash from user & from the submmited transaction on root chain manager. if value is same then withdraw is initiated.

# Plasma withdraw

1. user burns the tx & get a tx Hash. Checkpoint is submitted to rootchain contract.
2. After the checkpoint is submitted, user can confirm transaction withdraw & he will get another string value which is NFT id. This is done using exitNFT contract.
3. After 7 days, user can complete the withdraw which will burn the NFT & amount will be transfered to user. 

# Validator

validator are people who are runing nodes. 

# Delegator

Delegatror are people who are investing on validator.


