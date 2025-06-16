# 🦋 Papillon Vital

**Papillon Vital** is an e-commerce platform built with **Ruby on Rails**, dedicated to selling **organic products** specifically selected to support people living with **Hashimoto’s thyroiditis**.

The application focuses on:
- High-quality natural products
- A **smooth and user-friendly experience**
- A **responsive and accessible interface**
- **Secure payment integration**
- Simple admin order management

---

## 🌿 Overview

Papillon Vital helps users:
- Discover thyroid-friendly organic products
- Order them online
- Navigate easily in a safe, multilingual environment

The project was developed as part of the **The Hacking Project** web development bootcamp.

---

## 🚀 MVP Features

### 🛍️ For Visitors

- Browse all available products
- View detailed product information
- Sign up / Log in (Devise)

### 🧾 For Logged-in Users

- Add products to a shopping cart
- Update or remove quantities
- Checkout securely via **Stripe**
- Receive a confirmation email after payment

### 🛠️ For Admins

- Receive an order confirmation email with full order details

---

## 🔜 Upcoming Features (Post-MVP)

- Admin dashboard with charts and stats (Chartkick)
- Full CRUD for product management
- Order history per user
- Favorite product saving
- Delivery status updates
- Product filtering by type
- Mobile/tablet/desktop responsiveness

---

## ⚙️ Tech Stack

| Layer             | Tools / Frameworks                                     |
|-------------------|--------------------------------------------------------|
| **Backend**        | Ruby on Rails 8.0.2                                    |
| **Database**       | SQLite (dev) / PostgreSQL (prod)                      |
| **Frontend**       | HTML, CSS, Bootstrap (or Tailwind)                    |
| **Authentication** | Devise + devise-i18n                                  |
| **Payments**       | Stripe                                                |
| **Dynamic UI**     | Hotwire (Turbo + Stimulus)                            |
| **Background Jobs**| ActiveJob + Solid Queue                               |
| **Mailer**         | ActionMailer                                          |
| **Deployment**     | Docker via **Kamal**                                  |
| **Testing**        | RSpec, Capybara, FactoryBot, Faker                    |
| **Security**       | Brakeman, Rubocop, BCrypt                             |
| **Caching**        | Solid Cache                                           |
| **Compression**    | Thruster                                              |
| **Assets**         | Propshaft                                             |

---

## 🧰 Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/papillon-vital.git
cd papillon-vital
