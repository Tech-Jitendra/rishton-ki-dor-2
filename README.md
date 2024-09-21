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




# RishtonKiDor

RishtonKiDor is a wedding website built with Next.js, TypeScript, and Tailwind CSS.

## Project Structure

```
RishtonKiDor/
├── components/
│   ├── Header.tsx
│   ├── Footer.tsx
│   ├── Navigation.tsx
│   └── ...
├── pages/
│   ├── index.tsx
│   ├── couple.tsx
│   ├── events.tsx
│   ├── rsvp.tsx
│   └── gallery.tsx
├── styles/
│   └── globals.css
├── public/
│   ├── images/
│   └── fonts/
├── lib/
│   └── utils.ts
├── types/
│   └── index.ts
├── next.config.js
├── tailwind.config.js
├── tsconfig.json
├── package.json
└── README.md
```

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/RishtonKiDor.git
   ```

2. Install dependencies:
   ```
   cd RishtonKiDor
   npm install
   ```

3. Run the development server:
   ```
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm run dev`: Runs the app in development mode
- `npm run build`: Builds the app for production
- `npm start`: Runs the built app in production mode
- `npm run lint`: Runs the linter to check for code style issues

## Technologies Used

- Next.js
- TypeScript
- Tailwind CSS
- React
- Node.js

## Features

- Responsive design
- Interactive gallery
- RSVP form with serverless functions
- Countdown timer to the wedding date
- Multilingual support (Hindi and English)

## Deployment

This project is set up for easy deployment on Vercel or Netlify. Follow their respective documentation for detailed deployment instructions.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

