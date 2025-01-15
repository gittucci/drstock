# Project overview
Use this guide to build a complete web app for managing stock, inventory and supply chain of a company, using github 'InvenTree' model as  reference.

# Feature requirements
- Use Next.js, Shadcn, Lucid and Clerk for frontend
- Use Python for backend
- Use PostgreSQL for database
- Use Docker Desktop for containerization
- The app will running in a docker desktop 4.34 image
- Use Github Actions for CI/CD
- Use Stripe for payment processing
- Use Twilio for SMS notifications
- Use Google Maps API for location tracking
- Use Firebase for real-time data synchronization
- Use Azure Cognitive Services for image recognition
- Use OpenAI for natural language processing
- Have a nice UI
- when hover each product in the list, the product details will be shown
- frontend pages:
    - login page that redirects to the product list page
    - product list page
    - product register and update
- backend endpoints:
  - get product list
  - upsert product
  - delete product

# Relevant docs
github 'InvenTree' reference: https://github.com/inventree/InvenTree

# Current File structure
DRSTOCK/
├── drs_stock_control/
│   └── .next/
├── app/
│   ├── fonts/
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   └── ui/
│       ├── button.tsx
│       ├── card.tsx
│       └── input.tsx
├── lib/
├── node_modules/
├── requirements/
├── .eslintrc.json
├── .gitignore
├── components.json
├── next-env.d.ts
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.ts
└── tsconfig.json

# Rules
- All new components should be in /components and named like example-component.tsx unless otherwise specified
- All new pages should be in /app and named like example-page.tsx unless otherwise specified

