<div align="center">
  <img src="https://via.placeholder.com/150x150?text=Chazon+Logo" alt="Chazon Logo" width="120" />

  <h1>Welcome to Chazon 👋</h1>
  
  <p><strong>Transforming campus exposure into real growth.</strong></p>
  
  <p>
    Chazon is a student-first event discovery and participation platform built for campuses. We centralize event information, registrations, and organizer profiles into one trusted place—helping students discover relevant events, engage intentionally, and turn their campus experience into social capital.
  </p>
</div>

---

## 🏗️ The Ecosystem

We are building a secure, scalable platform to connect students directly with event organizers and communities. Our core architecture is split across the following repositories:

* **[`chazon-frontend`](#)**: The Progressive Web App (PWA) built with **React / Next.js**. This handles the student discovery feed, QR code scanning, and organizer dashboards. *(State management via Zustand)*.
* **[`chazon-backend`](#)**: The core API built with **Laravel**. This handles our PostgreSQL database, business logic, role-based access control, and secure authentication via Sanctum.

---

## 💻 Tech Stack

We believe in using modern, type-safe, and scalable tools to build our MVP and beyond:

* **Frontend:** React.js, Next.js, TailwindCSS, TypeScript
* **Backend:** Laravel, PHP
* **Database:** PostgreSQL
* **Infrastructure:** Vercel (Frontend Hosting), Cloud-based deployment
* **Security:** HTTPS, Secure password hashing, Role-Based Access Control (RBAC)

---

## 🚀 Current Focus (MVP Scope)

We are actively developing our MVP, focusing on the core loops that bring value to students and organizers:

- [x] **Event Discovery:** Campus-focused feeds filtered by category (career, social, tech, etc.).
- [x] **Registration & Attendance:** Seamless sign-ups and QR code scanning to validate real participation.
- [x] **Organizer Tools:** Dashboards for creating events, managing visibility, and tracking basic engagement metrics.
- [x] **In-Platform Communication:** Automated confirmations and organizer-to-attendee update broadcasts.

## 🗺️ Future Enhancements (Phase 2)

Once the core discovery and attendance loops are validated, we are scaling to include:
* Volunteer tracking, credits, and event certificates.
* Advanced analytics and transparency dashboards showing impact metrics.
* Payments, ticketing, and sponsorship support.
* Verified organizer badges and campus-wide announcements.

---

## 🤝 For Developers & Contributors

If you are joining the team, please make sure you have requested access to the necessary repositories from the organization owner. 

**Getting Started:**
1. Clone the Backend API repository and follow the local environment setup guide to get your database running.
2. Clone the Frontend repository, link it to your local backend API, and install dependencies.
3. Check our internal Notion/Docs for our API contracts and TypeScript interfaces.

*Built with ❤️ for students, by students.*
