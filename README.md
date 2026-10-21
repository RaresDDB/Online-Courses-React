# Online Courses — Frontend

**Online Courses** is a React-based web application designed for browsing and managing online courses across different technology and programming topics.

This repository contains the **frontend**, developed with **React, JavaScript, and Material UI**. It provides user registration, login, course exploration, and personalized course management through a component-based interface.

## Tech stack

- **React** — component-based user interface
- **JavaScript** — frontend application logic
- **Material UI** — UI components and styling
- **React Router** — client-side navigation and protected routes
- **React Context API** — authentication and application state management
- **Local Storage** — client-side persistence of user and course data
- **Notistack** — notifications and user feedback
- **Create React App** — development and build tooling

## Key features

### Authentication and user management

- User registration and login.
- Email uniqueness validation during registration.
- Authentication state management using React Context API.
- Protected routes accessible only to authenticated users.
- Conditional navigation based on authentication status.

### Course discovery and management

- Browse a catalog of 12 online courses covering programming, web development, cybersecurity, and other technology topics.
- View course details, descriptions, categories, and durations.
- Explore courses through interactive cards.
- Add and remove courses from a personalized list.
- Access a dedicated "My Courses" page.
- Persist selected courses using browser Local Storage.

### User interface

- Reusable React components for navigation, course cards, and page layouts.
- Responsive course grid using Material UI.
- Dynamic navigation using React Router.
- Success and information notifications for course management actions.

## Architecture

The frontend is a **single-page application (SPA)** built with React.

The application uses React Router for navigation, Context API for shared state management, and Local Storage for client-side data persistence.

```text
      React + Material UI
               |
         React Router
               |
        React Context API
               |
          Local Storage
```

The project is implemented entirely on the client side and does not require a separate backend or database server.

## Running locally

Prerequisites include **Node.js**, **npm**, and **Git**.

Clone the repository:

```bash
git clone https://github.com/RaresDDB/cursuri-online-website-react.git
```

Navigate to the project directory:

```bash
cd cursuri-online-website-react
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application runs locally at `http://localhost:3000`.

To create a production build:

```bash
npm run build
```

## Project context

Online Courses was developed as a frontend project focused on **React development, client-side routing, state management, and interactive user interfaces**.

The project provided practical experience in:

- React components and hooks
- JavaScript application development
- React Context API
- Client-side routing and protected routes
- Local Storage integration
- Material UI and responsive layouts
- User interaction and state management

**Author:** Costin-Rareș-Călin Pârlea

> This repository showcases a client-side educational platform prototype. Authentication and data storage are implemented locally for demonstration purposes, without a production backend.
