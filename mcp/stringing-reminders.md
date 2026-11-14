# Stringing reminders with Codex

**Administrator · Local preview; awaiting deployment and a supervised WhatsApp test.**
[Open Stringing](https://tzhsports.vercel.app/admin/stringing)

<details>
<summary><strong>Choose waiting periods in your scheduler prompt</strong></summary>

Include your timing when setting up the Codex schedule, for example:

> Use $tzh-stringing-reminders. Send the first payment reminder two days after
> receipt, and the second reminder four days after the first recorded send.

These are examples; choose your own whole-day waiting periods. Timing stays in
that schedule's prompt. There are no website reminder-policy settings to save.
To disable a stage, leave it out of the schedule. If timing is missing, Codex asks
before processing that payment stage. Changing one schedule does not change others.

</details>

<details>
<summary><strong>Preview the next messages</strong></summary>

> Use $tzh-stringing-reminders. Show a dry-run count for payment reminders, ready
> rackets, feedback requests and due restring reminders. Do not send anything.

Payment reminders stop after payment. Pickup notices apply to Ready rackets.
Feedback is requested once, three days after collection, while unanswered.
Restring follows each job's saved reminder date. The assistant reports any
skipped work and incomplete scans.

</details>

<details>
<summary><strong>Set up scheduled WhatsApp sending</strong></summary>

After the release, use an owner-controlled test recipient first. Choose WhatsApp
Web with connected browser access, or the installed desktop app with computer
access, and sign in. Agree on recipients, message stages/templates, Malaysia
contact hours and the per-run limit. Keep the computer and session available.
Have TZH verify the test send and dashboard result before activating the schedule.

The MCP functions prepare the message/link and track the outcome. Codex uses the
approved WhatsApp application to send. Opening a link does not send a message.
Messages use the saved EN/ZH/MS preference. Already marked-sent stages are skipped. Use one sender and one job per customer
per run. If sending succeeds but recording is lost, a later run may send again.

Existing tokens inherit Stringing reminders permission when the release migration
runs; no replacement token is needed. Expired/revoked tokens remain invalid. New
tokens select **Stringing reminders** in MCP Access Tokens.

![Stringing reminders permission](../images/stringing/reminders-permission-desktop.jpg)

</details>

<details>
<summary><strong>Check sent status</strong></summary>

Codex records successful sends using the same **Mark as sent** status in the job's
**Message** dialog. Already marked-sent reminders are skipped. There is no separate
recovery panel. If a message was not sent, its status stays unchanged for a later
run. Check WhatsApp if the outcome is unclear: a send followed by a lost status
update may cause a duplicate.

![Existing message and sent status](../images/stringing/reminders-sent-status-desktop.jpg)

![Existing message controls on mobile](../images/stringing/reminders-sent-status-mobile.jpg)

</details>
