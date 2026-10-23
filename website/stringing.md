# Stringing · quick guide

**Administrator · Awaiting deployment**
[Open Stringing](https://tzhsports.vercel.app/admin/stringing) · [This week](../changelog/2026-10-19.md)

Open the step you need. Screenshots use fictional customers.

<details>
<summary><strong>1 · Add customer</strong></summary>

**Customers → Add customer → search member → select → Add contact.**
The customer must have a registered account.

![Search and select a registered customer](../images/stringing/quick-add-customer.jpg)

</details>

<details>
<summary><strong>2 · Add racket</strong></summary>

**View rackets → Add racket → model + optional nickname → Save.**
One record per physical racket, even for identical models.

![Add a physical racket](../images/stringing/quick-add-racket.jpg)

</details>

<details>
<summary><strong>3 · Add stringing</strong></summary>

**Racket Details → Start stringing → fill specifications/fees → Save.**
Pickup needs both date and time, or neither. Extra instructions go in **Notes**.
Only one active stringing per racket.

![String, tension, fees and optional pickup](../images/stringing/quick-add-stringing.jpg)

</details>

<details>
<summary><strong>4 · Change status</strong></summary>

**Details → status dropdown → choose → confirm.**

Received → In progress → Ready for pickup → Collected.
Status changes do not send WhatsApp or record payment.

![Status and Message beside the string specification](../images/stringing/quick-status.jpg)

</details>

<details>
<summary><strong>5 · Daily routine</strong></summary>

- **Timetable → Today:** work through pickups; “-” means unscheduled.
- Update status as work finishes; use **Messages** for customer updates.
- Check **Feedback** for replies and **Follow-ups** for due reminders.

<a id="record-full-payment"></a>

**Payment received?** Open racket Details → **Mark Paid** → review → confirm full
payment. Points/invoice follow; progress stays unchanged.

![Today's pickup list and available actions](../images/stringing/quick-daily-routine.jpg)

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

After **Collected**, the unique link is ready automatically.
**Feedback → Awaiting → Request feedback → Open WhatsApp → send → Mark as sent.**

![Request feedback from the Awaiting list](../images/stringing/quick-feedback-request.jpg)

The customer rates/comments without login, once per stringing.
Read replies in **Feedback → Received**.

![Read ratings and comments directly](../images/stringing/feedback-review-desktop.jpg)

</details>

<details>
<summary><strong>9 · WhatsApp reminder for the next stringing</strong></summary>

**Follow-ups → Manage racket reminder → Message → Open WhatsApp → send → Mark as sent.**
Or open **racket Details → … → Restring reminder**.

Default: **45 days after collection**. Change the interval or disable it in
**Settings**. Marking the reminder sent closes that pending follow-up.

![Next-stringing reminder and its settings](../images/stringing/quick-next-stringing.jpg)

</details>
