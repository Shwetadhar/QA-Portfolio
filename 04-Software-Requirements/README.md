# 📗 Software Requirements Specification (SRS)

## Project Information

| Field | Details |
|--------|---------|
| Project | ShopEase |
| Application Type | E-Commerce Web Application |
| Version | 1.0 |
| Prepared By | Shweta Dharmik |

---

# Purpose

The Software Requirements Specification (SRS) defines the functional and non-functional requirements of the ShopEase application. It provides a detailed description of system behaviour and serves as the foundation for development, testing, and validation.

---

# Functional Requirements

## Authentication

- Users shall register using a valid email address.
- Users shall log in using registered credentials.
- Users shall reset forgotten passwords.
- Users shall log out securely.

---

## Product Catalogue

- Users shall browse product categories.
- Users shall search products.
- Users shall filter products.
- Users shall sort products.
- Users shall view product details.

---

## Shopping Cart

- Add products to the cart.
- Update product quantities.
- Remove products.
- Display cart total.

---

## Checkout

- Capture shipping address.
- Select payment method.
- Place order.
- Generate order confirmation.

---

## User Profile

- View profile.
- Edit profile.
- View order history.

---

## Admin

- Add products.
- Edit products.
- Delete products.
- Manage customer orders.

---

# Non-Functional Requirements

- Responsive Design
- Browser Compatibility
- Secure Authentication
- Data Integrity
- High Availability
- Fast Page Loading
- Scalability

---

# Supported Browsers

- Google Chrome
- Microsoft Edge
- Mozilla Firefox

---

# Technology Stack

Frontend:
- HTML
- CSS
- JavaScript

Backend:
- REST API

Database:
- MySQL

Testing Tools:
- Jira
- TestRail
- Postman
- Playwright
- Selenium

---

# Assumptions

- Stable internet connection.
- Secure payment gateway.
- Database availability.
- Browser support is up to date.

---

# Dependencies

- Payment Gateway
- Email Service
- MySQL Database
- Authentication Service
