# System Architecture

## Overview

The Accounting System is designed using a modular architecture that separates business logic from the presentation layer, making the application scalable, maintainable, and easy to extend.

```
Frontend (React)
        │
        │ HTTP (Axios)
        ▼
REST API (Express.js)
        │
        ▼
Business Logic
        │
        ▼
Database
```

---

## Frontend

Built using:

- React 19
- TypeScript
- Tailwind CSS
- React Router
- TanStack Query

Responsibilities:

- Rendering UI
- Managing Forms
- State Management
- API Communication
- Client-side Validation

---

## Backend

Built using:

- Node.js
- Express.js

Responsibilities:

- Authentication
- Authorization
- CRUD Operations
- Business Rules
- Database Communication

---

## Database

Stores:

- Users
- Customers
- Suppliers
- Products
- Sales
- Purchases
- Inventory
- Reports

---

## Design Principles

- Component-Based Architecture
- Reusable Components
- Separation of Concerns
- Scalable Folder Structure
- API-Driven Development