# Manual invoice assistant

[← MCP guides](README.md) · **Who:** Authorised administrators

Create already-paid invoices for registered members or non-members through the connected assistant.

**Try:**

> Prepare an already-paid invoice for non-member Demo Customer, dated 13 October 2026, for stringing RM50. Show the complete preview; do not create it.

For a registered customer, the assistant first searches and confirms the account. Review the customer type, primary/extra printed names, date, every multiline item and RM amount, total, payment-received state, member points, notification recipient and expiry. Only then explicitly approve the exact preview.

**Expected:** The invoice is created once. Members earn one point per complete RM and may receive an invoice email; non-members have no account owner, points or email. Additional names are display-only. Check the returned email status; a failed email does not undo the invoice and must not cause another invoice to be created.

The old non-member functions remain for compatibility and cannot select members. Unpaid charges and invoice correction are website workflows. Unknown/expired uncommitted previews need fresh review; uncertain committed results must retry the same approved operation.
