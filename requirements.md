# Airbnb Clone Backend Requirement Specifications

## 🎯 Objective
This document outlines the technical and functional requirements for three key backend features of the **Airbnb Clone Project**:
1. User Authentication  
2. Property Management  
3. Booking System  

Each section defines the required API endpoints, data validation rules, input/output structures, and performance considerations.

---

## 1️⃣ User Authentication Module

### 💡 Functional Overview
This module manages user registration, login, and authentication using JWT (JSON Web Tokens). It supports both guests and hosts and ensures secure access to the system.

### 🔗 API Endpoints

| Method | Endpoint | Description | Authentication |
|--------|-----------|--------------|----------------|
| `POST` | `/api/v1/auth/register` | Register a new user (guest or host) | No |
| `POST` | `/api/v1/auth/login` | Log in and retrieve JWT token | No |
| `GET` | `/api/v1/auth/profile` | Retrieve logged-in user’s profile | Yes |
| `PUT` | `/api/v1/auth/profile` | Update user profile details | Yes |

---

### 🧾 Input/Output Specifications

#### **POST /api/v1/auth/register**
**Input:**
```json
{
  "first_name": "Nokukhanya",
  "last_name": "Mitane",
  "email": "user@example.com",
  "password": "StrongPassword123!",
  "role": "host"
}
