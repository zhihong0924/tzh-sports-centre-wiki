# Arrange off-site lessons

[← Overview](../overview.md) · **Who:** Administrators (including coaches using admin accounts)

**Status: Testing** — available on the local test website; awaiting production deployment.

## Administrator

1. Open [Lesson Management](http://localhost:3000/admin/lesson-fees), choose the date and select **Create Lesson** or **Create Recurring Lesson**. The same forms are available in [Schedule → Lessons](http://localhost:3000/admin/schedule?tab=lessons).
2. In **Court / venue**, choose **Off-site — no centre court**.
3. Enter **Off-site location**, for example **Demo School Hall**. Choose the lesson type, start time and duration. Off-site times can be outside centre operating hours; the lesson must finish by midnight on the same date.
4. Check the fee and seats, add students and any assistants, then create the lesson. For recurring lessons, also check the recurrence and start/end dates.
5. In Lesson Management, find the occurrence under **Off-site lessons**, then **Details** for later changes. Use the normal Enrollment, Attendance and Member Fees tabs for student administration and payments.

![Fictional off-site lesson form](../images/features/offsite-lesson-create.png)

![Fictional recurring off-site form](../images/features/offsite-recurring-create.png)

## Expected results and points

The lesson shows its external location and reserves **no centre court**. Generated recurring sessions and monthly renewal keep the location. Centre courts remain available for ordinary bookings, subject to their other bookings and lessons.

Off-site lessons use the normal enrollment-based fees. Creating or renewing them awards **no points**. When an admin approves a registered member's lesson-fee receipt or records received payment, the member earns **1 point per complete RM received** automatically. Follow [Recurring payments and points](recurring-payments-points.md#recurring-lessons); do not add the same points manually.

Enrolled members can check the external location in [My Lessons](http://localhost:3000/my-lessons) and their charges in [My Lesson Fees](http://localhost:3000/my-lesson-fees).
