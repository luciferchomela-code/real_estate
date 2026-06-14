# Real Estate Marketplace

A modern full-stack Real Estate Marketplace built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The platform allows users to browse, search, create, and manage property listings with a clean and responsive user experience.

## Features

### Authentication & Authorization

* Secure user registration and login using JWT authentication.
* Google Sign-In integration with Firebase OAuth.
* Protected routes and user-specific property management.

### Property Management

* Create, update, and delete property listings.
* Upload multiple property images.
* View detailed information for each property.
* Manage personal listings through a dedicated profile dashboard.

### Advanced Search & Filtering

* Search properties by name or keyword.
* Filter listings by Rent or Sale.
* Filter by amenities such as Parking and Furnished status.
* Sort listings by Price or Latest Added.

### Modern User Experience

* Fully responsive design for desktop, tablet, and mobile devices.
* Fast client-side routing with React Router.
* State management using Redux Toolkit.
* Clean and intuitive user interface built with Tailwind CSS.

## Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* Redux Toolkit
* React Router DOM
* Firebase

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Tokens (JWT)
* bcryptjs

## Getting Started

### Prerequisites

* Node.js installed on your machine
* MongoDB Atlas account or local MongoDB instance
* Firebase project for Google Authentication and Image Storage

### Installation

1. Clone the repository:

```bash
git clone https://github.com/luciferchomela-code/real_estate.git
cd real_estate
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables for MongoDB, JWT, and Firebase.

4. Start the development server:

```bash
npm run dev
```

5. Start the backend server:

```bash
npm start
```

## Project Highlights

* JWT-based authentication system
* Google OAuth login with Firebase
* CRUD operations for property listings
* Image upload functionality
* Advanced property search and filtering
* Responsive and modern UI
* Scalable MERN architecture
