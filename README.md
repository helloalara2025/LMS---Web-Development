# Learning Management System (LMS)

<img width="1602" height="512" alt="Screenshot 2025-11-11 at 12 56 19" src="https://github.com/user-attachments/assets/c35ab3a7-453b-428b-a1fc-96077f3a6e86" />

# Summary
  - This project is a **web-based Learning Management System** inspired by platforms like Canvas, built with **React**, **Next.js**, and **Node.js**.  
  - It was developed to strengthen full-stack development skills and experiment with modern front-end patterns such as component-based architecture 
  - The goal of this project is to create a scalable, responsive learning platform where users can view courses, assignments, and progress dashboards in an       intuitive interface.
    
# Core Features
- **Component-based UI:** Modular React components for flexibility and reusability.  
- **Server-Side Rendering:** Optimized performance and SEO using Next.js.  
- **Dynamic Routing:** Clean navigation between course pages, dashboards, and assignments.  
- **State Management:** Implemented with React hooks and context for predictable UI behavior.  
- **Secure Data Flow:** Integration between front-end components and backend APIs for authentication and content delivery.  
- **Responsive Design:** Adapts seamlessly across desktop and mobile devices.

# Architecture Overview

## Front-End — React / Next.js

- **Pages**  
  Each major view (Dashboard, Courses, Assignments) is implemented as a separate Next.js page.  
  Server-side rendering ensures data loads efficiently while maintaining clean routes.  

- **Components**  
  Shared UI elements such as navigation bars, progress bars, and course cards are modularized for reusability.  

- **State Management**  
  Context and hooks are used for global state, authentication, and loading management.  

## Back-End — Node.js / API Layer

- Handles user authentication and data retrieval.  
- Simulates a database layer for course and assignment information.  
- Ensures a clean separation between logic, presentation, and data handling.  
