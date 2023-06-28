# Coffee Shop Loyalty Rewards Trust Onion
Date Created: [[2023-06-27]]
Links:

---
---

## Trust Framework Worksheet
This is a practice worksheet for a coffee shop called First Sip who has four locations within the same town. 

### Issuer
> [!question]- Who issues trusted data in your ecosystem? 
> Who provides the Issuer Wallet where the issuer stores their private keys?
> Who provides services that enable the issuer to issue and revoke credentials and write on the blockchain

- Each store location would be an issuer.
- Each store location would store their own private key.
- I will build a terminal device to allow stores to issue and revoke credentials

#### Credentials
> [! question]- What credentials are issued and what data do they contain?
> How are they issued? (programmatically or manual) (website or app)
> How are the credentials sent to the Holders? (email, SMS, QR code)

- Credentials are issued manually when the holder decides they want to join. Joining would only be available at the coffee shop.
- Credentials are shared via a QR code scan in person.

### Policy Maker
> [!question]- Who makes the policy that Issuers, Holders, and Verifiers must follow?
> How is the policy developed and whose expertise must policy makers rely on?
> How is the policy documented?

- This space is not regulated.

### Holder
> [!question]- Who are the people, organizations or things that need to prove data about themselves in your ecosystem?

- The holders will be patrons of the coffee shop. 
- No organizations or things would be holders at this time.

#### Wallet
> [!question]- What type of wallet do Holders have and who provides the wallets?
> - Mobile Wallets, also known as edge wallets, store credentials on a prover's device such as: Mobile App Wallets, Browser Wallets or Hardware Wallets.
> - Web-based Wallets store the Holders data in a personal vault in the cloud.

- Holders will need a mobile wallet almost certainly on their phone.
- Any wallet compatible with the [[Atala Prism]] stack would be viable. Ideally something with a minimal and clean UX/UI would be ideal as control and security are not critical.

### Verifier
> [!question]- Who are the people, organization or things that need to verify data about Holders in order to perform actions?
> What are these actions?
> Who provides the tools (known as the verifiable credentials toolkit) that enables Verifiers to request and validate proofs?

- Each coffee shop would be a verifier. No other people, organizations or things would be verifying at this time. 
- Customer scans a QR code to tell the terminal to request proof from them. This would start the present proof work flow.

### Points of Engagement
> [!question]- What data must Verifiers verify about Holders in order to perform a given action?
> How much data is actually required?
> Would sensitive disclosure suffice?
> Does the data need to be stored afterward?

- Verifiers name and email address. I would also add what store the customer is at to the registry.
- Data about the visit would need to be stored. This data would be a tally of the number of items or the value of the items for the purpose of knowing when a reward can be claimed.

### Business Model

#### Revenue Streams
> [!question]- What services do we provide?
> Who pays for these services?
> Who are the competitors and what do their revenue streams look like?

- The coffee shop will pay for this system. 
- Square [[Loyalty Rewards Programs]] charge 100$ per month if you have more than 1500 customers. That’s just 50 loyalty members per day.

#### Value Proposition
> [!question]- What value do we deliver to Issuers, Verifiers and/or Holders?

- The value prop to the coffee shop (issuer & verifier) is cost. At 50$ per month a store that had 50 loyalty users per day would save 600$ per year.
- The value prop to the holder is that they would be able to see their reward status on their phone.
	- This could also be a benefit to the coffee shop as it could encourage more traffic to the shop.

---