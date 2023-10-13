# rain-x-treescribe

- Some broken links, but this article we wrote contains the idea: https://querylaw.com/au/articles/wet_code_dry_code_damp_code
- This contains the design principle: https://querylaw.com/au/articles/code_is_law

## Pseudo code

- flow caller increases an amount that an address may withdraw 
- address withdraws an amount that they specify and specify 1 address other than self (reverts if those addresses did not approve prior) 
- there is an absolute unix timestamp after which a nominated address (hardcoded) may withdraw unlimited amounts 

## Standard wrapper obligations

- Each party bears its own gas costs.
- Legal contract is not operative until all smart contracts have been deployed to stipulated blockchain.
- The entity represented by the person who signs a transaction is responsible for the transaction; and
- We should address who is to be communicated with (for a decentralised project) as a representative.
- Code comments are not legally operative.

## Mechanism specific obligations

- Legal contract is not operative until Customer deposits money to escrow contract (human activity governed by legal obligation).
- Expert determination takes place in the context of payment amount relative to completion only (no damages etc).
- Expert provides default judgment of full amount where the customer doesn’t property participate in the expert determination process.
 
## Conceptual elements

- Contract is working with fixed fee structure.
- There is a definition of “Completion”.
- “Completion” is specified by reference to a “Work Specification”.
- Escrow key holder paid a small fee to operate third key on escrow.
- Dispute Resolution Discussion should not block expert determination.

## Process

- Escrow Amount is deduced as an absolute dollar amount smaller than the total fixed fee price of work, which could be, legally speaking:
  - final milestone;
  - second half of payment after deposit.
- Customer deposits escrow amount to escrow under the smart contract.
- When Provider considers that Services output satisfies “Completion”, they notify the Customer.
- If payment refused or not provided on time, provider can kick off expert determination process for escrow amount.
- Expert decides amount [party amount?] and turns the second key with the Provider if they consider completion reached.
