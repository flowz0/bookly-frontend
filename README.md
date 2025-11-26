# Bookly Frontend

![Bookly Logo](./public/logo.png)

**Bookly** is a modern, web-based SaaS platform for booking, lead management, and customer relationship management (CRM). This repository contains the **frontend** application built with **Next.js (App Router), TypeScript, and Tailwind CSS**.

The frontend allows business owners to embed booking and lead capture widgets on their websites, manage leads, bookings, and customers from a central dashboard, and interact seamlessly with the backend API.

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Scripts](#scripts)
- [Environment Variables](#environment-variables)
- [License](#license)

---

## Demo

Coming soon: [Live Demo](https://www.google.com/)

---

## Features

- User authentication and business isolation  
- Embeddable lead capture and booking forms  
- Dashboard with Leads, Bookings, and Customers modules  
- CRUD operations for leads, bookings, and customers  
- Settings for business info and API keys  
- Fully responsive and accessible design  
- Scalable architecture for multiple businesses  

---

## Tech Stack

**Frontend**:

- [Next.js (App Router)](https://nextjs.org/) – React framework for server-side rendering and routing  
- [TypeScript](https://www.typescriptlang.org/) – Type-safe JavaScript  
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework  
- [Axios](https://axios-http.com/) – HTTP client for API requests  
- [React Query / SWR](https://react-query.tanstack.com/) – (Optional) Data fetching and caching  

**Other Tools**:

- ESLint & Prettier – Code quality and formatting  
- Vercel – Deployment platform  

---

## Getting Started

### Prerequisites

- Node.js >= 18.x  
- npm or yarn  
- Access to backend API (Bookly backend repository)

### Installation

1. Clone the repository:

git clone https://github.com/flowz0/bookly-frontend.git
cd bookly-frontend
Install dependencies:

```bash
npm install
# or
yarn install
```
Create a .env.local file in the root directory:

```env
NEXT_PUBLIC_API_URL=https://api.bookly.com
NEXT_PUBLIC_EMBED_KEY=your-public-key
```

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open http://localhost:3000 to view the app.

### Project Structure
```php
bookly-frontend/
├─ app/                  # Next.js App Router pages & layouts
│  ├─ dashboard/         # Dashboard routes (leads, bookings, customers)
│  ├─ auth/              # Authentication pages (login, signup)
│  └─ embed/             # Embeddable widgets
├─ components/           # Reusable React components
├─ hooks/                # Custom React hooks
├─ context/              # React context providers
├─ utils/                # Utility functions
├─ public/               # Static assets (images, icons)
├─ styles/               # Global CSS / Tailwind config
├─ types/                # TypeScript types
└─ .env.local            # Environment variables
```

### Scripts
| Command |	Description |
| ------- | ----------- |
| npm run dev	| Start the development server |
| npm run build | Build the production app |
| npm run start | Run the production build locally |
| npm run lint | Run ESLint checks |
| npm run format | Format code with Prettier |


### Environment Variables
| Variable | Description |
| -------- | ----------- |
| NEXT_PUBLIC_API_URL |	URL of the Bookly backend API |
| NEXT_PUBLIC_EMBED_KEY	| Public API key for the embeddable widget |

### License
This project is licensed under the MIT License. See LICENSE for details.

### Contact
Billy Flowers – billylflowers@gmail.com
