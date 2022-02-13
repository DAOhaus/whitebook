---
description: 'fact: 80% of 150 > 100% of 100'
---

# ERC20DAO LENDING

For sake of example we will use an ERC20DAO token that is representative of the governance and revenue of an AirBnB. The manager wants to borrow the maximum amount possible against a property currently valued at $200,000 via traditional appraisal and has $30,000 in yearly revenue.

The DAO recognizes unrealized value in the property, with a $300,000 valuation at a 10% cap rate so is desirous to take on the property. It mints 100 property tokens (BNBT) and decides on a the following economics:&#x20;

* 20% market valuation buffer - $160,000
* 20% AMM position using USDC / BNBT pair  - 10 / $32,000
* 31% STAKE minimum - $49,600
* 40% Revenue drop to trigger AMM withdrawal vote - $21,000/yr

The asset will be collateralized at a secure liquidation price of $160,000 in order to account for pricing risks during a real world liquidation event.

The AirBnB manager now holds 80% of the asset, which at its new valuation is worth $224,000 according to the liquidity locked in the AMM.  That's a 10% increase literally happening overnight to capture the unrecognized value.

If the manager desires to stake these tokens to mint LEGT they may do so, however in order to offset the risk of defaulting on revenue deposit responsibilities -- such as in a "take the money and run" attack -- there is an imposed minimum where the total locked in the the AMM and the amount the DAO holds must equal above 50% of the BNBT.  That way the DAO can regain control and either appoint a new manager or sell the underlying asset but only if the revenue produced by the asset falls below the before agreed upon amount.

Since 20% is already allocated to the pool, the minimum amount in order to mint LEGT stable coin is 31% and equates to $49,600 with a maximum of $128,000 LEGT for all 80.  If foul play occurs the DAO closes the AMM and regains control of the underlying asset in order to either recoup loss or appoint a new manager.\
