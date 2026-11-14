# MCP function reference

[← MCP guides](README.md)

You can ask in ordinary language; the assistant chooses the function. Functions in the main table are deployed; the stringing preview section below is awaiting deployment. Each function requires its listed permission and an active administrator.

| Permission | Function | What it does | Effect |
|---|---|---|---|
| Student account | `search_student_accounts` | Find active students; choose the matching account. | Read |
| Student account | `list_student_audit_cases` | Find a confirmed student’s open cases by name/date/status. | Read |
| Student account | `create_student_audit_case` | Create a named working case for a year/date range. | Draft write |
| Student account | `upload_student_audit_proof_image` | Attach a private proof image to a draft case. | Draft write |
| Student account | `add_student_audit_entry` | Add historical lessons, payments or signed corrections. | Draft write |
| Student account | `remove_student_audit_entry` | Remove a confirmed draft entry and unused proof. | Confirmed draft removal |
| Student account | `delete_student_audit_case` | Permanently delete a draft/rejected case and owned proof. | Confirmed deletion |
| Student account | `review_student_audit_case` | Validate and show account effects with the exact version. | Draft validation; no official change |
| Student account | `commit_student_audit_case` | Apply the explicitly approved reviewed version. | Confirmed official write |
| Member points | `search_point_members` | Find active members for a point award. | Read |
| Member points | `list_active_point_policies` | List available award policies. | Read |
| Member points | `preview_points_assignment` | Show every recipient, contribution and award total. | Preview |
| Member points | `commit_points_assignment` | Apply the exact approved positive-point award. | Confirmed write |
| Read admin attention | `query_admin_attention` | List overdue, due-in-window and undated admin work. | Read |
| Lesson management | `find_manageable_lessons` | Find concrete lessons with schedule, fee and minimal roster. | Read |
| Lesson management | `preview_lesson_management_batch` | Check the full occurrence duration/price batch. | Preview |
| Lesson management | `commit_lesson_management_batch` | Apply the exact approved occurrence changes atomically. | Confirmed write |
| Lesson management | `query_lesson_attendance` | Read recorded/missing/not-due attendance and summaries. | Read |
| Lesson management | `preview_lesson_attendance_updates` | Show attendance and replacement/cancellation effects. | Preview |
| Lesson management | `commit_lesson_attendance_updates` | Record the exact approved attendance batch atomically. | Confirmed write |
| Manual invoices | `search_invoice_members` | Find registered invoice owners. | Read |
| Manual invoices | `preview_manual_invoice` | Show an already-paid member/non-member invoice proposal. | Preview |
| Manual invoices | `commit_manual_invoice` | Create the approved invoice and applicable member points. | Confirmed write |
| Manual invoices · compatibility | `preview_non_member_invoice` | Show a legacy non-member-only proposal. | Preview |
| Manual invoices · compatibility | `commit_non_member_invoice` | Create the approved legacy non-member invoice. | Confirmed write |

Read/preview does not finalize business changes. Draft tools save working audit data; validation records the reviewed version without changing the official account. Destructive actions and commits require explicit approval of the displayed target or exact full preview. Never approve a different batch after a timeout under an earlier approval.

Use the matching [task guide](README.md) for steps and examples. For connection/discovery problems, follow the [customer setup and troubleshooting guide](https://github.com/zhihong0924/tzh-sports-centre-mcp/blob/main/SETUP.md). Credentials are supplied separately through a secure channel.


## Stringing reminders — awaiting deployment

All require an active administrator and **Stringing reminders**. Existing tokens
inherit this permission on release; invalid tokens remain invalid. Sending still
requires approved WhatsApp computer/browser access. See [the guide](stringing-outreach.md).

| Function | What it does |
|---|---|
| `get_stringing_outreach_policy` | Read the saved payment reminder delays. |
| `update_stringing_outreach_policy` | Save confirmed first/second waiting periods or disable them. |
| `list_stringing_outreach` | Find outstanding payment, pickup, feedback and restring messages. |
| `create_stringing_outreach_feedback_request` | Create a missing due job feedback request once. |
| `prepare_stringing_outreach` | Prepare the exact private message and WhatsApp link. |
| `finish_stringing_outreach` | Mark the existing job/stage sent after observing the outgoing message. |

MCP does not send the WhatsApp message. Opening a link does not prove it was sent.
