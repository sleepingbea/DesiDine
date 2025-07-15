#  DesiDine

**DesiDine** – A culturally rooted food delivery platform that empowers local chefs, brings authentic Indian flavors online, and simplifies food ordering for everyone.

##  Tech Stack

- **Frontend:** React, Vite, React Router
- **Backend:** Node.js, Express, MongoDB
- **Admin Panel:** React (for vendor-side management)
- **Payments:** Stripe Integration
- **Authentication:** JWT-based login

## Folder Structure

DesiDine/
├── frontend/ # Customer website
├── backend/ # API & DB logic
├── admin/ # Admin panel

## 🔧 Setup Instructions

```bash
npm install            # From root, to install dev tools like concurrently
cd frontend && npm install
cd ../backend && npm install
cd ../admin && npm install

Create a .env file inside /backend:
PORT=5000
MONGO_URI=your_local_or_cloud_connection_string
JWT_SECRET=random#secret
STRIPE_SECRET_KEY=your_stripe_key

Run App Concurrently
From the root folder:
npm run dev
