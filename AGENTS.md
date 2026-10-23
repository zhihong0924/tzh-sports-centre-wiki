# Client wiki

Keep README.md brief, with a Weekly changes table linking Monday–Sunday changelog pages, newest week first. Keep inline feature lists out of README.md and changelog/README.md; list details in each weekly page. Use overview.md as the role/task map. Maintain current website/ and mcp/ guides separately from dated guides linked by changelog/README.md. Preserve dated guide URLs. Keep each task guide brief: required role, actual page link, clicks/inputs, expected results and important approval/payment effects. Save real application screenshots under images/ using fictional demo data; never commit credentials, real contact details, receipts or private customer records. Label rollout limitations accurately and do not invent client screens or MCP capabilities. Keep developer implementation notes in the application repository and customer MCP setup/skills in tzh-sports-centre-mcp.

Client-facing pages describe features and usage only. Omit writing-process notes, coverage commentary, task requirements, and statements about periods with no changes.

## Website guide style

Use [website/stringing.md](website/stringing.md) as the style reference. Write for a capable client who wants to complete a task, not learn the implementation.

- Organize by practical use case: add a customer, record payment, check today's work, send a reminder. Use the actual button names.
- Lead with the required role, a direct website link and a short availability note when awaiting deployment.
- Prefer a short click path or a few brief steps, followed by a current screenshot showing the relevant controls. Include only the inputs and expected result needed to complete that task.
- Let screenshots carry the explanation. Avoid long paragraphs, exhaustive field descriptions, repeated instructions and feature inventories. Use fictional data and exclude credentials, including private feedback-link tokens.
- For a guide covering several tasks, use numbered, collapsed `<details>` sections with clear `<summary>` titles so the client opens only the task they need. Keep a single-task guide simple; do not add disclosures unnecessarily.
- Use a small table only when it makes a choice clearer, such as which WhatsApp stage to select. Distinguish manual sending from automatic behavior.
- Keep essential consequences beside the action: confirming payment records money, deleting does not refund, and opening WhatsApp does not send. Omit unrelated caveats and technical details.
- Replace stale text/screenshots when the UI changes rather than appending another explanation of the same workflow. Keep weekly changelogs as short links to these guides.

Apply this style by default to new and revised website guides. MCP guides should likewise focus on user tasks, using short command examples where screenshots are not useful. Implementation, schema, security and operational details belong in the application repository.

Use `https://tzhsports.vercel.app/` for client website links; never use localhost URLs in published guides.

Weekly changelog pages are a single list with one update per bullet. Each bullet links to its relevant step-by-step guide or guide section. Keep screenshots and walkthroughs in those guides, not as standalone images or walkthrough links on the weekly page.
