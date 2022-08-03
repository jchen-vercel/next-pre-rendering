This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Purpose of this repository is to showcase a bunch of the different cool rendering strategies available within Next.js (static generation, incremental static regeneration, on-demand incremental static regeneration, client side rendering and server side rendering).

## Getting Started

To test rendering strategies start with:
npm run start
npm run serve-json --watch db.json --port 4000

## Rendering Strategy Legend

**/posts/** is used to showcase **static generation** on a static path.

**/posts/[postid].js** is used to showcase **static generation with dynamic routes (getStaticPaths)**.

**/news/** is used to showcase **server side rendering**

**/products/** is used to showcase **incremental static regeneration** with a set revalidation period.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
