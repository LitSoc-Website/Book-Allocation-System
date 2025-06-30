# LitSoc Book Allocation System

This repository hosts the Book Allocation System for the LitSoc Club, designed to manage internal assignments of books for events, workshops, or specific member usage. It complements the main Library Management System by tracking books allocated outside general patron loans.

Built using the MERN stack (MongoDB, Express, React, Node.js) with TypeScript for full-stack type safety.

> Note: Active development is on the `main` branch.

---

## Features

- Book Allocation Tracking  
  Assign books to club events, workshops, or individual members.

- Allocation History  
  Maintain a log of all past and current book allocations.

- Availability Management  
  Update availability status based on allocations (standalone or integrated with the main library).

- Reporting  
  Generate reports on who has which books and for what purpose.

- Admin Dashboard  
  Simple and intuitive interface for administrators to manage allocations.

---

## Technologies Used

### Backend (Node.js + Express + TypeScript)

- Node.js – JavaScript runtime
- Express.js – Web framework for APIs
- TypeScript – Static typing
- MongoDB – NoSQL database
- Mongoose – ODM for MongoDB
- Authentication – JWT (shared with main library or standalone)
- dotenv – Environment variable management

### Frontend (React + TypeScript + Redux)

- React – UI library
- TypeScript – For type safety
- Redux Toolkit – State management
- React Router DOM – Client-side routing
- Axios – API calls
- Tailwind CSS – Styling
- Lucide React – Icons
