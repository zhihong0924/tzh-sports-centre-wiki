# Court operations

[← Overview](../overview.md) · **Who:** Administrators

1. Open [Schedule → Bookings](https://tzhsports.vercel.app/admin/schedule?tab=bookings), pick a date and inspect the timetable. Create a one-off booking through its booking-creation control; check the member/guest, court, sport and time before saving. Admin-created settled bookings record payment already received.
2. In **Court Booking Reviews**, review pending receipts. Check the detail/receipt and displayed points before confirming approval or rejection.
3. Use **Approved**, **Rejected / Cancelled** and their booking-month filters to find records. For an agreed test booking, open **Details → Edit → Cancel Booking** and review the Yes/No confirmation. Cancellation releases slots, reverses awarded points up to the available balance and records no refund.
4. In recurring bookings, create a rule with its dates, recurrence, court, time and payment requirement. Expand a member for rule actions and **Occurrences**.
5. Click a recurring timetable block to change time; choose **This occurrence**, **This and upcoming occurrences**, or **All occurrences**. Select the cancellation scope carefully too. Record a refund as completed only when it has actually been made.
6. Use renewal/deactivation or selected bulk actions as needed. Renewals create a new unpaid cycle. **Assign User** links the latest active guest cycle to a chosen account; it does not transfer older history or backfill points.

**Expected:** Conflicts and operating-hours checks can prevent saving. Deactivation stops the rule; cancelling one occurrence affects the selected date/scope. Review scope and payment state before confirming.

**Closing-time selection (awaiting deployment):** Check the schedule's
**Operating** line before creating a booking. An 11:00 PM close allows
11:00 PM as the end time, but excludes 11:30 PM and midnight. To book later,
use **Edit Operating Hours** to extend the selected date's closing time first.
A midnight close offers 11:00 PM, 11:30 PM and 12:00 AM as end times.

For receipt approval, counter settlement and automatic loyalty awards, follow [Recurring payments and points](recurring-payments-points.md#recurring-court-bookings).

![Approved booking review](../images/2026-10-12-13/booking-reviews.png)

## 30-minute bookings

**Available:** One-off court bookings require at least one hour for
either sport unless the selected half-hour is surrounded by occupied slots on
the same court/date. This check also applies to admin creation. Check the
schedule before saving; opening and closing boundaries do not qualify. A paid
half-hour member booking earns points from its actual half-hour payment.

Try the [30-minute court booking test guide](30-minute-court-bookings.md).
