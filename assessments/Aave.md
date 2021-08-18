# Aave Analysis

## Results
| Category    | Security Maturity Level  | Comments    |
| ------------- |:-------------:|:-------------:|
| Audits |     Level 5          |      |         
| Bug Bounty |    Level 5             |           |      
| Value at Risk |     Level 5            |           |      

## Governance
Short and long timelock (depending on proposer), "guardian" allowed to veto / cancel proposals.

As a precaution, the fallback price oracle is currently maintained by the Aave team.  

## Oracle
Chainlink Price Feeds

## Audits
| Date | Performed by  |  Duration  |  Scope |  Findings  | Findings addressed |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| :-------------:|
| Sep 2019 |Trail of Bits   |  4 weeks  | Smart Contracts  |  7 high / 2 medium / 3 low | All high findings resolved |
| Jan 2020  | OpenZeppelin  | Not stated, based on documentation approx. 4 weeks   | Smart Contracts  | 5 critical / 7 high / 11 medium / 18 low |  All severe findings have been resolved|
| May 2020 | ConsenSys Diligence  | 3 days  |   CPM Price Provider Uniswap Market | 2 findings unrated - approx. both high findings  | All resolved |
| Jun 2020|  Certora |  |  Formal Verification  |2 high / 1 medium / 4 low   | All major findings resolved |
| Jul 2020|  Certik |  12 days | Smart Contracts   |1 medium / 1 low    | All resolved |
| Jul 2020|  Consensys Diligence |  3 days | Smart Contracts   |  1 low | All resolved |
| Aug 2020|  PeckShield |  Not stated, based on documentation approx. 2 weeks  |  Credit Delegation Vault | 1 high / 3 medium / 3 low  | All resolved |
| Aug 2020|  ConsenSys Diligence | 15 days  | Aave Governance DAO   | 2 high / 1 medium / 1 low  |All major findings resolved|
| Sep 2020| MixBytes  | 2 weeks  |   v2 Protocol Smart Contracts | 9 medium / 44 low  | Mostly resolved |
| Sep 2020| PeckShield  | Not stated, based on documentation approx. 2 weeks  | v2 Protocol Smart Contracts    |  1 critical / 2 high / 6 medium / 8 low | All high findings resolved |
| Sep 2020| CertiK | Not stated, based on documentation approx. 2 weeks  |  v2 Protocol Smart Contracts  |  3 low | All resolved |
| Sep 2020| ConsenSys Diligence |  4 weeks |   v2 Protocol Smart Contracts | 4 medium / 5 low  | Mostly resolved |
| Sep 2020|  CertiK  |   Not stated, based on documentation approx. 1 week | Safe Module Contracts   |  0 | |
| Sep 2020| ConsenSys Diligence   | 10 days  |  Safe Module Contracts  |  1 medium / 2 low|  All resolved|
| Jan 2021| SigmaPrime  |  Not stated, based on documentation approx. 2 weeks   |  v2 Protocol Smart Contracts   | 1 high / 1 low  | All resolved |



## Bug Bounty
 - Bug bounty competitive?

Yes, up to $250k

 - Payouts in the past?

 No public information available.

## Value at Risk
$1000 million value reached in August 2020 (reference: https://defipulse.com/aave)
