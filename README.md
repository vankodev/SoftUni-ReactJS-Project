# Final Exam Project for SoftUni ReactJS Course

## Overview

This project is a full-stack web application built with React.js, leveraging technologies like Vite, React Hooks, and Context API. It's designed as a full-fledged web application with authentication, CRUD operations, and dynamic routing, offering both public and private user experiences.

[Live Demo](https://softuni-reactjs-project-1234.web.app)

## Application Structure

### Public Features

- **Homepage:** Provides an overview of the platform.
- **Product Catalog:** Displays all products with basic details, accessible to all users.
- **User Authentication:** Login and registration forms for user access.

### Private Features (Authenticated Users)

- **Comment Management:** Users can add, edit, and delete comments on product pages.
- **Admin Features:** Admins can create, edit, and delete products through a secure interface.

## Features

- **Dynamic Product Display:** Utilizes React's `useEffect` hook for API calls to fetch and display products.
- **Product Detail Pages:** Each product has a dedicated page with detailed information and user comments.
- **User Interaction:** Registered users can add, edit, or delete comments on product pages.
- **Admin Capabilities:** Special privileges for admins to create new products and to edit product specifications or delete the product through a modal interface.
- **Authentication:** Robust system allowing user account creation and login with different privileges.

## Technical Highlights

- **Form Validation and Error Handling:** Ensures a smooth user experience and robust application performance.
- **Dynamic Pages and Views:** Incorporates at least three dynamic pages, including product catalog and detail views.
- **Component-Based Architecture:** Structured with separate components and CSS files for modularity and maintainability.
- **Data Storage:** Product images and data are stored securely on Google Cloud.
- **Deployment:** Fully deployed [live demo](https://softuni-reactjs-project-1234.web.app) on Firebase.

## Advanced Features

- **Custom `useForm` Hook:** Enhances forms handling process.
- **Local Storage Management:** Efficient handling of authentication tokens for secure and persistent user sessions.
- **Auth Guard:** Route guards based on user privileges for enhanced security and user experience.
- **Reusable Services:** Efficient, reusable services for server communication, optimizing data fetching and manipulation.
- **AuthContext:** Streamlined user state management across the application using AuthContext.

## UI/UX Design
- **Styling:** Demonstrates strong UI creation skills with CSS, focusing on an intuitive and responsive design.

## Setup Instructions
1. **Run the Local Server:**
   ```bash
   cd server
   node .\server.js
   ```
2. **Start Client Development:**
   ```bash
   cd client
   npm run dev
   ```

## Deployment
- **Build and Deploy Client:** 
  ```bash
  npm run build 
  firebase deploy
  ```
- **Deploy Server Functions:**
  ```bash
  firebase deploy --only functions
  ```
