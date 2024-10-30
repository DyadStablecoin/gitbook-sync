# Vaults

Upon depositing, Note holders are issued share-tokens of collateral specific Vaults. Collateral always remains in its respective Vaults. It’s the Notes vault-shares that are backing DYAD.  A Notes quantity of share tokens, compared to the total quantity of share tokens, entitles the holder to the same percentage of the vault’s collateral pool. \
\
The Vaults can, in principle, consist of any ERC-20, but before vaults are able to get added to a Notes balance sheet and DYAD can get minted against the collateral, these vaults need to be approved via governance.

If the underlying collateral is an RWA or other asset that requires KYC for custody, the share tokens can be permissionlessly transferred to other Notes regardless of KYC status. This is possible because the right to mint DYAD against the RWA’s value is being transferred, not the right to withdraw and custody it. The 4626 vault remains the custodian.\
\
