# Query and record attendance

[← MCP guides](README.md) · **Who:** Authorised administrators

**Read-only try:**

> Use $tzh-lesson-attendance to show missing attendance last week. Include the resolved Malaysia range and whole-query counts. Do not record anything.

1. Use today/yesterday, this/last week, this/last month, or an explicit range up to 366 days. Ask for recorded or all states when needed.
2. Check the whole-query summary separately from the current page. Future lessons are **not due**; guests are excluded by default and **not tracked** if included. Missing records are not proof of absence.
3. To record outcomes, identify the exact returned lessons/enrollments. Ask to **preview** present, eligible absence or absence without replacement for students; lesson-wide actions are mark all present or centre cancelled.
4. Check the complete current/proposed state, reason, replacements issued/restored, seat/slot/cancellation effects, billing treatment, no-ops and expiry.
5. Explicitly approve that full preview, then verify the committed outcome and refreshed website roster.

**Expected:** Read/preview does not record attendance. An approved batch saves atomically. Existing charges are preserved for the attendance actions, and replacement-funded classes cannot earn another entitlement. Ask for only server-offered actions; do not guess eligibility.

An uncertain commit retry keeps the exact preview and operation key; a changed or stale batch needs a new approval.
