# Elixir website

Marketing site and docs for [Elixir](https://github.com/Credivis-Labs) — a Squads-equivalent
treasury multisig for Stellar.

Next.js (App Router) + TypeScript + Tailwind CSS.

## Develop

```
pnpm install
pnpm dev
```

Open http://localhost:3000.

## Checks

```
pnpm build      # generates .next/types that typecheck depends on
pnpm typecheck
pnpm lint
```

## Notes

This site does not depend on `@credivis/elixir-sdk` and does not sign transactions. The dapp
lives in `Elixir-dapp-frontend` and deploys separately.

## License

AGPL-3.0-or-later
