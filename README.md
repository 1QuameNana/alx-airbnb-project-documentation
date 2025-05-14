# alx-airbnb-project-documentation
1. User Authentication & Management
Entities:

Users (Guest, Host, Admin)

Functionalities:

User registration (with role assignment: Guest/Host)

Email/password login

Password encryption (e.g., bcrypt)

JWT-based authentication

Password reset (email OTP or reset link)

Profile management (name, bio, photo, contact info)

Email verification

Admin-specific:

View all users

Deactivate / suspend accounts

2. Property Management
Entities:

Properties

Amenities

Property Images

Availability

Functionalities:

Host adds new property

Title, description, location, price

Upload multiple images

Select amenities

Set availability calendar

Update / delete property

Host dashboard to view their listings

Search/filter properties by:

Location

Price range

Type

Availability

3. Booking System
Entities:

Bookings

Guests

Hosts

Functionalities:

Guest can request booking

Host can accept/decline requests

Booking confirmation emails

Prevent double-booking

Booking history (for guests & hosts)

Booking status: pending, accepted, declined, cancelled, completed
 4. Payments & Transactions
Entities:

Payments

Payouts

Transactions

Functionalities:

Integrate with payment gateways (e.g., Stripe/PayPal)

Secure payment for bookings

Payment status tracking (pending, succeeded, failed)

Host payouts after booking completion

Refunds & cancellation handling

View payment history per user

 5. Messaging System
Entities:

Messages

Threads (Conversation ID)

Functionalities:

Guest ↔ Host messaging

Secure message storage

Notification on new message

Threaded conversations by booking

 6. Reviews & Ratings
Entities:

Reviews

Ratings

Users

Properties

Functionalities:

Guest reviews property after stay

Star rating (1–5)

Optional written review

Host review guest

Prevent multiple reviews per booking

Review moderation (by Admin)

 7. Security & Access Control
Functionalities:

Role-based access (Guest, Host, Admin)

Rate limiting (e.g., on login or messaging)

Input validation and sanitization

Activity logs (admin view)

Two-factor authentication (optional)

 8. Admin Dashboard
Functionalities:

View/manage all users, properties, bookings

Approve or ban listings

Issue refunds or manage disputes

Review reported messages or users

Analytics (e.g., bookings per month, revenue)

 9. Notifications System
Functionalities:

Email notifications (booking confirmation, message alerts, etc.)

Optional push notifications (mobile/web)

Notification preferences per user