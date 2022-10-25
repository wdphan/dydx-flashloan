
# Vault

> A mini-vault implementation

Simple example of vault contract, commonly used in DeFi protocols.

Most vaults on the mainnet are more complex. This focuses on the math for calculating shares to mint on deposit and the amount of token to withdraw. Some amount of shares are minted when an user deposits. The DeFi protocol would use the users' deposits to generate yield (somehow). The user burn shares to withdraw his tokens + yield.


[Contract Source](src/mini-vault.sol)
