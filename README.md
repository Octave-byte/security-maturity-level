# DeFi Security Maturity Level

## Overview
| Project    | Security Maturity Level  | Governance  | Oracle | Last Review |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|
| [Compound](assessments/Compound.md) |  Level 5 ⭐  |  timelock | decentralized, community multisig oracle failover |  Aug 12, 2021  |        
| [Aave](assessments/Aave.md) |     Level 5 ⭐     | timelock  | decentralized, Aave team controls failover oracle |  Aug 12, 2021  |            
| [MakerDAO MCD](assessments/MakerDAO_MCD.md) | Level 5 ⭐ | timelock | decentralized |  Aug 18, 2021
| [Uniswap v2](assessments/Uniswap2.md) |  Level 4 🟢 | timelock | - | Aug 17, 2021
| [SushiSwap](assessments/Sushiswap.md) |  Level 4  🟢  | offchain, multisig| - |  Aug 17, 2021         
| [Yearn Finance](assessments/Yearn.md) |  Level 4 🟢 | offchain, multisig | - |  Aug 17, 2021            
| [Bancor](assessments/Bancor.md) |       Level 4 🟢   | offchain, multisig  | decentralized|  Aug 17, 2021
| [Synthetix](assessments/Synthetix.md) |   Level 4 🟢   | council-based, delegated | decentralized |  Aug 18, 2021      
| [Curve](assessments/Curve.md) |   Level 4  🟢   | timelock, emergency multisig | decentralized |  Aug 16, 2021   
| [ReflexerLabs](assessments/ReflexerLabs.md) |   Level 3  🟡   | temp. gov, admin, multisig | decentralized |    Aug 16, 2021
| [Alchemix](assessments/Alchemix.md) |   Level 3  🟡   |  multisig | - |   Aug 16, 2021
| [Convex Finance](assessments/Convex.md) |   Level 3  🟡   | multisig | - |   Aug 16, 2021
| [Idle Finance](assessments/Idle.md) |   Level 3  🟡   |timelock | decentralized |   Aug 16, 2021
| [UMA](assessments/UMA.md) |        Level 3  🟡     | timelock| optimistic oracle |    Aug 16, 2021   
| [Argent](assessments/Argent.md) |   Level 3  🟡   | - | - |   Aug 16, 2021              
| [Origin Dollar](assessments/Origin_Dollar.md) |  Level 2 🟠| multisig | decentralized |    Aug 18, 2021          


## Disclaimer
This repository is for informational purposes only and does not constitute an offer to sell, a solicitation to buy, or a recommendation for any cover-related staking, nor does it constitute an offer to provide investment advisory or other services.

## Methodology and Maturity Levels
The resulting security maturity level is based on public information only. The maturity levels are structured similarly to the [Capability Maturity Model](https://en.wikipedia.org/wiki/Capability_Maturity_Model) with custom goals/requirements, which need to be fulfilled to reach a certain maturity level:

| Category    | Level 1  🔴 | Level 2 🟠   | Level 3 🟡  | Level 4 🟢   | Level 5 ⭐   |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| Audits        | -           | Audits performed           | Audits from reputable security companies or individuals | Multiple audits from reputable security companies or individuals | 1. Multiple audits from reputable security companies or individuals <br />2. Formal verification conducted           |
| Bug Bounty    | -           | -           | Bug bounty program in place           | 1. Bug bounty program in place <br />2. Competitive payouts          | 1. Bug bounty program in place <br />2. High payouts  <br />3. Bug bounty submissions (if information public)         |
| Value at Risk | -           | >$1 million in the last 2 weeks           | >$10 million for at least 1 month      |  >$100 million for at least 3 months          |  >$500 million for at least 6 months  |
