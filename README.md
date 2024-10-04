# Full Stack Spotify Clone 🎧

A full-stack Spotify clone built with the latest technologies such as **Next.js 13.4**, **React**, **Stripe**, **Supabase**, **PostgreSQL**, and **Tailwind CSS**. This project demonstrates how to implement full-stack web applications using modern web development tools.

## Features
- **Authentication**: User authentication with Supabase.
- **Music Streaming**: Allows users to search, play, and control music.
- **Subscription Payments**: Integrates with **Stripe** for premium subscriptions.
- **Responsive Design**: Mobile-friendly UI built with Tailwind CSS.
  
## Tech Stack
- **Frontend**: Next.js 13.4, React, Tailwind CSS
- **Backend**: Supabase (PostgreSQL), Next.js API Routes
- **Payments**: Stripe integration for subscription payments

## Getting Started

### Prerequisites
- Node.js >= 16.x
- PostgreSQL
- Stripe account for payment integration
- Supabase account for database and authentication

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kenton-Enoid/Full-Stack-Spotify-Clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Full-Stack-Spotify-Clone
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   - Create a `.env.local` file in the root of the project and add the following:

     ```
     NEXT_PUBLIC_SUPABASE_URL=<your_supabase_url>
     NEXT_PUBLIC_SUPABASE_ANON_KEY=<your_supabase_anon_key>
     STRIPE_SECRET_KEY=<your_stripe_secret_key>
     ```

5. Run the development server:
   ```bash
   npm run dev
   ```

6. Open your browser and visit:
   ```
   http://localhost:3000
   ```

### Project Structure

```
.
├── components
├── pages
├── public
├── styles
├── utils
└── README.md
```

## Contributing
Feel free to submit issues or pull requests for improvements. Collaboration is welcome!

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
