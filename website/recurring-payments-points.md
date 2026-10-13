# Recurring courts and lessons: payments and points

[← Overview](../overview.md) · **Who:** Administrators

Registered members earn **1 loyalty point per complete RM received** when payment is finalized. Admins award these points by completing the payment workflow below. Do not add the same points separately in Points Management or through MCP.

## What monthly renewal does

Eligible recurring court and lesson rules renew automatically into the next month. Renewal itself awards **no points**.

| Recurring activity | Result of renewal | Action that awards member points |
|---|---|---|
| Court booking | A new unpaid booking cycle, even when the previous cycle was paid | Approve its receipt or mark that cycle paid after receiving payment |
| Lesson | Next month's lessons and enrollments, which feed the lesson-fee balance | Approve a lesson-fee receipt or record a received lesson-fee payment |

Rules spanning multiple months or without an end date are not renewed by the monthly job. Review the next month's schedule before arranging payment.

## Recurring court bookings

1. Open [Schedule → Bookings](https://tzhsports.vercel.app/admin/schedule?tab=bookings), find the recurring member row and expand it.
2. Check the account, court, dates and time for the cycle being paid. Points require a registered member account; guest payments earn none.
3. Complete **one** payment path:
   - **Member uploaded a receipt:** Choose **Review receipt**, inspect the proof and cycle details, then **Approve**. Members submit proof from [My Payments](https://tzhsports.vercel.app/my-payments).
   - **Payment received at the counter:** Open **Details**, choose **Mark as Paid (Counter Payment)** and confirm only after receiving the full cycle payment.
   - **Several cycles paid:** Select the intended recurring rules and use bulk **Mark Paid**. Check every selected cycle before confirming, then review the individual results; some items can fail while others succeed.
4. Confirm the cycle shows **Paid**. Its registered member earns points on the full settled cycle total automatically.

**Example:** A fictional member's cycle totals RM240. Finalizing that cycle's payment awards **240 points**. Renewing it, uploading proof or rejecting proof awards none.

When initially creating a recurring court rule, marking it already paid also awards member points immediately. Choose that state only when payment has already been received. Assigning an already-paid guest cycle to a member later does not backfill points.

## Recurring lessons

1. Open [Lesson Management → Member Fees](https://tzhsports.vercel.app/admin/lesson-fees?tab=fees), search for the member and check their statement and outstanding balance.
2. Complete **one** payment path:
   - **Member uploaded a receipt:** Choose **Review receipt**, inspect the amount and proof, then **Approve & Award … Points** (or **Approve** when no whole-RM points apply).
   - **Payment received offline:** Choose **Record payment**. Enter the actual **Amount** received in RM, select **Payment method**, add optional **Notes**, then **Save payment**.
3. Confirm the payment is recorded and the balance updates. Points follow the received payment amount, including partial payments; creating or renewing lessons does not award them.

**Example:** A fictional member owes RM180 but pays RM100 now. Recording that received payment awards **100 points**. A later finalized RM80 payment awards another **80 points**.

Free replacement lessons do not earn spending points.

## Check the award

Ask the member to open [My Points](https://tzhsports.vercel.app/my-points) and check the court-booking or lesson-fee payment entry. Paid invoices appear in [My Invoices](https://tzhsports.vercel.app/my-invoices); lesson payment records and statements are in [My Lesson Fees](https://tzhsports.vercel.app/my-lesson-fees).

Amounts are rounded down to complete RM: RM100.50 earns **100 points**. Pending/rejected receipts and unpaid cycles earn none. If a payment succeeds but its points entry appears missing, check the correct member account and payment record with the centre owner before making any manual award or recording the payment again.
