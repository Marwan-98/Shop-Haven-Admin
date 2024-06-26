# Full Stack E-Commerce + Dashboard & CMS

This project showcases a comprehensive full-stack e-commerce application complete with a dashboard and CMS. Built with modern technologies including Next.js 13, React, Tailwind CSS, Prisma, and MySQL, this application demonstrates robust functionalities for both users and administrators.
This repo is for the Dashboard & CMS, You can checkout the repo for the E-commerce website [here](https://github.com/Marwan-98/Shop-Haven-Store)

## Features

- **E-Commerce Platform**
  - User-friendly shopping experience
  - Product listings with detailed descriptions
  - Shopping cart and checkout process
  - Order management

- **Admin Dashboard**
  - Product management (CRUD operations)
  - Order tracking and management
  - User management
  - Sales analytics and reports

- **CMS (Content Management System)**
  - Manage website content dynamically
  - Add, edit, and remove content without code changes
  - Real-time updates

## Technologies Used

- **Frontend**
  - [Next.js 13](https://nextjs.org/)
  - [React](https://reactjs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)

- **Backend**
  - [Prisma](https://www.prisma.io/) - ORM for database interactions
  - [MySQL](https://www.mysql.com/) - Relational database management system

- **Deployment**
  - Vercel (for frontend hosting)
  - Planetscale (for database hosting)

## Getting Started

### Prerequisites

- Node.js
- MySQL

### Installation

1. Clone the repository:
   ```
    git clone git@github.com:your-username/Shop-Haven-Admin.git
   ```

2. Navigate to the project directory:
   ```
    cd Shop-Haven-Admin
   ```

3. Install dependencies:
    ```
        npm install
    ```

4. Set up the database:
    ```
        npx prisma migrate dev
    ```

5. Start the development server:
    ```
        npm run dev
    ```
    
### Usage

- Access the application at http://localhost:3000
- Default admin credentials can be set in the environment variables

### Environment 
```
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="Your Clerk public key"
    CLERK_SECRET_KEY="Your Clerk secret key"
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
    DATABASE_URL="Your planet scale database url"
    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="cloudinary cloud name"
    FRONTEND_STORE_URL="http://localhost:3000"
    STRIPE_KEY="Your Stripe key"
    STRIPE_WEBHOOK_SECRET="Your Stripe key"
```
