# Event Ease

**College Event Management System**

Event Ease is a web-based college event management system developed using Next.js, React, TypeScript, and Firebase. It provides a centralized platform for students to explore and register for college events while allowing administrators to manage events and registrations efficiently.

## Features

### Student
- Explore upcoming college events
- View event details and schedules
- Register for available events
- View registered events and bookings
- Check event seat availability

### Administrator
- Secure administrator authentication
- Create, update, and manage events
- Manage event categories
- View student registrations
- Monitor bookings and seat availability

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
EventEase/
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── next.config.ts
└── README.md
```

## Getting Started

**1. Clone the repository**

```bash
git clone <repository-url>
```

**2. Navigate to the frontend**

```bash
cd EventEase/frontend
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure Firebase**

Create a `.env.local` file inside the frontend directory and configure the required Firebase environment variables.

**5. Start the development server**

```bash
npm run dev
```

**6. Open the application**

Visit http://localhost:3000.

## Deployment

The application is designed for deployment on Vercel.

- Connect the GitHub repository to Vercel.
- Set `frontend` as the Root Directory.
- Configure Firebase environment variables.
- Deploy the application.

## Security

- Use Firebase Authentication for user authentication.
- Configure Firestore Security Rules to restrict unauthorized access.
- Protect administrator operations using verified permissions.
- Never commit private keys, service-account credentials, or `.env.local` files.

## Project Status

**Under Active Development**

Event Ease is being developed to simplify college event organization, student registration, and event management.
