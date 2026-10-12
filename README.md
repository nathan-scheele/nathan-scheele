### Nathan Scheele

Software engineer on Shopify Plus commerce: storefront themes, Shopify Functions, and TypeScript services on Cloudflare Workers. Most of my work lives in private repositories; public projects are pinned below.

#### How I work with coding agents

I use Claude Code every day. The agent writes much of the code; the constraints decide what lands:

- Parallel sessions in separate git worktrees, with hooks that keep edits inside the worktree and block changes to generated files, migrations and secrets.
- Plans stress-tested in an adversarial review before any code; decisions recorded in architecture decision records.
- Strict TypeScript with a lint rule banning type assertions, CI that fails on generated-code drift, and a code-review agent on all code.

TypeScript · Shopify Plus · Shopify Functions · Cloudflare Workers · GraphQL
