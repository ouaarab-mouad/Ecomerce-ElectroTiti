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

<h2>Project screenshots</h2>

<h3>Home page</h3>

![singitronic home page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a48c092d-1f19-4bae-a480-0b5862630e1c)

<h3>Shop page</h3>

![singitronic shop page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/1133effb-0511-40c6-aee5-119404c5af34)

<h3>Single product page</h3>

![singitronic single product page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/443ea3e2-4d32-4d15-aa3b-436cbae0eade)

<h3>Register page</h3>

![singitronic register page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/0052cc90-d61a-4a8c-b8d8-02cee1b45d13)

<h3>Login page</h3>

![singitronic logic page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/7a377bb3-330f-43a4-860f-400bf7aa0f97)

<h3>Search page</h3>

![singitronic search page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/384c7f55-16ee-4966-b612-a34f5506af51)

<h3>Wishlist page</h3>

![singitronic wishlist page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a20568d6-12fb-42e6-a5ef-583f6e79229a)

<h3>Cart page</h3>

![singitronic cart page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/b9d326be-342c-4f6a-af64-34794f6c39eb)

<h3>Checkout page</h3>

![singitronic checkout page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a458d931-9df2-4e3d-bf3f-702c1a3ba9e9)

<h3>Admin dashboard - All orders page</h3>

![singitronic admin orders page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/498b07f4-422c-46c5-b2e4-ed2a93306b7a)

<h3>Admin dashboard - All products page</h3>

![singitronic admin products page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/e26822ab-6c7e-4474-9161-288a5bb3476f)

<h3>Admin dashboard - All categories page<h3>

![singitronic admin categories page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/9e4a54d7-5bbb-4f1b-bdab-43c1079510e1)

<h3>Admin dashboard - All users page</h3>

![singitronic admin users page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/e14e8f2c-4377-42fd-b89b-d4868cc11b11)



## License

This project is based on an open-source e-commerce template. The original work was developed by **[Kuzma02](https://github.com/Kuzma02)**. All rights and credits go to the original author. ElectroTiti extends and customizes the project for specific business needs.

