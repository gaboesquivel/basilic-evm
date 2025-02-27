# BasilicEVM: FullStack EVM Project Starter

A performance-optimized development stack for EVM applications. Built with Foundry, viem/wagmi, and Next.js 15.

## Stack Components

- __Contracts__: Foundry, Solidity ^0.8.19
- __Chain Integration__: viem/wagmi, Alchemy RPC
- __Frontend__: Next.js 15, React Server Components
- __Data Layer__: Ponder indexing, Supabase
- 
## Project Structure

### Apps
- [__apps/web__](./apps/web/README.md) - Next.js frontend
- [__apps/ponder__](./apps/ponder/README.md) - Chain indexing service

### Packages
- [__packages/ui__](./packages/ui/README.md) - Shadcn/ui and custom components
- [__packages/core__](./packages/core/README.md) - Chain interactions, contract ABIs
- [__packages/react__](./packages/react/README.md) - Web3 React hooks
- [__packages/supabase__](./packages/supabase/README.md) - Database/auth integration
- [__packages/lib__](./packages/lib/README.md) - Shared utilities
- [__packages/tsconfig__](./packages/tsconfig/README.md) - TypeScript configuration

## Development Setup

### Requirements
- Node.js 18+
- pnpm
- Foundry
- Git

### Quick Start

```bash
npm install -g pnpm
curl -L https://foundry.paradigm.xyz | bash
foundryup
git clone https://github.com/blockmatic/basilic-evm.git
cd basilic-evm
pnpm install
```

For detailed information about our backend architecture, including how Ponder.sh and Supabase work together, database branching, and deployment workflows, please refer to [BACKEND.md](./BACKEND.md).

### Development Commands

```bash
pnpm backend    # Start Supabase & Ponder 
pnpm dev        # Dev server
pnpm build      # Production build
pnpm test       # Run tests
```

## Technical References

- [viem](https://viem.sh)
- [wagmi](https://wagmi.sh)
- [tanstack query](https://tanstack.com/query)
- [thirdweb connect](https://thirdweb.com/connect)
- [Next.js](https://nextjs.org/docs)
- [Ponder](https://ponder.sh/docs)
- [Supabase](https://supabase.com/docs)
- [Foundry](https://book.getfoundry.sh)
- [EIP-2771: Meta Transactions](https://eips.ethereum.org/EIPS/eip-2771)
- [0x Protocol Gasless API](https://0x.org/docs/gasless-api/introduction)

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for development guidelines.

## License

MIT License

