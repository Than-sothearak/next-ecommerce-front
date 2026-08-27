# Next E-Commerce Frontend

A full-featured e-commerce web application built with Next.js, React, Tailwind CSS, MongoDB, and Stripe, designed to provide customers with a modern online shopping experience.

The application includes product browsing, shopping cart management, user authentication, checkout, online payment integration, responsive layouts, and interactive UI components. It uses MongoDB/Mongoose for data management, NextAuth for authentication, and Stripe for secure online payments.

## Features

- 🛍️ Product browsing and product details
- 🛒 Shopping cart management
- 👤 User authentication with NextAuth
- 💳 Stripe online payment integration
- 📦 Checkout and order workflow
- 🔐 User account functionality
- 🔔 Toast notifications
- 🎨 Responsive UI with Tailwind CSS
- ✨ Smooth animations with Framer Motion
- 🖼️ Product and image presentation
- 📱 Mobile-friendly design
- 🗄️ MongoDB and Mongoose integration
- ⚡ API communication with Axios
- 🎞️ Product sliders and carousels

## Tech Stack

- **Next.js 13**
- **React 18**
- **JavaScript**
- **Tailwind CSS**
- **MongoDB**
- **Mongoose**
- **NextAuth**
- **Stripe**
- **Axios**
- **Framer Motion**
- **React Slick**
- **React Icons**
- **React Hot Toast**

## Environment Variables

Create a `.env.local` file in the project root:

```env
MONGODB_URI=

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

PUBLIC_URL=http://localhost:3000
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
