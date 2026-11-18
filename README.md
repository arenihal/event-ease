# Event Ease — College Event Management System

![Next.js](https://img.shields.io/badge/Next.js-black?logo=nextdotjs) ![React](https://img.shields.io/badge/React-149ECA?logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?logo=firebase&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-black?logo=vercel)

**[Live Website](https://eventease-web-sooty.vercel.app/explore-events)** · **[GitHub Repository](https://github.com/arenihal/event-ease)**

Event Ease is a college event management web application built with Next.js, React, TypeScript, and Firebase. Students can discover events, view details, register, and manage bookings. Administrators can manage events and monitor registrations.

## Features

**Student:** Explore events, search and filter by category, view event details and seat availability, book events, view or cancel bookings, and manage profile settings.

**Administrator:** Sign in to an administrator dashboard, create and manage events and categories, monitor bookings and registered students, and review event seat availability.

## Screenshots

### Student Login
![Student Login](screenshots/login-page.png)

### Student Dashboard
![Student Dashboard](screenshots/student-dashboard.png)

### Explore Events
![Explore Events](screenshots/explore-events.png)

### Event Details
![Event Details](screenshots/event-details.png)

### My Bookings
![My Bookings](screenshots/my-bookings.png)

### Student Profile
![Student Profile](screenshots/student-profile.png)

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### Manage Events
![Manage Events](screenshots/manage-events.png)

## Technology Stack

| Area | Technology |
| --- | --- |
| Frontend | Next.js, React, TypeScript |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| Deployment | Vercel |
| Version Control | Git and GitHub |

## Getting Started

```bash
git clone https://github.com/arenihal/event-ease.git
cd event-ease/frontend
npm install
npm run dev
```

Configure the Firebase web environment variables in `frontend/.env.local` before starting the app. Open http://localhost:3000.

## Deployment

Deploy to Vercel using `frontend` as the Root Directory, and configure the required Firebase environment variables in the Vercel project settings.

## Security

Protect privileged administrator actions using verified authorization and Firestore Security Rules. Never commit service-account credentials, private keys, or `.env.local` files.

## Project Status

Under active development.
