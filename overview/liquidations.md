# Liquidations

When a user's collateral value falls below the required 150% collateralization ratio, (relative to their minted DYAD), they can be liquidated. Any note holder can trigger a liquidation. The liquidator repays the outstanding minted DYAD and receives collateral, plus a 20% liquidation reward, in return.\
\
With the launch of DYAD V2 it is now possible to partially liquidate a position. The mechanism works the same as described above, only a liquidator can opt to 'partially fill' a position that is eligible for liquidation. With partial liquidations, users can work together to liquidate positions that would otherwise be too large to tackle.

Liquidation rewards in partial liquidations are proportional to the debt that is liquidated. If a note liquidates the full debt, a 20% liquidation reward is obtained. However, if less then the full debt is liquidated, the liquidation reward shrinks relative to the amount of DYAD that is repaid.

**Examples:**\
\
**Full liquidation**

_100 DYAD is up for liquidation because the collateralization ratio has fallen below 150%_

A note liquidates the full debt and hence obtains $100 worth of collateral plus 20% liquidation reward.

**Partial liquidation**

_100 DYAD is up for liquidation because the collateralization ratio has fallen below 150%_

A note liquidates 50 DYAD and hence obtains $50 worth of collateral plus 20% / (100 DYAD / 50 DYAD) liquidation reward. This results in $50 worth of collateral plus a 10% liquidation reward. This incentivizes liquidators to fully repay the DYAD debt and obtain the maximum liquidation reward.



\
