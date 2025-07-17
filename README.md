# Lodge Next.js Project

A modern web application built with [Next.js](https://nextjs.org), [React 19](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), and [Tailwind CSS](https://tailwindcss.com/).

## Project Structure

```
learning/lodge/
├── public/           # Static assets (icons, fonts, images)
├── src/
│   ├── app/          # Main app entry, routing, and layout
│   ├── components/   # Reusable UI components
│   ├── layout/       # Layout components (headers, footers, etc.)
│   ├── hooks/        # Custom React hooks
│   ├── helpers/      # Helper utilities
│   ├── data/         # Static/mock data
│   ├── services/     # API and service logic
│   ├── store/        # State management (e.g., Redux slices)
│   ├── styles/       # Global and modular styles
│   ├── utils/        # Utility functions
│   └── lib/          # Shared libraries and utilities
├── package.json      # Project metadata and scripts
├── next.config.ts    # Next.js configuration
├── tsconfig.json     # TypeScript configuration
└── ...
```

## Getting Started

Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Available Scripts

- `npm run dev`     – Start the development server (with Turbopack)
- `npm run build`   – Build for production
- `npm run start`   – Start the production server
- `npm run lint`    – Lint the codebase

## Key Files & Folders

- `src/app/page.tsx` – Main entry page (edit to update homepage)
- `src/components/`  – All reusable UI components
- `src/layout/`      – Layout components (e.g., header, footer)
- `src/store/`       – State management logic
- `src/lib/`         – Shared libraries and utilities
- `public/`          – Static assets served at root

## Customization & Contribution

- Add new pages in `src/app/` as per Next.js routing.
- Place shared UI in `src/components/`.
- Use `src/services/` for API logic.
- Add global styles in `src/app/globals.css` or modular styles in `src/styles/`.
- Add shared libraries or utilities in `src/lib/`.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)

---

Feel free to contribute or customize as needed!
