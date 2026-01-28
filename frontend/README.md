# ChatApp Frontend

The React-based frontend for the ChatApp real-time chat application. Built with React 18, TailwindCSS, and Firebase authentication.

## Installation

Navigate to the frontend directory and install dependencies:

```bash
npm install
```

## Available Scripts

### `npm start`

Starts the development server.\
Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.\
The app will hot-reload when you make changes.

### `npm run build`

Builds the app for production to the `build` folder.

### `npm test`

Runs the test suite in interactive watch mode.

## Features

- User authentication with Firebase
- Create and join chat rooms
- Real-time messaging with Socket.io
- User online status indicators
- Search and discover users
- Custom avatar generation with DiceBear API
- Dark mode support
- Emoji picker integration
- Responsive design with TailwindCSS

## Project Structure

```
src/
├── components/
│   ├── accounts/     (Login, Register, Profile, Logout)
│   ├── chat/        (ChatRoom, Messages, Users)
│   └── layouts/     (Header, Theme, Error handling)
├── contexts/        (Authentication context)
├── services/        (API and Chat services)
├── utils/          (Helpers and utilities)
└── config/         (Firebase configuration)
```

## Environment Setup

Create a `.env` file in the frontend directory with your Firebase configuration:

```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

---

**Created by:** Rachi
**Last Updated:** January 2026
