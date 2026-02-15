# Pillora Capital

## Project Description
Pillora Capital is a cutting-edge financial platform designed to cater to the unique needs of investors and entrepreneurs alike. Our mission is to redefine investment methodologies by blending traditional financial wisdom with modern technological innovations.

## Brand Context
Pillora Capital stands at the intersection of finance and technology. We believe in empowering our users by providing them with the tools and insights they need to make informed investment decisions. Our brand reflects reliability, expertise, and a forward-thinking approach to financial management.

## Core Philosophy
- **Clarity over hype**: We prioritize transparency and straightforward communication.
- **Structure over urgency**: We advocate for well-thought-out strategies rather than hasty decisions.
- **Trust before transactions**: Building relationships and trust is our foundation.

## Tech Stack
Our application is built using:
- **Next.js 14**: A React framework that enables server-side rendering and static site generation.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A superset of JavaScript that adds static types.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **PostgreSQL**: An open-source relational database.
- **Prisma**: An ORM for Node.js and TypeScript that simplifies database interactions.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/bikramandbetaal/pilloacapital.git
   cd pilloacapital
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```

## Environment Setup
Create a `.env` file in the root directory and set the necessary environment variables. You can refer to `.env.example` for guidance.

## Database Setup
To set up the database, run the following command:
```bash
npx prisma db push
```
This command will synchronize the database schema with your Prisma schema.

## Running Dev Server
To start the development server, use the following command:
```bash
npm run dev
```
Visit `http://localhost:3000` in your browser to see the application in action!