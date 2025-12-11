AlmaChain — Core Features
1. Alumni Donation Registration (On-chain)
Alumni donate using testnet tokens (Ethereum Sepolia).
Smart contract stores:
Donor address
Amount
Timestamp
Purpose
No modification possible → removes manipulation and increases trust.

2. Fund Allocation & Usage Tracking
Institute admin uploads:
Expenses
Invoices
Distribution data
Invoices stored on IPFS, and the CID is saved on-chain.
Ensures spending is transparent and tamper-proof.

3. Proof-of-Spend Verification
For each spending record:
Admin uploads proof → IPFS
Hash stored on blockchain
Alumni and batchmates can verify that:
Proof exists
It was not modified
Strengthens accountability.

4. Public Transparency Dashboard
Displays:
Total donation amount
How funds were used
Invoice viewing (IPFS)
Filters by alumni, batch, purpose
Acts as the main evaluation showcase for academic assessment.

5. Role-Based Access Control
Alumni: Donate + View spending
Institute Admin: Add fund usage
Auditor: Approve or reject spending
Public: View-only
Represents real-world system design.

6. Smart Contract Events
Emitted for indexing via The Graph:
DonationReceived
FundUsageAdded
FundUsageApproved
Enables real-time dashboard updates and enhances research depth.