# Stringing

[← Website guides](README.md)

**Role:** Administrator. **Availability:** Awaiting production database update and
deployment. After release, open [Admin → Stringing](https://tzhsports.vercel.app/admin/stringing).

## Default view

Stringing opens on **Timetable**, with the selected day's pickup agenda above the
month calendar. The other tabs are **Customers**, **Feedback** and **Follow-ups**.
Customers and Follow-ups open directly into their records without summary cards.
The customer count appears below the customer table and follows its filters.

![Customer records with the count in the footer](../images/stringing/customer-count-only.jpg)

## Add a customer and racket

1. In **Customers**, select **Add customer**. Type at least two characters of a
   registered member's name, email or phone, choose the result, then **Add contact**.
2. Select their name or **View rackets**, then **Add racket**. Enter the model and
   optional nickname, such as “Blue grip”. Save separate records for separate
   physical rackets, even when their models match.
3. Select the racket name or **Details** to open its window. Empty rackets offer
   **Start stringing**; existing active work appears immediately. Completed or
   cancelled services stay under collapsed **Stringing history**.

Customer name, phone and email come from the member account and cannot be edited
here. Account updates appear automatically. Racket changes preserve earlier service
details. The list shows the latest service; search and Payment/Feedback/Stage
filters can match older services. **Follow up** finds pending racket reminders due
today or overdue in Malaysia time. **Work queue** counts physical rackets needing
stringing or ready for pickup. Collected/cancelled services add no open work.

## Start or edit stringing

1. In the racket window, select **Start stringing**. Only one service can be active
   on a racket; collect or cancel it before starting another.
2. Enter the string, **Tension (lbs)**, string fee and grommet fee. Set both pickup
   date/time, or leave both empty for unscheduled work.
3. Expand **Notes & received date** if needed. The received date defaults to today.
   Use the single Notes field for all instructions, including main/cross tension
   requests and grommet instructions.
4. Select **Save**. The service starts Received/Unpaid. Use the header **… → Edit
   stringing** for an unpaid, open service. Cancel discards edits.
5. Choose the status beside the specification to advance to In progress, Ready for
   pickup or Collected. Review and confirm; Cancel keeps the current status.

Progress moves forward only and does not record payment. Collection automatically
creates the service's private feedback link and starts its racket reminder.
Paid services can advance but cannot be edited/cancelled. If another administrator
changed a record, refresh before trying again.

The racket window keeps **Message** beside status, payment controls beside total
fees, and secondary actions in the header ellipsis. **Restring reminder** is for
future restringing, separate from messages about this service.

## Delete a stringing service

1. Open **Details → … → Delete stringing**. No status change is needed, including
   for paid, collected or previously contacted services. For history, use that
   service's Actions menu.
2. Check the racket, string, tension, received date and total. Select **Cancel**
   to keep it, or **Delete stringing** to confirm.
3. It disappears from the workspace, calendar and follow-ups. The member/racket
   remain, and another service can start. Existing payments, points, invoices and
   linked history are kept. Deletion does not issue a refund.

## Remove an unused racket

Open **Details → … → Delete racket**, review its model/nickname, then confirm.
Cancel keeps it. Rackets with any retained service history cannot be removed,
including history belonging to deleted services.

## Record full payment

1. Open the racket's **Details** and select **Mark Paid** beside total fees (or on
   its unpaid collected service in history).
2. Review member, separate fees, total and points. Choose the actual payment date,
   Malaysia today or earlier. **Cancel** leaves the service unpaid.
3. Select **Confirm payment received** only after receiving the full amount.
   Deposits/partial payments are not supported. Payment earns member points and
   makes the service Paid; it does not change stringing progress.
4. Use the linked invoice when available. If its PDF could not be prepared, choose
   **Retry invoice**; do not record another payment. Recovery does not repeat points
   or resend the payment email.

Paid fees cannot be edited/reversed and paid services cannot be cancelled.
An unpaid collected service can still be settled. Source-linked stringing invoices
use Retry invoice rather than manual invoice editing or PDF regeneration.

## Plan pickup deadlines

1. In **Timetable**, use the date arrows, Today, or the date field and **Go to date**.
   The list shows that date's services, earliest pickup first, then open unscheduled
   services with “-”. Dated completed/cancelled services remain visible.
2. Browse the **Month calendar** below. Selecting a day opens its agenda above.
   Month arrows browse independently of the selected daily list. The calendar
   includes completed work; no completed-jobs toggle is needed.
3. Select **Edit** on eligible unpaid/open work to set or clear both pickup fields.
   On desktop, drag an eligible calendar entry to another date, review the proposed
   date/time and save. **Cancel** keeps the original pickup. Mobile uses daily Edit.
4. Select Refresh to reload the agenda/calendar.

Month pickups refers to the displayed month; Today/Next 7 days use Malaysia today.
Red overdue work means Received/In progress work past its pickup time; Ready work
is awaiting collection. Unscheduled work is never overdue. Scheduling does not
record money, collection or contact.

## Prepare WhatsApp messages and follow-ups

1. Open the service's **Message** button beside status, or **Messages** in the agenda.
   Collected history offers **Request feedback** / **View feedback** directly.
2. Choose the message Stage and Language (English, 中文 or Bahasa Melayu). Language
   is remembered for this customer across rackets/services. Review/edit the preview.
3. **Copy message** copies the draft; **Open WhatsApp** prepares it for you to send.
   Neither sends automatically or records contact. A missing/invalid account phone
   disables WhatsApp but still allows Copy. Resolve missing preview details first.
4. After sending yourself, select **Mark as sent**. Its label applies to this stage
   and retains the first manually recorded account/time. You may resend a stage
   already marked sent. It is not proof of delivery.
5. Shared-template editing and feedback/link controls are collapsed below the
   preview. Editing the draft does not change the shared template.

For the next restring reminder, use the racket header **… → Restring reminder** or
**Follow-ups → Manage racket reminder**. Its Settings control the interval (45 days
by default) or disable reminders. Collection starts the interval; changing settings
recalculates pending reminders from collection, not from today. Message prepares
that reminder. Recording its contact completion closes the pending follow-up.
Another collection supersedes older pending reminders on the same physical racket.
Completed contacts stay closed; future collections use the saved setting.

## Request and review private feedback

1. Mark the service **Collected**. Its unique feedback link is created automatically
   for that stringing service, identifying its racket and customer.
2. Open **Feedback → Awaiting → Request feedback**, or the collected service's
   Request feedback action. The preview already includes its link. Reopening reuses
   the same link. Copy/open WhatsApp and send it yourself.
3. The customer opens the private link without logging in, chooses a language,
   rates string feel, tension and service from 1–5, optionally comments and submits.
   It can be reopened before submitting; afterward it shows confirmation and
   cannot accept or edit another response. Respondent identity is not verified.
4. Open **Feedback → Received** for ratings, full comments, racket/string and
   submission time directly in the list. Search customer, racket or string and
   Refresh for new responses. History's **View feedback** is also available.
5. Only if access must stop, expand **Feedback & link options**, confirm
   **Deactivate this feedback link**, then **Revoke link**. Revocation preserves
   the response, disables the link and cannot be undone here. There is no manual
   create/replacement step. Links do not expire automatically.

Opening/copying does not count as feedback received or a sent message. Feedback
changes no payment, points, invoices or progress. Deleting the service disables
its old link without losing retained linked history.

![Feedback review with fictional demo data](../images/stringing/feedback-review-mobile.jpg)
