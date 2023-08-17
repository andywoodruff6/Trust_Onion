# Cornucopias Racing League Trust Onion
Date Created: [[2023-08-14]]
Links:

---
---
## Trust Framework Worksheet

Cornucopias is an MMORPG where players can explore the bubble-verse (meta-verse).
- Cornucopias Racing League (CRL)

### Issuer
> [!question]- Who issues trusted data in your ecosystem? 
> Who provides the Issuer Wallet where the issuer stores their private keys?
> Who provides services that enable the issuer to issue and revoke credentials and write on the blockchain

- Cornucopias organization would hold the issuing wallet. More specifically the wallet holder(s) would represent the CRL governing body.
- The issuer would likely want to have an [[PRISM Agent Enterprise]] system set up to allow potential holders to register automatically. 
	- A reason to revoke credentials is not clear at this time.


#### Credentials
> [! question]- What credentials are issued and what data do they contain?
> How are they issued? (programmatically or manual) (website or app)
> How are the credentials sent to the Holders? (email, SMS, QR code)

- Credentials would need to be issued programmatically. For a smooth UX, players would be able to access a kiosk in the game near the racing portal. From here players would be able to scan a QR code to receive the credential. 
- Data:
	- Rider ID (UUID)
	- Rider Nickname or In game name
	- Date Created
	- Team / Organization name (optional)

If there was some form of overall Copi ID system you could add some of that information if there was a use case for it. 

### Policy Maker
> [!question]- Who makes the policy that Issuers, Holders, and Verifiers must follow?
> How is the policy developed and whose expertise must policy makers rely on?
> How is the policy documented?

- There is no official governing body for an eSports racing league, so the Issuer(cornucopias) would have free reign to set up the system in anyway they like. 
- It would be ideal to talk to entities who have launched their own credentials already to gather lessons learned.

### Holder
> [!question]- Who are the people, organizations or things that need to prove data about themselves in your ecosystem?

- The holders will be people who are wanting to race in the CRL. 
- There will be no organizations or things that would hold the credentials.


#### Wallet
> [!question]- What type of wallet do Holders have and who provides the wallets?
> - Mobile Wallets, also known as edge wallets, store credentials on a prover's device such as: Mobile App Wallets, Browser Wallets or Hardware Wallets.
> - Web-based Wallets store the Holders data in a personal vault in the cloud.

- A mobile wallet would be the most ideal for the use case. 
- Unfortanently at this moment in time no cardano native wallets support AP DIDs and VCs
- Wallet options would include: Proofspace, or [[Trinsic]] Wallet


### Verifier
> [!question]- Who are the people, organization or things that need to verify data about Holders in order to perform actions?
> What are these actions?
> Who provides the tools (known as the verifiable credentials toolkit) that enables Verifiers to request and validate proofs?

- The CRL would verify each racer as they sign in to race ranked. 
- At this time no other organization or thing would verify data about the holder.
	- I cannot think of additional use cases that other COPI business would have for a racing license or other information in the credential 
- The VC toolkit would be built in house to optimize the UX. This would also speed up verification time as Atala Prism Infrastructure could be set to run in the physical location as the game servers.

### Points of Engagement
> [!question]- What data must Verifiers verify about Holders in order to perform a given action?
> How much data is actually required?
> Would sensitive disclosure suffice?
> Does the data need to be stored afterward?

- The data does not need to be stored and would be get checked and then forgotten.
- The first engagement point would be when a player wants to sign up for the racing league and they visit the sign up portal. This is where they would have their credential created and sent to their wallet. 
	- One note is that the user will need to get a wallet and set up a DID prior to being able to do this.
- The second engagement point is when the now holder is ready to race and submits their credential for verification to enter the racing league portal.

### Business Model

#### Revenue Streams
> [!question]- What services do we provide?
> Who pays for these services?
> Who are the competitors and what do their revenue streams look like?

- F1 Esports uses a centralized system where participants must create an account with f1esports.com then fill out a written contract if the qualify for the second round. Drivers also must be over 16.
- iRacing is another competitor who utilizes a traditional web2 system like F1 Esports.
- The issuing and verification infrastructure would be ran by Cornucopias.  

#### Value Proposition
> [!question]- What value do we deliver to Issuers, Verifiers and/or Holders?

When a sporting event is conducted in an equal and fair manner everyone wins. Cliche, but true. For the holder it is reassuring that the driver they beat in one race is the same person racing in the next event.
For Cornucopias (Issuer and Verifier) who has expressed the desire to grow this league into an esports event remaining controversy free is important. This also sets the ground work for future identity measures that the game leads have discussed. 


---