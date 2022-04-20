# Aave V3 Analysis

## Context

Aave V3 is a major update of the Aave protocol which is a non custodial liquidity protocols where users can participate as borrowers, lenders or liquidators. 
Aave V3 improves core concepts of previous protocols versions on Capital Efficiency (portal, efficiency mode, isolation mode) and Risk Management.


## Results
| Category    | Security Maturity Level  | Comments    |
| ------------- |:-------------:|:-------------:|
| Audits |     Level 5          |      |         
| Bug Bounty |    Level 5             |           |      
| Value at Risk |     Level 5            |           |      

## Governance
Timelock : non-specified length. 
There are two different lengths for the timelock, In V2 it is identified as 3 days and 10 days, though there is no clear explanation of any change on Aave V3 in comparison with V2.

As for V2, the fallback price oracle is currently maintained by the admin team.  

## [Oracle] (https://docs.aave.com/developers/core-contracts/aaveoracle)
Chainlink Price Feeds

## Audits
| Date | Performed by  |  Duration  |  Scope |  Findings  | Findings addressed |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| :-------------:|
| Nov 2021 | Open Zeppelin   |  Not specified  | Smart Contracts  |  2 critical / 3 high / 1 medium / 7 low | All high findings resolved |
| Nov 2021  | Trail of Bits  | 4 weeks   | Smart Contracts  |  5 high / 1 medium / 2 low |  All high, medium and low findings have been resolved|
| Jan 2022 | Peckshield  | Not specified  |  Smart Contracts  | 2 high / 3 medium / 4 low  | All resolved |
| Jan 2022|  ABDK Consulting | Not specified |  Smart Contracts   | 4 critical / 11 high / 9 moderate medium  | Not specified  |
| Jan 2022|  SigmaPrime |  Not specified | Smart Contracts and Economic security  | 3 low  | 2 low |
| Jan 2022|  Certora |  13 weeks | Formal verification  | 1 critical / 2 high / 2 medium / 1 low  | All resolved |


Summary:

- [Multiple audits](https://docs.aave.com/developers/security-and-audits) performed
- Formal verification

## [Bug Bounty](https://github.com/aave/bug-bounty?utm_source=immunefi)
 - Bug bounty competitive?

Yes,

Medium = Up to 5,000 USDC
High = Up to 10,000 USDC
Very High = Up to 50,000 USDC
Critical = Up to 250,000 USDC

 - Payouts in the past?

 No public information available.

## Value at Risk
$1000 million value reached in August 2020 (reference: https://defipulse.com/aave)
