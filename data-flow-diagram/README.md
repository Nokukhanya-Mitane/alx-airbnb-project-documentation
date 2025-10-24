# Airbnb Clone – Data Flow Diagram (DFD)

## 🎯 Objective
This document presents the **Data Flow Diagram (DFD)** for the Airbnb Clone backend system.  
It visualizes how data moves between users, the backend processes, and data stores, ensuring clear understanding of system interactions.

---

## 🧍 External Entities
- **User (Guest/Host):** Provides data for registration, bookings, and reviews.  
- **Payment Gateway:** Handles external payment transactions securely.  
- **Admin:** Oversees users, bookings, and payments.

---

## ⚙️ Key Processes
1. **User Management** – Registers users, manages authentication, and updates profiles.  
2. **Property Management** – Hosts add, edit, and delete property listings.  
3. **Booking Management** – Guests make and cancel bookings; checks property availability.  
4. **Payment Processing** – Handles secure payments and stores transaction records.  
5. **Review Management** – Guests submit reviews and ratings for completed bookings.

---

## 💾 Data Stores
| Data Store | Description |
|-------------|-------------|
| **D1 – User Data Store** | Stores user credentials, roles, and profiles. |
| **D2 – Property Data Store** | Holds property details and availability. |
| **D3 – Booking Data Store** | Contains all booking records and statuses. |
| **D4 – Payment Data Store** | Stores payment transaction information. |
| **D5 – Review Data Store** | Contains guest reviews and ratings. |

---

## 🔁 Data Flow Summary
- Users interact with the system through registration, property listing, booking, payment, and reviews.
- Each process exchanges data with its respective data store.
- The Admin can view and manage all stored data through a secure interface.
- Payments are processed via an external gateway, ensuring secure transactions.

---
