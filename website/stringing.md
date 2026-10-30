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
<summary><strong>1 · Add customer</strong></summary>

**Customers → Add customer → search member → select → Add contact.**
The customer must have a registered account.

![Search and select a registered customer](../images/stringing/quick-add-customer.jpg)

</details>

<details>
<summary><strong>2 · Add stringing</strong></summary>

**Customers → View stringing → Add stringing.** Enter the **Racket name**, string,
tension and fees, then **Save**. Pickup needs both date and time, or neither.
Extra instructions go in **Notes**. Repeat for each racket the customer brings;
identical names can have separate jobs. No separate racket setup is needed.

![Add a stringing job with its racket name](../images/stringing/job-first-add-stringing.png)

![The same job form on mobile](../images/stringing/job-first-add-stringing-mobile.png)

</details>

<details>
<summary><strong>3 · See all jobs under a customer</strong></summary>

**Customers → View stringing.** Each racket visit has its own row, including
completed jobs. Check string/tension, separate fees, payment, received date,
and status. The **Feedback** column shows **No feedback** or **Received**; click
**Received** to read that visit’s response. **Message** and **Details** have
separate columns. Use **View feedback** on the customer header to read all their
responses, with racket details and service dates. Use **Message** on a row to prepare a message
for that job; opening the composer does not send it. Open **Details** for that specific job; **Edit stringing**
can correct its racket name while it is unpaid and open.

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

Scroll below the daily list. **Click a date** for its agenda; red shows overdue work.
Completed pickups stay visible. On desktop, **drag an unpaid open item → review →
Save** to reschedule; on mobile, use the daily **Edit** action.

![Monthly overview with overdue and completed pickups](../images/stringing/quick-calendar.jpg)

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

**Follow-ups → Manage job reminder → Message → Open WhatsApp → send → Mark as sent.**
Or open **job Details → … → Restring reminder**.

Default: **45 days after collection**. Change the interval or disable it in
**Settings**. Each job has its own reminder; a newer job does not replace it.
Marking the reminder sent closes only that job’s follow-up.

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
