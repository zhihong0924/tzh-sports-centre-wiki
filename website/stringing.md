# Stringing jobs

[← Website guides](README.md)

**Role:** Administrator. **Availability:** Awaiting deployment; this preview covers contacts, rackets, jobs and full-payment recording.

After deployment, open [Admin → Stringing](https://tzhsports.vercel.app/admin/stringing).

1. Find an existing registered member and select **Add contact**. The stringing name/phone is separate from the member account; **Edit contact** changes only this contact.
2. Select **Add racket**, enter its model and an optional nickname such as “Blue grip”, then save. Add separate records for separate physical rackets, even when their models match.
3. Expand **Rackets and job history**, select **New job**, and enter the string, main/cross tension, stringing fee, optional grommet fee/notes and received date. Set both pickup date and time, or leave both empty.
4. Save. The job starts **Received / Unpaid**. Search by name, contact or string; expand history to find all open jobs. **Edit job** changes an unpaid, open job.
5. Select **In progress**, **Ready for pickup** or **Collected**, review the confirmation, and confirm. Progress moves forward only; collection records its time. **Cancel job** closes an unpaid, uncollected job after confirmation.

Contact/racket edits preserve earlier job details. If another administrator changed a record, refresh before trying again. Progress does not record payment, award points or issue an invoice.

Timetable, WhatsApp templates, per-racket reminders and private feedback links are not available in this preview. Existing Shop ordering remains available separately.

Fictional examples:

![Desktop stringing workspace](../images/stringing/workspace-desktop.jpg)

![Mobile unpaid job editor](../images/stringing/job-mobile.jpg)


## Record full payment

1. Find the racket job and select **Mark Paid**. Check the linked member, both fees, total and points. Choose the actual payment date (today or earlier, Malaysia time).
2. **Cancel** leaves the job unpaid. Select **Confirm payment received** only after the full amount has been received. Deposits and partial payments are not supported.
3. The job becomes **Paid**, earns the displayed points once, and shows its invoice link. The invoice also appears under **Stringing** in Admin Invoices and the member's My Invoices.
4. If the PDF could not be prepared, the job stays Paid and shows **Retry invoice**. Use that action; do not record another payment. Retrying does not award more points or resend the payment email.
5. Check the cards: distinct customers, received money this Malaysia month by payment date, and all unpaid fees excluding cancelled jobs. Changing the customer filter does not change these totals.

Paid fees cannot be edited or reversed, and paid jobs cannot be cancelled. Normal forward progress remains available, and an unpaid collected job can still be settled. Payment emails are best-effort; email failure never reverses a payment.

![Review full payment on mobile](../images/stringing/payment-confirmation-mobile.jpg)

![Paid job and received-money summaries](../images/stringing/payment-desktop.jpg)
