# NOTICE

We do not recommend any farming tools (中文：机枪池) to interact with the liquidity pool or deposit pool contract. In these two contracts, we use `tx.origin` instead of `msg.sender` in the withdraw function. If you have already linked with these two contracts, you can get your lp or token back by calling `emergencywithdraw`.  


## Smart Contract Addresses

KswapToken=0xab0d1578216A545532882e420A8C61Ea07B00B12

Factory=0x60DCD4a2406Be12dbe3Bb2AaDa12cFb762A418c1

Router=0xc3364A27f56b95f4bEB0742a7325D67a04D80942

LiquidityPool=0xaEBa5C691aF30b7108D9C277d6BB47347387Dc13

DepositPool=0x5E6D7c01824C64C4BC7f2FF42C300871ce6Ff555

Oracle=0x5d1F23b1564ce7A00C94f9Fa970D9c630369CA72

TradingPool=0x1FcCEabCd2dDaDEa61Ae30a2f1c2D67A05fDDa29

Treasury=0xd3D6Ac6D28A894993d7A84CC7eb27DbBE0f3af87

TeamVesting=0xaFA0Ae68E5b4a38c619d6139b2cA1aD418f14c14

InvestorVesting=0xa6b91cd9A82C73D7341Ad4A7add8d020A5874b49

InitCodeHash=0x73fce53e0c877f17bc03bb34eead12c2c3f30d3493cff1259744d0c0dfcb3a92


