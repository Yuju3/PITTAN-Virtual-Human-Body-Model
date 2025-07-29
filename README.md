July 28th 2025

Eliot Lee

eliothoonlee@gmail.com

PITTAN Intern Summer 2025

This is a basic UI for the Virtual Human Body Model being developed by PITTAN.

The page.tsx launches the VirtualBodyInterface.tsx component.

The webpage is composed of a human body model, as well as interactive buttons on the model. When either the buttons on the model or the tabs below the model are clicked, a stat-tab will show on the right. The tab itself will vary depending on which button was clicked. Currently, there are 5 buttons, which are Sleep, Heart, Grip, Skin, and Sweat. This is only the front-end, as the back-end/server side has not yet been created.

## Things to work on/expand
- Create and integrate a backside/server that holds userdata

- Integrate an actual 3D human body model that can be viewed from any angle, zoomed in, etc

- Have a system for user login

- Improve the current UI design

- Integrate an AI Companion that gives suggestions/health advice

- Create a user survey to collect other health related data

- Integrate a mental health section

- Audio analyzation for vocal related conditons

- Sensor connection integration

- Integrate AI skin condition analyzer

To run the local host, have node js downloaded, open up the terminal in the src folder, run the command "npm run dev". Then open http://localhost:3000 in a browser. Make sure not to have any extensions running.

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
