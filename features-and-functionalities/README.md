# Airbnb Clone – Features and Functionalities

## Objective
This document describes the **core backend features** and **functionalities** of the Airbnb Clone project.  
It also includes a visual representation of how these features interact within the system architecture.

---

## 1. User Management
- User registration, login, and logout.
- Secure password hashing and authentication.
- Roles: Guest, Host, Admin.
- View and update user profiles.

---

## 2. Property Management
- Hosts can create, update, and delete property listings.
- Store property details: name, description, location, price, and images.
- Guests can browse and search available listings.
- Admin moderation for properties.

---

## 3. Booking System
- Guests can book available properties.
- Validate booking dates and avoid overlaps.
- Calculate total price.
- Update or cancel bookings.
- Booking statuses: `pending`, `confirmed`, `canceled`.

---

## 4. Payment Processing
- Record payment details for confirmed bookings.
- Supported methods: credit card, PayPal, Stripe.
- Track payment amounts, dates, and methods.
- Admin oversight for transactions.

---

## 5. Messaging System
- Enables communication between guests and hosts.
- Stores messages with timestamps.
- Provides notifications for new messages (future enhancement).

---

## 6. Reviews & Ratings
- Guests can leave reviews after booking completion.
- Ratings from 1 to 5 stars.
- Comments stored per property.
- Admin can moderate or remove reviews.

---

## 7. Admin Dashboard
- Manage users, properties, and bookings.
- Monitor platform activities and payments.
- Remove inappropriate content.
- Future enhancements: analytics and reporting.

---

## 8. System & Security
- JWT or session-based authentication.
- Input validation and data sanitization.
- Secure password storage (bcrypt or similar).
- Logging and error handling.
- Encrypted sensitive information.

---
