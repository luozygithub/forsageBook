# FDT Liquidity LP Mining

In order to incentivize more long-term value investors, FireDAO has launched an （a） Liquidity  LP Mining incentive activity for FDT. Each community member can lock the Liquidity LP of FDT and BNB’s into the liquidity mining pool, and can mine the incentive token FLM. The obtained FLMs can be converted to FDTs, which will be released linearly within two years.

Different mining weight coefficients are determined by various lockup period. The longer the lock-up is, the higher the mining weight will be. Mining pools enforce specific reward policies depending on the number of FD-SBT-005 owned by different wallets.

During this lock-up, the protocol mints a total of two SBTs, FD-SBT-001 and FD-SBR-005. FD-SBT-001 is mainly used to count the FDT comprehensive position information of this Soul Account, and FD-SBT-005 is to count the liquidity mining information. The entire ecology will distribute FDT ecological dividends according to the position weight ratio of FD-SBT-001, and provide liquidity mining rewards according to the position weight ratio of FD-SBT-005.

The minting quantity of FD-SBT-001 is determined by the number and weight coefficient of FDT contained in the LP during LP’s lock-up. If the LP contains 10,000 FDTs, for example, the position is locked for 3 months, and the weight coefficient is 3, then the minting amount is 30,000 FD-SBT-001s. Meanwhile, since the amount of FDT contained in LP changes from time to time, if the lock-up matures and LP needs to be withdrawn from the mining pool, the same proportion of FD-SBT-001s will be burned according to the proportion of withdrawn LP. If the lock-up time ends and LP is not withdrawn from the lock-up pool, the order will continue to enjoy the original policy.

The number of minted FD-SBT-005 is determined by the number of LPs and the weighting system when the LP is locked. In the case of current lock, 1 LP can mint 1000 FD-SBT-005s. If locked for 3 months and the weight factor is 3, then 1 LP can mint 3000 FD-SBT-005s. In the meantime, if the lock-up matures and LPs need to be withdrawn from the mining pool, the same proportion of FD-SBT-005s will be burned according to the proportion of withdrawn LPs.

## FDT Liquidity LP Mining Weight Design

|  No. | Lock-up Period |  Weight Coefficient  
| :--: |  :----------:  | :-------:
|  1.  | Demand Deposit |    1
|  2.  |    1 month     |    2
|  3.  |    3 months    |    3
|  4.  |    6 months    |    4
|  5.  |    12 months   |    5
|  6.  |    24 months   |    6
|  7.  |    36 months   |    7
