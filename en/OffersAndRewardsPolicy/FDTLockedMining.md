# FDT Lock-up Mining

In order to motivate more long-term value investors, FireDAO has launched a FDT Lock-up Mining. Each community member can lock FDTs into the mining pool, assign different weight coefficients according to various lock-up period and can mine the incentive token FLMs. The obtained FLMs can be converted to FDTs, which will be released linearly within two years.

Different mining weight coefficients are determined by various lockup period. The longer the lock-up is, the higher the mining weight will be. The protocol relies on the number of  FD-SBT-006 to implement specific mining reward policy.

During this lock-up, the protocol mints a total of two SBTs, FD-SBT-001 and FD-SBT-006. FD-SBT-001 is mainly used to count the FDT comprehensive position information of this Soul Account, and FD-SBT-006 is to count the lock-up  mining information  for this Soul Account.. The whole ecology distributes the ecological income according to the proportion of holding weight of the FD-SBT-001, and rewards the lock position mining according to the proportion of holding weight of the FD-SBT-006.

The minting quantity of FD-SBT-001 is determined by the number and weight coefficient of FDTs during the lock-up. If 10,000 FDTs are locked, for example, the period for 3 months, and the weight coefficient is 3, then the minting amount is  30,000 FD-SBT-001s. If the lock-up matures and FDTs need to be withdrawn from the mining pool, the same proportion of FD-SBT-001s will be burned according to the proportion of withdrawal from the lock-up order. If the lock-up time ends and FDTs are not withdrawn from the lock-up pool, the order will continue to enjoy the original policy.

The minting quantity of FD-SBT-006 is determined by the number of FDTs and the weight coefficient during the FDTs lock-up. If 10,000 FDTs are locked for 3 months, and the weight coefficient is 3, then 30,000 FD- SBT-006s will be minted. If the lock-up matures and FDTs need to be withdrawn from the mining pool, the same proportion of FD-SBT-006 will be destroyed according to the proportion of FDTs withdrawal from the lock-up order. If the lock-up time ends and FDTs are not withdrawn from the lock-up pool, the FDTs will continue to enjoy the original policy.

## FDT Lock-up Mining Weight Design

|  No. | Lock-up Period |  Weight Coefficient  
| :--: |  :----------:  | :-------:
|  1.  | Demand Deposit |    1
|  2.  |    1 month     |    2
|  3.  |    3 months    |    3
|  4.  |    6 months    |    4
|  5.  |    12 months   |    5
|  6.  |    24 months   |    6
|  7.  |    36 months   |    7