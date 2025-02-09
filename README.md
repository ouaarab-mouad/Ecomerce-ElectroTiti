# Ecommerce-ElectroTiti

**Ecommerce-ElectroTiti** is a full-stack e-commerce platform built with **Next.js, React.js, TypeScript, and Node.js**, featuring a seamless shopping experience, secure authentication, and an **Admin Dashboard** for managing products, orders, and users.

This project is based on a template from [**Kuzma02**](https://github.com/Kuzma02) .

## About This Project

This project is a customized version of an original e-commerce template, tailored to match the needs of **ElectroTiti**, a store specializing in **phones, phone accessories, and women's accessories**. It is built to be fast, scalable, and user-friendly.

### Features

- Modern UI with Next.js & Tailwind CSS
- Secure Authentication using JWT
- Admin Dashboard for managing products, orders, and users
- Shopping Cart & Checkout functionality
- Product Listings with Search & Filters
- Wishlist Feature
- Fully Responsive Design for all devices

## Tech Stack

- **Frontend:** Next.js, React.js, TypeScript, Tailwind CSS
- **Backend:** Node.js, Express.js, MySQL
- **Auth:** JWT (or NextAuth if used)
- **Database Management:** Prisma ORM

## Installation & Usage

Follow these steps to set up the project:

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [MySQL](https://dev.mysql.com/downloads/installer/)
- (Optional) [HeidiSQL](https://www.heidisql.com) for database management

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/ouaarab-mouad/Ecomerce-ElectroTiti.git
   cd Ecomerce-ElectroTiti
   ```
2. Install dependencies:
   ```bash
   npm install  # or yarn install
   ```
3. Create a `.env` file in the root and add your database credentials:
   ```env
   DATABASE_URL="mysql://username:password@localhost:3306/electrotiti_db"
   NEXTAUTH_SECRET=your_secret_key
   NEXTAUTH_URL=http://localhost:3000
   ```
4. Navigate to the server folder:
   ```bash
   cd server
   npm install
   ```
5. Run Prisma migrations:
   ```bash
   npx prisma migrate dev
   ```
6. Insert demo data:
   ```bash
   cd utills
   node insertDemoData.js
   ```
7. Start the backend:
   ```bash
   cd ..
   node app.js
   ```
8. Open a new terminal for the frontend and run:
   ```bash
   npm run dev
   ```
9. Open **[http://localhost:3000](http://localhost:3000)** in your browser!

## Project Screenshots

### Home Page



### Shop Page



### Single Product Page



### Cart Page



### Checkout Page



### Admin Dashboard



## License & Credits

This project is based on an open-source e-commerce template. The original work was developed by **[Kuzma02](https://github.com/Kuzma02)**. All rights and credits go to the original author. ElectroTiti extends and customizes the project for specific business needs.

Open to contributions. Feel free to fork, create issues, or submit pull requests.

