# Private Chat: A Privacy-First Real-Time Messaging System

Developed a high-performance, privacy-focused chat application using Next.js, Elysia, and Redis, designed for secure and ephemeral communication.
Implemented real-time messaging with ultra-low latency, enabling seamless live conversations between users.
Engineered automatic data self-destruction, ensuring all messages are securely wiped from servers within 10 minutes or instantly upon manual deletion.
Leveraged Redis for in-memory message handling and session management, significantly improving speed and real-time reliability.
Applied privacy-by-design principles to eliminate long-term data storage and minimize security risk.

## Demo Video

Watch a demonstration of the app's functionality here:

<p align="center">
  <a href="https://www.youtube.com/watch?v=mvqxe8_kDPc">
    <img src="docs/images/thumbnail.png" width="700" />
  </a>
</p>

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
