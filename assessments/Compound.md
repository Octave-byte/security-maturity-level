# Compound Analysis

## Results
| Category    | Security Maturity Level  | Comments    |
| ------------- |:-------------:|:-------------:|
| Audits |   Level 5             |           |         
| Bug Bounty |    Level 5            |   No public information with respect to submissions         |      
| Value at Risk |  Level 5              |           |   

## Governance
In general 48 hour timelock.

As a precaution, the Compound community multisig has the ability to engage a failover that will switch a market's primary oracle from the Chainlink Price Feeds to Uniswap v2. The multisig is able to change to a failover for single markets.  

## Oracle
Chainlink Price Feeds

## Audits [(Summary)](https://compound.finance/docs/security)
| Date | Performed by  |  Duration  |  Scope |  Findings  | Findings addressed |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| :-------------:|
| [Apr 2019]() | Trail of Bits  |  8 weeks  | Smart Contracts  | 4 high|  |    
| [May 2019]() | Certora |   | Formal Verification  | The verification of the Compound Protocol succeeded in proving that the implementation correctly matches the specification. | All resolved, verification integrated into deployment process|   
| [Aug 2019]() | OpenZeppelin |    | Smart Contracts  |  |  |  
| [Aug 2019]() | Trail of Bits |  2 weeks  |Smart Contracts | 1 high / 1 medium / 2 low  |    |
| [Oct 2019]() | OpenZeppelin | Not specified, based on documentation approx. 1 week  | Timelock Contract | 1 medium / 1 low   | All resolved  |   
| [Feb 2020]() | Trail of Bits  |  11 days  | Governance System & Token  | 0 |  |    
| [Feb 2020]() | Gauntlet  | Not specified, based on documentation approx. 4 weeks| Economic/Market Simulations      | No major findings |  |  
| [Feb 2020]() | OpenZeppelin |Not specified, based on documentation approx. 2 weeks | Alpha Governance System   | 2 high / 3 medium / 6 low  | high findings resolved |  
| [Feb 2020]() | OpenZeppelin | Not specified, based on documentation approx. 1 week | MCD & DSR Integration  | 3 medium  |  |    
| [Apr 2020]() | OpenZeppelin | Not specified, based on documentation approx. 1 week | Tether Integration  | 1 medium / 3 low  |  |
| [May 2020]() | OpenZeppelin  |  Not specified, based on documentation approx. 1 week  | COMP Distribution System Smart Contracts   |  0 |  |

Summary:
- [Multiple audits](https://compound.finance/docs/security#audits) performed on major product releases
- Economic security audit performed
- [Formal verification](https://compound.finance/documents/Certora.pdf) is part of deployment process


## Bug Bounty
 - Bug bounty competitive?

 Yes, max. payout $150k

 - Payouts in the past?

 No public information available

## Value at Risk
$1000 million value reached in October 2020 (reference: https://defipulse.com/compound)
