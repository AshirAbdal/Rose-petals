# Rose-petals

Got it — thanks for calling it out 👍
Let’s reset and make this **practical, actionable, and team-oriented**, not generic theory.

Below is a **VERY DIRECT README** focused on:

1. **Clear work division (who does what)**
2. **Exact use of the Facebook URL as a design reference**
3. **Step-by-step build order**

You can use this as a *living contract* between the 3 of you.

---

# 🛒 E-Commerce Shopping Website (Team Project)

## 📌 Design Reference (MANDATORY)

**Primary UI / UX reference:**
👉 [https://www.facebook.com/share/1ADkJncxFu/?mibextid=wwXIfr](https://www.facebook.com/share/1ADkJncxFu/?mibextid=wwXIfr)

> All layouts, product cards, spacing, banners, and visual flow must FOLLOW this Facebook page’s design pattern (not copied blindly).

Frontend developer must continuously compare screens with this URL.

---

## 👥 Team Work Division (IMPORTANT)

### 👤 Developer 1 – Frontend (React)

**Main Responsibility:** UI, UX, API integration

**Tasks**

* Create React project (Vite / CRA)
* Build UI based on Facebook reference
* Implement pages:

  * Home page (product feed style like Facebook page)
  * Product listing
  * Product details
  * Cart page
  * Checkout page
  * Login / Register
* API integration with Laravel
* State management (Cart, User, Orders)
* Responsive design (mobile first)

**Deliverables**

* Fully working UI
* Clean reusable components
* Connected to backend APIs

---

### 👤 Developer 2 – Backend (Laravel)

**Main Responsibility:** Business logic, API, database

**Tasks**

* Setup Laravel project
* Database design & migrations
* Authentication (User & Admin)
* REST APIs:

  * Auth
  * Products
  * Categories
  * Cart
  * Orders
* Admin APIs
* Validation & security
* Image upload + CDN support (SADCDN)

**Deliverables**

* REST API with documentation
* Secure auth system
* Optimized database

---

### 👤 Developer 3 – Full Stack / Integrator

**Main Responsibility:** Architecture, coordination, deployment

**Tasks**

* Define API contract between frontend & backend
* Review Facebook design and break into components
* Environment setup (.env, configs)
* API testing (Postman)
* Performance optimization
* CDN configuration (SADCDN)
* Final deployment

**Deliverables**

* Smooth frontend–backend integration
* Stable production build
* Deployment documentation

---

## 🧱 Technology Stack

### Frontend

* React
* React Router
* Axios
* Redux Toolkit / Context
* Tailwind CSS / SCSS

### Backend

* Laravel
* Laravel Sanctum / JWT
* MySQL
* Queue & Jobs
* CDN (SADCDN)

---

## 🗂️ Folder Structure

### Frontend

```
frontend/
├── src/
│   ├── components/
│   ├── pages/
│   ├── layouts/
│   ├── services/   // API calls
│   ├── store/
│   └── utils/
```

### Backend

```
backend/
├── app/
│   ├── Http/Controllers/
│   ├── Models/
│   └── Services/
├── routes/api.php
├── database/migrations/
```

---

## 🔄 Development Phases (DO NOT SKIP)

### Phase 1 – Planning (ALL MEMBERS)

✅ Review Facebook URL
✅ Break design into pages & components
✅ Finalize database tables
✅ Define API list

---

### Phase 2 – Core Setup

**Frontend**

* Base layout (header, footer)
* Home page UI cloned from Facebook layout

**Backend**

* Auth APIs
* Product & category tables
* Admin login

---

### Phase 3 – Shopping Flow

* Product listing
* Product details
* Add to cart
* Cart management
* Checkout API

---

### Phase 4 – Admin Panel

* Product CRUD
* Order management
* User management

---

### Phase 5 – Optimization

* CDN for images
* Performance tuning
* Security review
* Production deployment

---

## 📡 API Ownership Rule

Backend **ONLY** creates APIs
Frontend **ONLY** consumes APIs
No direct DB access from frontend

API example:

```
GET /api/v1/products
POST /api/v1/cart
POST /api/v1/order
```

---

## 🔐 Auth Rules

* User & Admin roles
* Token-based auth
* Protected routes
* Admin-only endpoints

---

## 🧪 Testing Responsibility

| Task              | Owner                |
| ----------------- | -------------------- |
| API Testing       | Backend + Integrator |
| UI Testing        | Frontend             |
| Full Flow Testing | All                  |

---

## 🔁 Git Rules

* Branch per feature
* No direct push to `main`
* Pull request + review mandatory

---

## ✅ Definition of Done

A feature is DONE only if:

* UI matches Facebook reference
* API is documented
* No console errors
* Mobile works
* Code reviewed

---

If you want, next I can:

* ✅ Break the **Facebook page UI into exact React components**
* ✅ Design the **database tables**
* ✅ Create a **task board (per developer)**
* ✅ Write **API endpoint contracts**
* ✅ Draw **system architecture**

Tell me what you want next — we’ll lock it down properly.
