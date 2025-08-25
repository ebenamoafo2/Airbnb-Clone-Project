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


## UI/UX Design Plan

Design goals (from brief): intuitive booking flow; visual consistency; fast; mobile‑first.

## Core Features

- **Property Listing View:** Grid display of available properties with filters (location, dates, guests, price, type, rating).
- **Listing Detail View:** Gallery, amenities, map, reviews, availability calendar, and booking form.
- **Checkout:** Contact info, price breakdown, payment, and confirmation screen.
- **Authentication:** Sign in/up, reset password.
- **Account:** Trips, favorites, profile (phase 2: host dashboard).

---

## Primary Colors & Typography

**Colors**
- Primary: `#FF5A5F`
- Secondary: `#008489`
- Background: `#FFFFFF`
- Text: `#222222`
- Muted: `#717171`

**Typography**
- Font: Circular (or Inter as drop-in)
- Base: 16px
- Headings: 24–32px

---

## Component Library (Reusable Patterns)

**Layout**
- Navbar
- Footer
- Container
- Grid
- Breadcrumbs

**Inputs**
- TextField
- Select
- DateRangePicker
- Counter
- Checkbox
- Radio
- Slider

**Data Display**
- PropertyCard
- Rating
- Badge
- PriceTag

**Feedback**
- Toast
- Spinner
- EmptyState
- Modal

**Commerce**
- PriceBreakdown
- BookingForm
- PaymentForm