## Welcome to Coxygen Global Real World Applications MVP Project

Our work on this has been ongoing, beginning with research and exploration of Cardano ecosystem.

## Problems: Broken, abondoned tools and playgrounds. Just look at the list below:- 

[Plutus Playground](https://playground.plutus.iohkdev.io/)

<img width="1917" height="1029" alt="image" src="https://github.com/user-attachments/assets/4540843e-a17e-4390-a551-3c9b6c6a8113" />

[Plutus Kuber IDE Offline](https://kuberide.com/)

<img width="1917" height="1029" alt="image" src="https://github.com/user-attachments/assets/7d885532-4f37-43b1-963c-41806293c66c" />

[Plutus Mock Tx not working](https://github.com/besiwims/COTS)

<img width="1917" height="1029" alt="image" src="https://github.com/user-attachments/assets/6640d5f2-4bd9-423b-b1c0-421c15cfda0f" />

[Programmable Tokens Video Not Available](https://docs.fluidtokens.com/DemoWST.mp4)

<img width="1917" height="1029" alt="image" src="https://github.com/user-attachments/assets/4c957686-7618-4224-a792-8b89a4e14b81" />

## Past Work and Explorations, moving towards rapid templating:

1. https://github.com/wimsio/coxygen-mssd  
2. https://github.com/wimsio/plutus-nix  
3. https://github://github.com/besiwims/plutus-tx-template  
4. https://github.com/wimsio/universities/wiki/000-%E2%80%90-Beginner-Plutus-Validators-Mockups-Readme  
5. https://github.com/besiwims/BouncingBall  
6. https://github.com/besiwims/plutus-tx-template/wiki/Home-:-Plutus  
7. https://github.com/besiwims/plutus-tx-template/wiki/30-Lists-of-Plutus-Examples-&-Templates  
8. https://github.com/besiwims/plutus-tx-template/wiki/30-Lists-of-Plutus-Examples-Example-Code  
9. https://github.com/besiwims/plutus-tx-template/wiki/Simplified-Contract-Monad-with-example  
10. https://github.com/besiwims/plutus-tx-template/wiki/State-Machine-A-Simple-Voting-Contract  

Visit the website to read about value we will bring to Cardano development ecosystem: <a href="https://coxygen.co/rwa/">here</a> 

1. **Real Estate Tokenization**  
   **Industry:** Real Estate & Property Management  
   **Use Case:** Tokenize buildings into fractional NFTs (representing shares of property).

2. **Supply Chain Tracking**  
   **Industry:** Logistics & Manufacturing  
   **Use Case:** Track authenticity of goods (pharma, luxury, food).  
   **On-Chain Logic:**
   - Each batch/item has an NFT as a “digital twin.”
   - Smart contracts update location/status when a certified participant signs.
   - Tamper-proof handover chain (e.g., DHL handover → customs → retailer).
   **Off-Chain Components:**
   - IoT integration (QR/NFC scanning).
   - REST API to sync supply chain status.
   **Demo Potential:**
   - Show wine bottles tracked on-chain from vineyard → distributor → retail shop.

3. **Green Energy Credits**  
   **Industry:** Energy & Sustainability  
   **Use Case:** Tokenize renewable energy credits (REC) for trading.  
   **On-Chain Logic:**
   - Mint carbon credit tokens after oracle verification.
   - Expiry date enforcement in validator.
   - Peer-to-peer trading with on-chain auctions.
   **Off-Chain Components:**
   - Smart meter oracle API.
   - Marketplace UI for trading.
   **Demo Potential:**
   - Simulate solar farms minting credits that companies buy to offset carbon footprint.

4. **Commodities Tokenization**  
   **Industry:** Agriculture & Commodities  
   **Use Case:** Represent coffee, cocoa, or grain inventories as tokens.  
   **On-Chain Logic:**
   - Fungible tokens representing 1 ton units of commodity.
   - Escrow contracts for buyers/sellers to lock ADA until shipment verified.
   **Off-Chain Components:**
   - Warehouse proof oracle.
   - Logistics dApp dashboard.
   **Demo Potential:**
   - Tokenized coffee beans batch → buyers purchase via Cardano stablecoin.

5. **Healthcare Data NFTs**  
   **Industry:** Healthcare & Biotech  
   **Use Case:** Patient consent + secure access to medical records.  
   **On-Chain Logic:**
   - Patient issues NFT to represent consent for data access.
   - Validator ensures NFT must be returned/burned after research access ends.
   **Off-Chain Components:**
   - HIPAA/GDPR-compliant encrypted storage linked via IPFS.
   - Hospital portals for researchers to request access.
   **Demo Potential:**
   - Simulated patient NFT → researcher requests access → auto-expiry in validator.

6. **Art & Collectibles**  
   **Industry:** Creative Economy (Art, Music, Sports)  
   **Use Case:** NFT provenance & fractional ownership of fine art.  
   **On-Chain Logic:**
   - Mint art-backed NFT (with metadata hash of appraisal).
   - Optionally fractionalize into fungible tokens for co-ownership.
   - Smart contract redistributes resale royalties to artist.
   **Off-Chain Components:**
   - Appraisal oracle feed.
   - Gallery marketplace dApp.
   **Demo Potential:**
   - A famous painting NFT → auctioned → fractions sold on a Cardano DEX.

7. **Insurance Payout Automation**  
   **Industry:** Insurance & Risk Management  
   **Use Case:** Parametric insurance (e.g., crop, travel, health).  
   **On-Chain Logic:**
   - Policy NFT represents coverage.
   - Validator auto-triggers payout if oracle says condition met (e.g., rainfall < 50mm).
   **Off-Chain Components:**
   - Oracle feed for weather, flight cancellations, medical records.
   - Insurance dashboard for policy management.
   **Demo Potential:**
   - Flight cancellation oracle triggers instant ADA payout to NFT policy holder.

8. **Trade Finance & Invoicing**  
   **Industry:** FinTech & SME Finance  
   **Use Case:** Tokenize invoices for factoring & liquidity.  
   **On-Chain Logic:**
   - Each invoice is minted as NFT with metadata (amount, due date).
   - Buyers stake ADA to purchase invoices at discount.
   - Validator enforces redemption only after invoice settlement.
   **Off-Chain Components:**
   - ERP/accounting system oracle (QuickBooks, SAP).
   - Finance dashboard for SMEs.
   **Demo Potential:**
   - Simulated invoice NFT → investor buys at 95% → full repayment unlocks investor’s ADA + yield.

9. **Transport & Mobility Tokens**  
   **Industry:** Transportation / Mobility  
   **Use Case:** Tokenize vehicle ownership & mobility credits.  
   **On-Chain Logic:**
   - NFTs for vehicle digital IDs (car, bus, EV scooter).
   - Mobility credit tokens (miles, fuel, or EV charge credits).
   - Smart contracts for leasing & ride-sharing (escrow deposits + auto-release).
   **Off-Chain Components:**
   - IoT oracle for GPS & usage.
   - Transport company API for tickets & rentals.
   **Demo Potential:**
   - Rent a tokenized scooter → ADA escrow → auto-release when scooter returned.

10. **Education Credentials**  
    **Industry:** Education & Certification  
    **Use Case:** Decentralized diplomas, certificates, and micro-credentials.  
    **On-Chain Logic:**
    - Universities mint NFTs as verifiable credentials.
    - Validator ensures credentials tied to DID identity (no transfer).
    - Staking contracts to fund scholarships.
    **Off-Chain Components:**
    - University registrar API.
    - Wallet dApp to show certificates.
    **Demo Potential:**
    - Student wallet shows diploma NFT; employer verifies authenticity without third-party middleman.

11. **Medical Asset Management**  
    **Industry:** Healthcare / Medical Equipment  
    **Use Case:** Tokenize hospital equipment, medicines, or licenses.  
    **On-Chain Logic:**
    - NFTs for medical devices (track leasing, expiry, warranty).
    - Smart contract validates licensed operator NFT before usage.
    - Tokenized patient data access as per consent.
    **Off-Chain Components:**
    - Oracle from hospital ERP system.
    - IPFS for encrypted records.
    **Demo Potential:**
    - Hospital leases MRI machine (NFT) → ADA escrow → NFT access expires after term.

12. **Mining & Natural Resources**  
    **Industry:** Mining & Resource Extraction  
    **Use Case:** Tokenize ownership rights of mines & extracted resources.  
    **On-Chain Logic:**
    - NFTs for mining licenses/permits.
    - FT tokens representing tons of extracted resource (gold, lithium, oil).
    - Escrow smart contracts for resource pre-purchase contracts.
    **Off-Chain Components:**
    - Oracle for mine output reporting.
    - Satellite/geology report integration.
    **Demo Potential:**
    - Tokenized lithium batch sold to EV battery company on Cardano marketplace.

13. **Entertainment & Media Rights**  
    **Industry:** Media, Music, Gaming  
    **Use Case:** Tokenize movie/music royalties and gaming assets.  
    **On-Chain Logic:**
    - NFT for each media asset (movie, song, in-game item).
    - Royalties auto-split to stakeholders via validator.
    - Event ticket NFTs with resale control.
    **Off-Chain Components:**
    - Streaming service API oracle.
    - Web3 marketplace for fans & creators.
    **Demo Potential:**
    - Music track NFT → streams tracked via oracle → ADA royalties split to artist + producer.

14. **Agriculture & Farm Assets**  
    **Industry:** Agriculture & Food Supply  
    **Use Case:** Tokenize farmland, livestock, and crop futures.  
    **On-Chain Logic:**
    - NFT for farmland ownership & rental agreements.
    - Crop futures tokens (fungible tokens representing future yield).
    - Parametric insurance validator (payout if rainfall < threshold).
    **Off-Chain Components:**
    - Weather oracle integration.
    - Farm IoT sensors (soil, livestock health).
    **Demo Potential:**
    - Farmer mints crop future tokens → investors buy → oracle triggers payout if drought detected.

15. **Communication & Connectivity**  
    **Industry:** Telecom & Networking  
    **Use Case:** Tokenize bandwidth and communication services.  
    **On-Chain Logic:**
    - FT tokens represent bandwidth credits (e.g., 1GB = 1 token).
    - Validator enforces pay-per-use consumption.
    - NFT for SIM/eSIM identity.
    **Off-Chain Components:**
    - Telecom operator oracle (data usage).
    - IoT connectivity for billing.
    **Demo Potential:**
    - Buy bandwidth tokens → consume via oracle → tokens automatically burned as data is used.
