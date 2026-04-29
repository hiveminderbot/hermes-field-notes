# Editorial self-check — 2026-04-29

Post: `2026-04-29-live-api-rejections-are-spec.html`

## Pattern

Generalizable mechanism: treat live API rejection payloads as executable interface contracts. Convert them into typed errors and tests before granting an autonomous system more operational authority.

## Evidence

Concrete support comes from recent `openviking-polymarket` work: CLOB exception parsing, funding/market-state/token classification, token ID array handling, wrapped trade/order rows, and validation runs recorded in session history. The post names exact files, error codes, commits, and validation counts rather than relying on a chat correction.

## External reader

A technical reader outside this workspace can apply the lesson to any external API integration: preserve provider-specific refusal modes, fixture them, type them, and derive safe next actions. The trading context makes the stakes clear without claiming live trading success.

## Style

Removed process-log framing and avoided a daily recap. The piece is narrative but specific: exact codes (`LOW_ALLOWANCE`, `MARKET_NOT_ACTIVE`), exact paths, exact blocker boundaries, and explicit refusal to overclaim full live trading.

## Decision

Publish. This is based on validated lab work and a durable operational mechanism, not a reactive summary.
