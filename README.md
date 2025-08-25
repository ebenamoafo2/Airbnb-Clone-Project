# Airbnb Clone

## Project Overview

This project is a full-stack clone of Airbnb, designed to let users browse property listings, view detailed property information, and complete bookings. The main goals are to create an intuitive booking flow, ensure visual consistency, optimize for fast performance, and provide a mobile-first experience. The project is ideal for learning modern web development practices and scalable architecture.

## Tech Stack

- **Frontend:** React (Vite), React Router, React Query, Tailwind CSS, shadcn/ui
- **Backend:** Node.js (Express), Prisma ORM, Zod (validation)
- **Database:** PostgreSQL (Neon/Supabase/Render Postgres)
- **Authentication:** JWT access and refresh tokens (httpOnly cookies), social login (planned)
- **Image Storage:** Cloudinary (S3-compatible planned)
- **Payments:** Stripe (test mode)
- **Deployment:** Vercel/Netlify (frontend), Render/Railway/Fly.io (API), Neon/Supabase (DB)
- **CI/CD:** GitHub Actions (lint → test → build → deploy)


## UI/UX Design Planning



- **Intuitive Booking Flow:** Ensure users can easily search, view, and book properties with minimal friction.
- **Visual Consistency:** Maintain a cohesive look and feel across all pages and components.
- **Fast Performance:** Optimize for quick load times and smooth interactions.
- **Mobile-First:** Design for responsiveness and accessibility on all devices.

### Key Features to Implement

- Property search and filtering
- Detailed property viewing
- Secure checkout process
- User authentication and account management

### Primary Pages

| Page                   | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Property Listing View  | Grid display of available properties with filters for location, dates, etc. |
| Listing Detailed View  | Complete property details, images, amenities, reviews, and booking form.    |
| Simple Checkout View   | Streamlined payment and booking confirmation process.                       |

### Color Styles

- **Primary:** #FF5A5F
- **Secondary:** #008489
- **Background:** #FFFFFF
- **Text:** #222222
- **Secondary Text:** #717171

### Typography

- **Font Family:** Circular (fallback: Inter, Arial, sans-serif)
- **Font Weight:** 
  - Headings: Bold (700)
  - Body: Medium (500), Book (400)
- **Font Size:** 
  - Headings: 24px–32px
  - Body: 16px
  - Secondary Text: 14px

### Importance of Identifying Design Properties

Identifying design properties such as color styles and typography in a mockup is crucial for maintaining brand consistency, visual hierarchy, and accessibility. Clear documentation of these properties ensures that developers and designers can accurately translate the design into code, resulting in a cohesive and professional user interface. It also streamlines collaboration, reduces ambiguity, and helps deliver a polished product that meets user expectations.

## Project Roles and Responsibilities

- **Project Manager:**  
  Oversees the project timeline, coordinates team members, manages deliverables and resources, and ensures the project stays on track and meets deadlines.

- **Frontend Developers:**  
  Implement UI components, ensure responsive design, integrate APIs, and maintain code quality. Their work delivers a seamless, user-friendly interface for all users.

- **Backend Developers:**  
  Build APIs, manage the database schema, implement business logic, and ensure security and scalability. They provide reliable and efficient backend services for the application.

- **Designers:**  
  Create mockups, maintain the design system, ensure UX quality, and collaborate on branding. Designers guarantee a visually appealing and intuitive user experience.

- **QA/Testers:**  
  Write test cases, perform manual and automated testing, report bugs, and verify fixes. Their efforts maintain high product quality and minimize defects.

- **DevOps Engineers:**  
  Manage deployment, CI/CD pipelines, server infrastructure, and monitor system health. They ensure smooth releases and reliable application uptime.

- **Product Owner:**  
  Define requirements, prioritize features, represent stakeholder interests, and validate deliverables. The product owner aligns the product with business goals and user needs.

- **Scrum Master:**  
  Facilitate agile processes, remove blockers, organize meetings, and support team collaboration. The scrum master fosters an efficient, collaborative, and high-performing team dynamic.

## UI Component Patterns

This section outlines the reusable UI components planned for the Airbnb Clone, based on the [Figma design](https://www.figma.com/design/E2BRqdPcKkrnX6hLGPto8Z/Project-Airbnb?node-id=1-4&p=f&t=asmdI7OxfZ21cglv-0). These patterns ensure consistency, scalability, and maintainability across the application.

### Planned Components

- **Navbar:**  
  A responsive navigation bar featuring logo, search input, navigation links, and user profile actions. Adapts for mobile and desktop layouts.

- **Property Card:**  
  Displays property image, title, location, price, rating, and quick actions (e.g., save, view details). Used in property listing grids.

- **Footer:**  
  Contains site links, contact information, social media icons, and legal disclaimers. Stays consistent across all pages.

- **Search Filter Panel:**  
  Allows users to filter properties by location, price, dates, amenities, and more. Collapsible on mobile devices.

- **Booking Form:**  
  Collects guest details, dates, and payment information. Includes validation and error handling.

- **Image Gallery:**  
  Interactive carousel for property images, supporting swipe and zoom features.

- **Review List:**  
  Displays user reviews with ratings, avatars, and timestamps.

- **Modal/Dialog:**  
  Used for login/signup, booking confirmation, and alerts. Accessible and reusable.

- **Button Variants:**  
  Primary, secondary, and icon buttons for consistent actions throughout the UI.

These components will be built with reusability and accessibility in mind, following the design system defined in Figma