# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`606a2f9e`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`d1e4ec9f`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`d1e4ec9f`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`bb9534d2`)
  
