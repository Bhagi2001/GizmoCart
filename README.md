# GizmoCart Sri Lanka 🇱🇰

A modern e-commerce platform for Sri Lanka, built with Next.js, featuring electronics, gadgets, and tech products with island-wide delivery.

## Features

- 🛒 Full-featured shopping cart
- 💰 LKR (Sri Lankan Rupees) currency
- 📍 Sri Lankan address format (Districts, Provinces, Postal Codes)
- 📱 Responsive design for mobile and desktop
- 🚚 Island-wide delivery support
- 👤 User and Seller dashboards
- 🎨 Modern UI with Tailwind CSS

## Getting Started

First, install the dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Sri Lankan Localization

This project is specifically designed for the Sri Lankan market with:

- **Currency**: LKR (Sri Lankan Rupees) with proper formatting
- **Contact**: Sri Lankan phone numbers (+94 format)
- **Address**: Districts, Provinces, and Postal Codes
- **Delivery**: Island-wide shipping to all provinces (Western, Central, Southern, etc.)
- **Local Context**: References to Colombo, Kandy, Galle, and other major cities

## Project Structure

```
gizmocart/
├── app/              # Next.js app directory
├── components/       # Reusable React components
├── context/          # React Context for state management
├── assets/           # Images and product data
└── public/           # Static assets
```

## Environment Variables

Create a `.env.local` file with:

```
NEXT_PUBLIC_CURRENCY=LKR
```

## Tech Stack

- **Framework**: Next.js 15.1.6
- **Styling**: Tailwind CSS
- **UI**: React 19
- **Notifications**: React Hot Toast

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

**Made for Sri Lanka 🇱🇰** | Island-wide delivery available
