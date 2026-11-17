# Remind students about today's class

**Role:** Administrator with **Lesson management** MCP permission.
**Availability:** Awaiting deployment and supervised WhatsApp setup.

First [save the message template](../website/lesson-reminders.md). Agree with the
owner on the daily run time, message language and approved WhatsApp session.

Try discovery first:

> Use $tzh-lesson-reminders to list today's class reminders. Do not send anything.

After the owner completes a supervised send and activates the schedule, Codex
finds eligible students, prepares the latest saved message, verifies the WhatsApp
chat and prefilled text, sends, then records the observed outgoing message.

- Each daily run sends reminders for all eligible unsent classes today, even
  evening classes when the schedule runs in the morning. It does not wait until
  each class is nearly starting. Multiple classes for one student get separate
  reminders.
- Today means Malaysia time. Cancelled classes, recorded absences, classes already
  started and invalid contacts are skipped.
- Students use their account phone; guests use their recorded enrollment phone.
- Each student/class enrollment gets one reminder. Changing the template or
  language does not resend one already recorded as sent.
- Opening WhatsApp alone does not send or mark anything sent.
- Use one sender at a time. A run processes at most 20 messages; additional
  students are reported as deferred. A lost acknowledgement can cause a duplicate.

Missing tools, sign-in or a mismatched chat/draft stops the flow for attention.
This workflow reminds students to attend class; it does not collect lesson fees.

For guided schedule creation, copy the [lesson scheduler setup prompt](https://github.com/zhihong0924/tzh-sports-centre-mcp/blob/main/prompts/setup-lesson-reminder-scheduler.md)
into your updated Codex workspace after deployment. Codex asks for run time,
language and WhatsApp session before activation. Keep your computer and the
signed-in session available for scheduled runs.
