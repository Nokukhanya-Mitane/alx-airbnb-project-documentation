# Airbnb Clone – User Stories

## 🎯 Objective
This document translates the key interactions identified in the **Airbnb Use Case Diagram** into **user stories**.  
Each story follows the standard agile format:  
> *As a [role], I want [goal] so that [benefit/result].*

---

## 🧍‍♀️ 1. User Registration and Authentication
**Story:**  
As a **user**, I want to **create an account or log in securely** so that **I can access my personal dashboard and manage my bookings or listings.**

**Acceptance Criteria:**
- User can sign up with email and password.
- User can log in using credentials or OAuth (Google, Facebook).
- Passwords are stored securely (hashed).
- JWT authentication is implemented for session management.

---

## 🏠 2. Property Management (Host)
**Story:**  
As a **host**, I want to **add and manage property listings** so that **I can rent out my properties to guests.**

**Acceptance Criteria:**
- Host can add a new property with title, description, price, and amenities.
- Host can update or delete their own properties.
- Properties are linked to the host’s user ID.
- Only hosts can perform these actions.

---

## 🔍 3. Search and Booking (Guest)
**Story:**  
As a **guest**, I want to **search for properties and make bookings** so that **I can find and reserve suitable accommodation for my stay.**

**Acceptance Criteria:**
- Guests can search by location, price range, and number of guests.
- Guests can select dates and confirm availability.
- Double-bookings are prevented.
- Booking status is visible (pending, confirmed, canceled).

---

## 💳 4. Payment Handling
**Story:**  
As a **guest**, I want to **make secure payments for bookings** so that **my reservations are confirmed and hosts receive payment automatically.**

**Acceptance Criteria:**
- Guests can pay using credit card, PayPal, or Stripe.
- Payment is linked to the booking record.
- Hosts receive payout after booking completion.
- Transaction records are stored securely.

---

## ⭐ 5. Reviews and Ratings
**Story:**  
As a **guest**, I want to **write a review and rate a property** so that **I can share my experience and help other users make informed decisions.**

**Acceptance Criteria:**
- Only guests who completed a booking can review.
- Reviews include a star rating (1–5) and comment.
- Hosts can respond to reviews.
- Admin can moderate inappropriate content.

---

## 🛡️ 6. Admin Management
**Story:**  
As an **admin**, I want to **monitor users, bookings, and payments** so that **I can ensure the platform operates securely and efficiently.**

**Acceptance Criteria:**
- Admin can view and manage all users, listings, and transactions.
- Admin can deactivate fraudulent users or listings.
- Admin can access audit logs and reports.

---

## ✅ Summary
These user stories represent the **core backend interactions** derived from the **Airbnb Use Case Diagram**:
- User authentication  
- Property management  
- Search and booking  
- Payments  
- Reviews  
- Administration  

They form the foundation for future **API design**, **database modeling**, and **feature implementation**.
