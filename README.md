# Social Media Dashboard

A modern, full-featured social media application built by **Ruth Njoki** using React and Tailwind CSS. This project focuses on a premium user experience with smooth animations, robust theme management, and validated authentication flows.

## Key Features

### Authentication
- **Secure Login & Registration**: Fully validated forms using `react-hook-form` and `yup`.
- **User Feedback**: Toast notifications for success/error states.
- **Password Visibility**: Toggle to show/hide passwords.
- **Protected Routes**: Secure navigation using `GuestRoute` and `ProtectedRoute`.

### UI/UX & Theming
- **Robust Theme System**: Supports **Light**, **Dark**, and **System** modes. Persists via `localStorage` with instant switching.
- **Glassmorphism Navbar**: Floating "pill" design on scroll with GSAP animations and blur effects on desktop; sticky header with bottom navigation on mobile.
- **Premium Design**: Clean, modern aesthetics with `lucide-react` icons, soft shadows, and responsive layouts.

### Key Functionalities
- **Post Feed**: Infinite scrolling feed with post interactions.
- **Post Details**: Detailed view of posts with comments.
- **Create Post**: Interface to upload images and text.
- **Profile**: User profile page with dynamic data.
- **Settings**: Modal to manage appearance and user preferences.

## Tech Stack
- **Frontend**: React (Vite)
- **Styling**: Tailwind CSS, PostCSS
- **Animations**: GSAP (GreenSock), Framer Motion
- **State Management**: React Context API
- **Form Handling**: React Hook Form, Yup
- **Data Fetching**: TanStack Query (React Query), Axios
- **Icons**: Lucide React

## Project Structure
```
src/
├── assets/          # Images and static files
├── components/      # Reusable UI components (Navbar, Loader, etc.)
├── context/         # React Contexts (Auth, Theme)
├── features/        # Feature-based modules (Auth, Posts)
├── hooks/           # Custom hooks
├── layouts/         # Layout wrappers
├── pages/           # Page components (Home, Login, Profile, etc.)
└── index.css        # Global styles and Tailwind configuration
```

## Getting Started
1. **Install Dependencies**: `npm install`
2. **Run Development Server**: `npm run dev`
3. **Build for Production**: `npm run build`

---
Built with ❤️ by [Ruth Njoki](https://github.com/Wanjiruth)
