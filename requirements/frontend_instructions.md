# Project overview
Use this guide to build a complete web app for managing stock, inventory and supply chain of a company, using github 'InvenTree' model as  reference.

# Feature requirements
- Use Next.js, Shadcn, Lucid and Clerk for frontend
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
    - login page that redirects to the products page
    - products page that redirects to the entries page and exits page
    - entries page that redirects to the suppliers page
    - exits page that redirects to the custommers page
    - suppliers page
    - custommers page

# Current File structure
DRSTOCK/
├── backend/
│   ├── .env.local
│   ├── .eslintrc.json
│   ├── .gitignore
│   ├── components.json
│   ├── middleware.ts
│   ├── next.config.mjs
│   ├── next-env.d.ts
│   ├── package-lock.json
│   ├── package.json
│   ├── postcss.config.mjs
│   ├── README.md
│   ├── tailwind.config.ts
│   └── tsconfig.json
├── frontend/
│   ├── .next/
│   ├── app/
│   │   ├── fonts/
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   └── ui/
│   │       ├── button.tsx
│   │       ├── card.tsx
│   │       └── input.tsx
│   ├── lib/
│   ├── node_modules/
│   ├── requirements/
│   ├── .eslintrc.json
│   ├── .gitignore
│   ├── components.json
│   ├── next-env.d.ts
│   ├── next.config.mjs
│   ├── package-lock.json
│   ├── package.json
│   ├── postcss.config.mjs
│   ├── README.md
│   ├── tailwind.config.ts
│   └── tsconfig.json
└── requirements/
    ├── app_instructions.md
    └── frontend_instructions.md
    ├── mockup_customers.png
    ├── mockup_entries.png
    ├── mockup_exits.png
    ├── mockup_products.png
    └── mockup_suppliers.png

# Rules
- All new components should be in /components and named like example-component.tsx unless otherwise specified
- All new pages should be in /app and named like example-page.tsx unless otherwise specified

