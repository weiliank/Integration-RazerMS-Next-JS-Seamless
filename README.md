
# Next JS Framework Seamless Payment - Checkout Page

Please refer to the RMS Seamless Integration docs if you need any further options.

https://github.com/RazerMS/Integration-RazerMS_JavaScript_Seamless_Integration/wiki/Latest-Razer-Merchant-Services-Seamless-Integration-(non-PCI)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) and [`Tailwind CSS`](https://tailwindcss.com/).

## Getting Started
First, clone the repo and run `npm init` to install the necessary packages. Then, edit the .env.local first based on your merchant ID and environment:
```
ENVIRONMENT=SANDBOX
MERCHANTID=merchant_id_here
VERIFY_KEY=merchant_verify_key
```

Finally, run the development server:


```bash
npm run dev
```

`Note`: You can change the port number here:` "dev": "next -p 8080"` under `package.json` file.

Open [http://localhost:8080](http://localhost:8080) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.


[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:8080/api/hello](http://localhost:8080/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!