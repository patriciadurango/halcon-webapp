#  Halcón WebApp

Web application for **Halcón**, a construction material distributor. This system automates internal order management and allows customers to track their orders in real time.

---

## Features

- Order lifecycle management (Ordered → In Process → In Route → Delivered)
- Role-based access control (Admin, Sales, Warehouse, Purchasing, Route)
- Photo upload as delivery evidence (Route personnel only)
- Customer order tracking (no login required)
- Soft-delete and order restoration

## User Roles

| Role | Responsibilities |
|------|-----------------|
| Admin | Manage users and assign roles |
| Sales | Create and manage orders |
| Warehouse | Process orders and update status |
| Purchasing | Procure missing materials |
| Route | Distribute orders and upload delivery photos |

##  Order Statuses

| Status | Description |
|--------|-------------|
| Ordered | Order placed by Sales |
| In Process | Warehouse preparing the order |
| In Route | Order loaded and dispatched |
| Delivered | Order delivered with photo evidence |

## Work Methodology: Scrum (Agile)
Scrum was chosen because the client's requirements came from an interview and will likely change as the project progresses. Scrum's short sprints (1–2 weeks) let the team deliver working features regularly, get client feedback, and adjust without starting over. Unlike Waterfall, it doesn't require locking all requirements upfront, and unlike Kanban, it has structured reviews that keep the client involved throughout the process.

## Tech Stack

- **Frontend:** React.js + Tailwind CSS
- **Backend:** Node.js + Express
- **Database:** MySQL
- **Auth:** JWT + bcrypt
- **File Storage:** Cloudinary


