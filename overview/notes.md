# Notes

To be part of the DYAD ecosystem, you need to own a DYAD specific NFT, called a Note.

A Note is not only required if you want to deposit collateral and mint DYAD, but also if you want to farm the protocol's native token or participate in any other exercise that allows you to earn yield.\
\
Notes are minted on a bonding line, where the first note in existence was minted for 0.1 ETH. This fee increases with 0.001 ETH on every subsequent mint. No cap, but an ever-increasing floor.\
\
The usage of Notes allows the system to track all user activity via metadata. This brings many advantages, for example: A user can sell or transfer their Note, including its collateral and minted DYAD balance.\
\
Another pro, is that in the case of liquidation, the collateral never has to move. It’s only the ownership that changes in the metadata of the Notes. With this implementation, only one vault per asset type has to be deployed on-chain.\
\
As a Note locks collateral and accumulates share tokens in various Vaults, its entitlements to those Vaults’ collateral pools will in aggregate form a blended collateral basket that’s unique to the Note. \
\
Due to gas limitations on Ethereum, the maximum number of collateral types per Note is set to five.

\
