# Stringing · quick guide

**Administrator · Awaiting deployment**
[Open Stringing](https://tzhsports.vercel.app/admin/stringing) · [This week](../changelog/2026-10-19.md)

Open the step you need. Screenshots use fictional customers.

<details>
<summary><strong>Customer requests and same-day pickup</strong></summary>

**Customer ordering · Awaiting deployment.** Customers use the separate
[Stringing page](customer-stringing.md). In the toolbar, **Requested (count)**
opens requests needing review. Open job **Details → … → Edit stringing** to
confirm fees and pickup; **Requested → Received** separately asks for the actual
received date. Then use the normal service and payment steps below.

![Requested review queue and unquoted fees](../images/stringing/customer-requests-admin.jpg)

**Same-day pickup today** is visible on every tab. Switch On while open to allow
later-today customer pickup; switch Off at any time. It ends at closing, never
carries into tomorrow, and switching Off preserves accepted requests. Staff can
still arrange exceptions directly.

![Visible mobile same-day policy](../images/stringing/same-day-policy-mobile.jpg)

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

**Add stringing** at the top of the workspace. Search and select a registered
member, then type in **Racket name** and **String** to choose a previous name.
For a new name, choose **Add new racket** or **Add new string**; it becomes
available next time after you save the job. Enter
tension and fees, then **Save**. Pickup needs both date and time, or neither.
Both fee boxes start blank with a 0.00 hint. Enter the string fee; leave
Grommets blank for RM0.00.

![Matching fee fields](../images/stringing/matching-fee-inputs.png)

Extra instructions go in **Notes**. Repeat for each racket the customer brings;
identical names can have separate jobs. No separate racket setup is needed.

![Search previously used racket names](../images/stringing/racket-name-suggestions-desktop.png)

![Add a new string name](../images/stringing/new-string-name-desktop.png)

![Search or add names on mobile](../images/stringing/new-string-name-mobile.png)

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


<details>
<summary><strong>Automatic outreach pause and recovery · awaiting deployment</strong></summary>

In **Message**, tick **Pause automatic outreach for this customer** to pause all
their jobs. Manual messages remain available.

![Customer pause control](../images/stringing/outreach-pause-mobile.png)

In **Automatic outreach recovery**, check the original WhatsApp chat and stop the
runner before choosing **Resolve as observed sent** or **Resolve as definitely
not sent**. Tick the exact confirmation, then **Confirm resolution**. Expiry is
never proof that a message was unsent. No WhatsApp send occurs from this panel.

![Fictional desktop recovery card](../images/stringing/outreach-recovery-desktop-dark.png)

Follow the [stringing outreach guide](../mcp/stringing-outreach.md) for the dry run,
owner test and separate sending/scheduling authorisation.

</details>


Customer requests may leave string model and tension blank and show **Needs advice**.
Discuss the setup with the customer, then use **Details → Edit stringing** to save the agreed
string, tension and fees before starting work or recording payment. Awaiting deployment.

Stage, Payment and Feedback filters narrow the jobs shown inside each customer.
For example, **Stage → Requested** shows only requested jobs; **Reset filters**
restores all visits. **Total spent** remains the customer’s lifetime paid total. Awaiting deployment.

![Only jobs matching the selected stage](../images/stringing/customer-stage-filter.png)

**Same-day pickup** is a compact On/Off switch in the toolbar. Tap the info icon
for the daily reset details. **Requests** beside it opens requested jobs. Awaiting deployment.

![Compact same-day control and separate actions](../images/stringing/same-day-toolbar.png)

![Same-day control on mobile](../images/stringing/same-day-toolbar-mobile.png)

The Same-day pickup setting, Requests and Add stringing controls use matching heights. On phones, the setting sits above the two action buttons.

The Off switch has a contrasting track and border in light and dark themes.

![Same-day switch in light theme](../images/stringing/same-day-toolbar-light.png)

![Same-day switch in dark theme](../images/stringing/same-day-toolbar-dark.png)
