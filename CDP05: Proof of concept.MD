
# Proposal: Proof of concept

Author(s): Nick010

Last updated: 26-06-2022

## Abstract

To validate the concept and architecture, a proof of concept will be created. The proof of concept will exist out of most components as used in the solution design and architecture.

## Proposal

The purpose of this proof of concept is to sell tickets using the CHI Ticketing protocol and add the ticket income (CHI Cash) to the DAO treasury of the event.

**CHI Ticketing protocol:**  
The CHI Ticketing protocol for the POC supports paid tickets. Users can buy tickets using CHI Cash (Balancer LP token) or a custom ERC20 token for testing purposes.

  
**Balancer LP token:**  
CHI Cash LP tokens are available on the Polygon network and created according proposal  
  

**Aragon DAO integration:**  
The CHI Ticketing protocol is connected to an Aragon DAO. The ticket revenue will be added to the DAO via the Aragon Agent App.

## Rationale

Out of scope:  
- A liquid supply for CHI Cash based on the underlying assets  
- Integration of Ticket contract in Aragon as an app.

## References

Balancer proposal
