# Award member points

[← MCP guides](README.md) · **Who:** Authorised administrators

**Try:**

> Use $tzh-point-assignment to prepare a 10-point award for Demo Member with reason “Event participation”. Find the account and show the preview; do not commit.

1. Confirm the account returned by `search_point_members`; choose when several accounts match.
2. Use either active policy selections or one free-form positive point amount and reason. For a money-based policy, supply its RM amount; fixed policies need none.
3. Inspect the full preview: every recipient and contribution, points per member, total points, ledger entries and expiry.
4. Explicitly approve that exact preview if correct. Check the committed result and the member's [My Points](https://tzhsports.vercel.app/my-points) history.

**Expected:** Discovery/preview writes no points. Commit applies the approved award once. This MCP workflow supports positive awards only; use [website Points Management](../website/commerce-rewards.md#points) for deductions. Do not manually duplicate automatic paid-spend awards.

If a preview expires or policies change, obtain and approve a new preview. An uncertain retry uses the same approved preview.
