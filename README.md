# Event Ease

### College Event Management System

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## Project Overview

**Event Ease** is a web-based College Event Management System developed using Next.js, React, TypeScript, and Firebase.

The platform simplifies college event organization by allowing students to explore upcoming events, register for activities, and track bookings.

Administrators can create events, manage registrations, organize categories, and monitor seat availability through a centralized management system.

## Features

### Student Features

- Explore upcoming college events
- View event details and schedules
- Register for available events
- View registered events and bookings
- Check event seat availability

### Administrator Features

- Secure administrator authentication
- Create, update, and manage events
- Manage event categories
- View student registrations
- Monitor event bookings
- Track available seats

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | Next.js, React, TypeScript |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| Hosting | Vercel |
| Version Control | Git and GitHub |

## Project Structure

```text
event-ease/
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── next.config.ts
└── README.md
```

*The structure above is illustrative and should be checked against the repository.*

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/arenihal/event-ease.git
```

### 2. Navigate to the Frontend

```bash
cd event-ease/frontend
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Firebase

Create a `.env.local` file inside the `frontend` directory.

Add the Firebase web configuration environment variables required by the application.

Never add private credentials to this file or commit it to GitHub.

### 5. Run the Development Server

```bash
npm run dev
```

### 6. Open the Application

Visit:

http://localhost:3000

## Deployment

The application is designed for deployment on **Vercel**.

1. Connect the GitHub repository to Vercel.
2. Select the Event Ease repository.
3. Configure `frontend` as the Root Directory.
4. Add the required Firebase environment variables.
5. Deploy the application.

## Security

- Firebase Authentication for user authentication
- Firestore Security Rules for database access control
- Verified administrator permissions for privileged operations
- Environment variables for application configuration
- No private keys or service-account credentials committed to GitHub

## Future Enhancements

- Event search and filtering
- Registration confirmation notifications
- QR-based event check-in
- Event attendance tracking
- Administrator analytics dashboard

## Project Status

**Under Active Development**

Event Ease is being developed to simplify college event organization, student registration, and event management.

## Repository

[Event Ease – GitHub](https://github.com/arenihal/event-ease)

---

**Built with Next.js, React, TypeScript, and Firebase.**
