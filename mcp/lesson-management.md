# Change specific lesson durations or fees

[← MCP guides](README.md) · **Who:** Authorised administrators

**Try:**

> Use $tzh-lesson-management to find lessons from 18 to 19 October 2026. Show date, court, time, type, duration, RM fee and student names. Do not change anything.

1. Choose the intended concrete lessons from discovery; use court/time/roster to resolve ambiguity.
2. Ask for the desired duration and/or per-student fee, for example **“Preview changing the selected lesson to 150 minutes and RM60 per student.”** Confirm the retained/new fee for a custom duration.
3. Check every current/proposed duration, end time and RM fee, recurring context, downstream effect and preview expiry.
4. Explicitly approve the exact complete batch. Check the commit result and reload [Lesson Management](https://tzhsports.vercel.app/admin/lesson-fees).

**Expected:** Durations use 30-minute increments. Preview checks operating hours and conflicts. The batch saves all changes or none. Each edit affects the selected occurrence, including a recurring occurrence; it does not change its rule or siblings. Monthly-flat customization, creation, capacity and enrollment are outside this function. Use the website for series edits.

An uncertain retry keeps the same preview and operation key. Stale/expired previews need new review and approval.
