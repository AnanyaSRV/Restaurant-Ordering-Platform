
# Restaurant Ordering Platform

A full-stack restaurant management and online ordering platform designed to streamline the dining experience for customers while simplifying restaurant operations. The application combines food ordering, reservations, order tracking, staff management, and kitchen workflows into a unified system.

## Overview

The Restaurant Ordering Platform provides a digital solution for restaurant operations, supporting customers placing orders and making reservations while enabling restaurant staff to manage menus, orders, and kitchen activities.

## Features

### Customer Experience
- Browse restaurant menus
- Explore food items and categories
- Place food orders
- Track order progress
- Make restaurant reservations
- Online payment integration

### Restaurant Management
- Menu management
- Order management
- Reservation management
- Staff dashboard
- Kitchen workflow management
- Order status updates

### Platform
- Full-stack web application
- Database-backed architecture
- Payment integration with Razorpay
- Responsive user interface
- Organized API architecture

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Full-stack web framework |
| React | User interface |
| TypeScript | Type-safe development |
| Prisma ORM | Database ORM |
| PostgreSQL | Database |
| Razorpay | Payment integration |
| Node.js | Runtime environment |
| Git & GitHub | Version control |

## Getting Started

### Prerequisites

- Node.js
- npm
- PostgreSQL
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/AnanyaSRV/Restaurant-Ordering-Platform.git
```

Navigate to the project directory:

```bash
cd Restaurant-Ordering-Platform
```

Install dependencies:

```bash
npm install
```

## Environment Configuration

Create a local environment file:

```text
.env
```

Configure the environment variables required by the application, including:

- PostgreSQL database connection
- Authentication configuration, if applicable
- Razorpay credentials
- Other application-specific settings

Never commit real passwords, API secrets, private keys, or payment credentials to GitHub.

## Database Setup

Configure your PostgreSQL database and ensure the database connection string is correctly set in your environment configuration.

Generate the Prisma client:

```bash
npx prisma generate
```

Apply database migrations:

```bash
npx prisma migrate dev
```

If the project includes seed scripts, follow the project's seed configuration to populate initial data.

## Run the Development Server

Start the application:

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## Project Structure

```text
Restaurant-Ordering-Platform/
├── app/
├── lib/
├── prisma/
├── public/
├── scripts/
├── .gitignore
├── package.json
├── package-lock.json
├── next.config.ts
├── prisma.config.ts
├── tsconfig.json
└── README.md
```

## Future Improvements

- Advanced restaurant analytics
- Enhanced order insights
- Expanded customer loyalty features
- Improved live order tracking
- Additional restaurant automation features

## Author

**Ananya SRV**

- GitHub: [@AnanyaSRV](https://github.com/AnanyaSRV)
- Repository: [Restaurant Ordering Platform](https://github.com/AnanyaSRV/Restaurant-Ordering-Platform)

---

Developed as a full-stack project exploring restaurant operations, online ordering, reservation workflows, database management, and payment integration.
