# Hanzi Strip

A Next.js application for processing Chinese characters (Hanzi), built on top of the AI SaaS Starter Kit template.

## Features

- **Modern Tech Stack:** Built with Next.js 15, React 19, and Tailwind CSS v4
- **AI Integration:** Ready for AI-powered Chinese text processing
- **Authentication:** NextAuth.js integration
- **Database:** PostgreSQL with Drizzle ORM
- **Payment:** Stripe integration ready
- **Modern UI:** Tailwind CSS with dark/light mode support

## Getting Started

We are using npm as our package manager.

> To use Yarn or any other package manager, delete the `package-lock.json` file and run the below commands using the package manager of your choice.

1. Install dependencies

   ```bash
   npm install
   ```

2. Rename `.env.example` to `.env` and set the environment variables

3. Development server

   ```bash
   npm run dev
   ```

   Your app template should now be running on [http://localhost:3000](http://localhost:3000).

   Additional commands:

   ```bash
   npm run build # Build the project
   npm run start # Start the production server
   ```

## Features

- [Next.js](https://nextjs.org) App Router
  - Advanced routing, SEO, and performance
  - React Server Components (RSCs) and Server Actions for server-side rendering
- [AI SDK](https://sdk.vercel.ai/docs)
  - Unified API for generating text and tool calls with LLMs
  - Supports OpenAI (default) and other model providers.
