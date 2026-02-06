# Corleone Forged - Order Tracking System

## Original Problem Statement
Build an order tracking app for a custom wheel manufacturing company that allows for real-time tracking of orders across different departments.

## Architecture & Features Completed

### Backend (FastAPI + MongoDB)
- JWT Authentication with role-based access (admin/staff)
- Order CRUD with department workflow
- 8 Department flow: received → design → program → machine → powder_coat → assembly → showroom → shipped → completed
- PDF export endpoint for order reports
- Stats and analytics endpoints

### Frontend (React + Tailwind + Shadcn UI)
- Dark industrial theme with Corleone Forged branding
- Login/Register with department selection
- Admin dashboard with 8 department columns
- Staff view (single department queue)
- Order creation with product types (Rim/Steering Wheel)
- PDF export for any department
- Completed orders report with filtering

### Key Files
- `/app/backend/server.py` - Main API
- `/app/frontend/src/pages/LoginPage.jsx` - Authentication
- `/app/frontend/src/pages/DashboardPage.jsx` - Main dashboard
- `/app/frontend/src/pages/CompletedPage.jsx` - Completed orders report

## Next Tasks (Future Enhancements)
1. SMS/Email notifications when order ready for pickup
2. Customer search/lookup functionality
3. Order edit capability (update specs, customer info)
4. Date range filtering for reports
5. Print order labels or receipts
6. QuickBooks integration (if requested)
7. Vehicle info tracking per order
