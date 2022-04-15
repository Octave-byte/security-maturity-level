# Rari Capital Analysis

## Context

Rari Capital is a suite of decentralized finance protocols including Fuse (a lending/borrowing protocol), Earn (a yield aggregator)and Pool2 (a decentralized exchange liquidity incentives).
This risk assessment focuses on Fuse protocol and Earn protocol.

## Results
| Category    | Security Maturity Level  | Comments    |
| ------------- |:-------------:|:-------------:|
| Audits |   Level 4            |           |         
| Bug Bounty |    Level 4           |   No public information with respect to submissions         |      
| Value at Risk |  Level 5              |           |   

## Governance

A 2/3 multisig detained by anonymous core members has the ability to shutdown and upgrade contracts.

## Oracle
Multiple oracle are integrated including : 
Chainlink Price Feeds, Uniswap/Sushiswap, and Uniswap V3.

## Audits [(Summary)]
| Date | Performed by  |  Duration  |  Scope |  Findings  | Findings addressed | Protocol |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| :-------------:| :-------------:| 
| [Dec 2020](https://certificate.quantstamp.com/full/rari-capital) | Quantstamp  |  4 months  | Smart Contracts  | 3 high / 6 medium / 5 low| 3 high / 5 medium / 3 low | Earn V1 |   
| [Dec 2020](https://certificate.quantstamp.com/full/rari-capital-v-2) | Quantstamp |  7 months | Formal Verification  | 3 high / 6 medium / 9 low | 3 high / 5 medium / 4 low| Earn V2 | 
| [Jun 2021](https://certificate.quantstamp.com/full/fuse-contracts) | Quantstamp |    | Smart Contracts  | 1 high / 1 medium / 6 low  | 1 high/ 1 medium / 1 low  | Fuse| 
| [Jul 2021](https://certificate.quantstamp.com/full/rari-capital-on-chain-governance) | Quantstamp |  4 weeks  |On Chain Governance | 2 medium / 2 low  |  2 medium / 2 low  | | 
| [XXX]() | Omniscia |  ---  | |  |   | |
| [XXX]() | OpenZeppelin |  ---  | |  |   | |


Summary:
- [Multiple audits](https://info.rari.capital/security/) performed on major product releases
- Economic security audit performed
- No formal verification


## Bug Bounty
 - Bug bounty competitive?

 Yes on Immunefi, payout is breakdown this way : 
 
 1. $250,000 - critical severity issue

2. $100,000 - high severity issue

3. $50,000 - medium severity issue

4. $10,000 - low severity issue

 - Payouts in the past?

 No public information available

## Value at Risk
$907 million value reached as of April 2022, max is $1.6 billion on December 2021 (reference: https://www.defipulse.com/projects/rari-capital)
