# Stringing · quick guide

**Administrator**
[Open Stringing](https://tzhsports.vercel.app/admin/stringing) · [This week](../changelog/2026-10-19.md)

Open the step you need. Screenshots use fictional customers. Catalogue autofill, quantity pricing and pickup slots are awaiting deployment.

For a complete example, follow [one customer visit from request through collection, feedback and follow-up](stringing-complete-visit.md).

<details>
<summary><strong>Customer requests and same-day pickup</strong></summary>

**Incoming rackets.** Open **Requests**, find the customer and racket, then choose **Receive racket**. Check the actual received date, string fee and grommet fee. A matching catalogue string supplies a suggested price. Check the racket to determine the quantity. Choose **Grommet type** and enter **Grommet quantity** to fill the fee. Standard costs RM1 per four and high-quality costs RM1 per two. Partial packs round up. You can enter the actual fee directly. Confirm with **Receive racket**. The job leaves Requests and appears under Received in Customers. Payment is still outstanding.

**Same-day pickup today** is visible on every tab. Switch On while open to allow
later-today customer pickup; switch Off at any time. It ends at closing, never
carries into tomorrow, and switching Off preserves accepted requests.

![Visible mobile same-day policy](../images/stringing/same-day-policy-mobile.jpg)

</details>

<details>
<summary><strong>Publish pickup availability</strong></summary>

**Admin → Stringing → Pickup availability.** Set the start date, number of days, weekdays and hours. Use **7** days for one week or **14** for two, then select **Publish slots**. Check the grid and use **Next week** to see later dates. Staff and members can choose from the same 30-minute slots. Enter the range and select **Close slots** to stop new reservations in it. Existing pickups stay on the timetable.

![Publishing two weeks of pickup slots](../images/stringing/pickup-availability-grid.jpg)

</details>

<details>
<summary><strong>1 · Choose a customer</strong></summary>

**Add stringing → search member → select.** Search by name, email or phone.
The customer must have a registered account. Continue with the racket details in
the same form; selecting a member or cancelling does not create a record.
A red customer field means no account matched or a search result still needs
to be selected. Correct the search and choose a result to enable Save.

![Customer selection error](../images/stringing/invalid-customer-desktop.png)

![Search and select a registered customer](../images/stringing/direct-stringing-member-picker.png)

</details>

<details>
<summary><strong>2 · Add stringing</strong></summary>

**Add stringing → select a member → enter the racket name and tension.** Choose a model and colour from **String**. The catalogue price fills **String fee (RM)** and can be adjusted. Choose **Grommet type** and enter the number of grommets used to calculate the grommet fee.

Open **Pickup schedule (optional)** to enter a date only, or choose **Show pickup slots** and select a 30-minute slot. Leave the date blank to save as **Unscheduled**. Select **Save**.

![Staff fee fields and date-only pickup](../images/stringing/staff-price-and-pickup-edit.jpg)

</details>

<details>
<summary><strong>3 · See all jobs under a customer</strong></summary>

**Customers → View stringing.** Each racket visit has its own row, including
completed jobs. **Total spent** at the right above the job rows adds all confirmed
stringing and grommet payments, including paid jobs removed from the list. Unpaid
jobs are excluded. Check string/tension, separate fees, payment, received date,
and status. The **Feedback** column shows **No feedback** or an underlined **View feedback**
action to read that visit’s response. **Message** and **Details** have
separate columns. Use **View feedback** on the customer header to read all their
responses, with racket details and service dates. Use **Message** on a row to prepare a message
for that job; opening the composer does not send it. Open **Details** for that specific job; **Edit stringing**
can correct its racket name while it is unpaid and open.
**Edit stringing** opens pickup automatically when a date is saved. Use **Show pickup slots** to choose a replacement, **Clear pickup time** to keep the date, or clear the date to remove pickup timing.

**Set or change timing later:** open **Details → … → Edit dates**, update the date or select a slot and **Save**. Paid open jobs can be rescheduled here. For a collected or cancelled job, keep the original time or make a date-only correction. A blank received date keeps the recorded date.

For paid or completed jobs, use **Details → … → Edit**, enter the
correct racket/string names and a reason, then **Save correction**. The change
is audited; payment amounts and issued invoices stay unchanged. A typo stops
appearing in suggestions once no other job uses it.

![Correct names on a paid or completed job](../images/stringing/correct-job-names-desktop.png)

![Name correction on mobile](../images/stringing/correct-job-names-mobile.png)

![Each stringing visit listed directly under its customer](../images/stringing/job-feedback-customer-jobs-desktop.png)

![Stringing jobs on mobile](../images/stringing/job-feedback-customer-jobs-mobile.png)

![Read the feedback for one job](../images/stringing/job-feedback-response-desktop.png)

</details>

<details>
<summary><strong>4 · Change status</strong></summary>

**Details → status dropdown → choose → confirm.**

Received → In progress → Ready for pickup → Collected.
Status changes do not send WhatsApp or record payment.

![Job details with status and payment controls](../images/stringing/job-first-details.png)

</details>

<details>
<summary><strong>5 · Daily routine</strong></summary>

- **Timetable → Today:** work through pickups; “-” means unscheduled.
- Use **Mark Paid** for unpaid jobs; paid jobs show their invoice link.
- Update status as work finishes; use **Messages** for customer updates.
- Check **Feedback** for replies and **Follow-ups** for due reminders.

<a id="record-full-payment"></a>

**Reset filters** clears the customer search and all three filters. Paid invoice
links show the reference only, such as **TZH-0060**.
Invoice links align with **Mark Paid** in the Payment column.

**Payment received?** In the timetable Payment column, choose **Mark Paid** →
review the fees and payment date → confirm full payment. The same button is on
mobile job cards and in job Details. Confirming records money received and awards
points; a brief confirmation appears and the row shows its invoice link. Progress
stays unchanged. Cancel records nothing. If the invoice is unavailable, use
**Retry invoice**.

![Mark Paid in the timetable Payment column](../images/stringing/timetable-mark-paid-desktop.png)

![Mark Paid on a mobile job card](../images/stringing/timetable-mark-paid-mobile.png)

![Paid jobs show the invoice link](../images/stringing/timetable-paid-invoice-desktop.png)

</details>

<details>
<summary><strong>6 · Calendar</strong></summary>

Choose a date in the daily date box to update the schedule immediately, or use
the arrows / **Today**.
The daily date controls appear together; the month grid below provides an overview.
**Monthly collected** counts jobs actually collected in the displayed month, using
Malaysia time. Today and Next 7 days show scheduled pickups.

![Monthly collected summary](../images/stringing/monthly-collected-desktop.png)

![Monthly collected on mobile](../images/stringing/monthly-collected-mobile.png)
Scroll below the daily list. **Click a date or any job inside it** to select that
day and return to its table; red shows overdue work. Use the table’s **Edit**
button to edit a job.
Completed pickups stay visible. On desktop, **drag an unpaid open item → review →
Save** to reschedule; on mobile, use the daily **Edit** action.

![Monthly overview with overdue and completed pickups](../images/stringing/quick-calendar.jpg)

![Single daily date toolbar](../images/stringing/timetable-date-toolbar.png)

![Calendar job selection returns to that day's table](../images/stringing/calendar-open-day.png)

</details>

<details>
<summary><strong>7 · WhatsApp updates, stage by stage</strong></summary>

**Details → Message → Stage:**

| When | Choose |
| --- | --- |
| Received / in progress, payment pending | First payment reminder |
| Still unpaid, another reminder needed | Second payment reminder |
| Payment recorded | Paid confirmation |
| Racket ready | Ready for pickup |

Choose language → review preview → **Open WhatsApp → send → Mark as sent**.
Language is remembered per customer. Sent stages can be resent.

![Choose message stage, language and preview](../images/stringing/quick-whatsapp-stage.jpg)

WhatsApp needs a valid account phone; **Copy message** also works without one.

</details>

<details>
<summary><strong>8 · WhatsApp feedback request</strong></summary>

For a collected job: **Message → Stage: Feedback request → Prepare feedback link**.
Expand **Prepare feedback message**, review it, then copy or open WhatsApp.
After sending, use **Mark as sent**. Opening the composer does not send anything.

Each job accepts one response. Retrying uses the same link; an old response cannot
make a later job look reviewed. Racket name remains part of the job.

**View feedback** on the customer header opens all responses, newest first, with
racket/string/tension and service dates. This window is for reading only; it has
no invitation creation or link-management actions. Earlier responses whose job
was not recorded remain labelled as earlier feedback.

![All feedback from one customer](../images/stringing/job-feedback-history-desktop.png)

![Feedback history on mobile](../images/stringing/job-feedback-history-mobile.png)

**Feedback → Received** also lists responses. **Awaiting → Message** opens the
specific job's composer. Removing a job retains its response in admin history.

</details>

<details>
<summary><strong>9 · WhatsApp reminder for the next stringing</strong></summary>

**Follow-ups → Send reminder → Message → Open WhatsApp → send → Mark as sent.**
Or open **job Details → … → Restring reminder**.

Default: **45 days after collection**. Change the interval or disable it in
**Settings**. Each job has its own reminder; a newer job does not replace it.
Marking the reminder sent closes only that job’s follow-up.

Disabled reminders show **Reminder settings** so you can enable them again.

Filter by **Due** (today or overdue), **Upcoming** (future reminders),
**Contact done** (manually marked as sent), or **Disabled** (switched off).
Opening WhatsApp alone does not mark contact done.

![Stringing follow-up filters](../images/stringing/follow-up-filters.png)

![Reminder settings for one stringing job](../images/stringing/job-first-reminder.png)

</details>





Customer requests may leave string model and tension blank and show **Needs advice**.
Discuss the setup with the customer, then use **Details → Edit stringing** to save the agreed
string, tension and fees before starting work or recording payment.

Stage, Payment and Feedback filters narrow the jobs shown inside each customer.
For example, **Stage → Requested** shows only requested jobs; **Reset filters**
restores all visits. **Total spent** remains the customer’s lifetime paid total.

![Only jobs matching the selected stage](../images/stringing/customer-stage-filter.png)

**Same-day pickup** is a compact On/Off switch in the toolbar. Tap the info icon
for the daily reset details. **Requests** beside it opens requested jobs.

![Compact same-day control and separate actions](../images/stringing/same-day-toolbar.png)

![Same-day control on mobile](../images/stringing/same-day-toolbar-mobile.png)

The Same-day pickup setting, Requests and Add stringing controls use matching heights. On phones, the setting sits above the two action buttons.

The Off switch has a contrasting track and border in light and dark themes.

![Same-day switch in light theme](../images/stringing/same-day-toolbar-light.png)

![Same-day switch in dark theme](../images/stringing/same-day-toolbar-dark.png)

<details>
<summary>Open stringing work from Admin actions</summary>

**Role: Admin.** Open the bell in the navbar, then choose:

- **New stringing requests** to review incoming jobs.
- **Stringing work due / overdue** for jobs still to string with pickup today or earlier.
- **Unsent stringing feedback** to prepare a collected job’s feedback request with **Message**.
- **Stringing follow-ups due / overdue** to open **Follow-ups → Due**.

Resolve the work in the linked screen and the bell count updates on refresh.
After sending in WhatsApp, click **Mark as sent**. A reminder then shows **Contact done**. Opening
WhatsApp alone does not mark a message sent. Feedback already sent and waiting
for the customer does not appear as unsent.

![Stringing queues in Admin actions](../images/stringing/admin-actions.png)

![Admin actions on mobile](../images/stringing/admin-actions-mobile.png)

</details>

<details>
<summary><strong>Manage string models, colours and prices</strong></summary>

**Admin → Stringing → Strings & prices.** View each string’s photo, model, colour
and price together. Missing photos show **Image unavailable**. Previous shop
stringing choices are now in this catalogue.
Create service choices here; create merchandise listings in Shop. Past shop
orders remain in their order history.

1. Choose **Add string**.
2. Enter **String model & colour**, for example **Yonex BG80 (White)**, and
   **Price (RM)**. Use a separate entry for each colour.
3. Choose a **Catalogue photo** (up to 4 MB) to show it in the customer photo picker. Use the same field in **Edit** to replace it.
4. Leave **Available to customers** checked and choose **Save**.

![Manage the string catalogue](../images/stringing/admin-catalog-desktop.png)

Use **Edit** to change the name or price. Uncheck **Available to customers** and
save to hide a choice; check it again to make it available. Customers see updates
when they refresh their request form. Saved jobs and invoices keep their recorded
details. Staff still confirms the final fee and any grommet charges after inspection.

![Edit or hide a string on mobile](../images/stringing/admin-catalog-photo-editor.png)

![String catalogue on mobile](../images/stringing/admin-catalog-mobile.png)

</details>


<details>
<summary><strong>Check Codex reminder sent status</strong></summary>

**Local preview; awaiting deployment and supervised WhatsApp setup.**
Codex uses the existing **Mark as sent** status in **Message**. It skips messages
already marked sent. If a send was not recorded, a later run can retry; check
WhatsApp when unsure because this may produce a duplicate. There is no separate
recovery panel. Run one sender at a time.

![Existing message and sent status](../images/stringing/reminders-sent-status-desktop.jpg)

See [Stringing reminders with Codex](../mcp/stringing-reminders.md) to put waiting periods in the scheduler prompt and arrange supervised setup.

</details>
