# Manual invoice assistant · Rollout pending verification

[← MCP guides](README.md) · **Who:** Authorised administrators

The shared member/non-member workflow is prepared in the application and customer workspace. Deployment and connected-client verification are still recorded as pending. Until the owner confirms it is available, use [website manual invoices](../website/admin-invoices.md); do not install staged invoice instructions against an older server.

**Once the owner confirms availability, try:**

> Prepare an already-paid invoice for non-member Demo Customer, dated 13 October 2026, for stringing RM50. Show the complete preview; do not create it.

For a registered customer, the assistant first searches and confirms the account. Review the customer type, primary/extra printed names, date, every multiline item and RM amount, total, payment-received state, member points, notification recipient and expiry. Only then explicitly approve the exact preview.

**Expected after rollout:** The invoice is created once. Members earn one point per complete RM and may receive an invoice email; non-members have no account owner, points or email. Additional names are display-only. Check the returned email status; a failed email does not undo the invoice and must not cause another invoice to be created.

The old non-member functions remain for compatibility and cannot select members. Unpaid charges and invoice correction are website workflows. Unknown/expired uncommitted previews need fresh review; uncertain committed results must retry the same approved operation.
