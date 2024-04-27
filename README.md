# ZKDID Prototype Application: Version 1 Alpha

This application showcases an initial proof of concept (PoC) for the Zero Knowledge Decentralised DNS (dDNS) proof of personhood protocol utilising .zkdid domain as the root of trust. Here’s a concise overview of what this code demonstrates:

- **Input and Computation:** Users enter a number to compute its square along with a proof of computation.
- **DWN Publishing:** Results and proofs are published to the user's Decentralized Web Node (DWN). Together with the DWN Record ID, these are used for registering a .zkdid domain on the Polygon Mumbai test network.
- **Verification and NFT Minting:** The proof and computed square undergo verification through a smart contract. If validated, an NFT symbolising domain ownership is minted.
- **Domain Resolution:** The registered .zkdid domain, generated from a SHA-256 hash of the proof and square, confirms the owner's knowledge of the original number by resolving to the stored proof.

This version 1 alpha is a preliminary demonstration, focusing on the essential mechanics of the .zkdid protocol to establish a foundation for further development and refinement.


----

### Tech used
- React (Vite)
- Third Web for web3 connection
- TBD Web5 for DWN
- ZoKrates for ZK proof generation and verifying
- Foundry for smart contracts
- Open Zeppelin for ERC721 (NFT)
