# 🧩 Next.js UI Components Library

A reusable, production-ready collection of UI components built with **Next.js** and **Tailwind CSS**, including:

- **Billing Page**
- **Pricing Card**
- **Price Cards**

Perfect for SaaS apps, startups, and landing pages.

---

## 📦 Features

- ⚡ Built with Next.js 13+/App Router
- 💅 Styled using Tailwind CSS
- ♻️ Reusable and modular components
- 🌙 Fully responsive and dark mode-ready (optional)
- 🧪 Easy to extend or integrate into any project

---

## 📁 Components

### 1. `BillingPage`
A complete billing management layout, including:

- Subscription overview
- Plan selection
- Payment method section
- Invoice history (optional)

### 2. `PricingCard`
A standalone card component for showcasing a single pricing plan. Includes:

- Plan name
- Price
- Features list
- CTA button

### 3. `PriceCards`
A grouped component that displays multiple `PricingCard` instances in a responsive layout. Ideal for:

- Plan comparisons
- Pricing tables
- Highlighting a "most popular" option

---
# Inspiration

- [Biling Page](https://www.uidesigndaily.com/posts/figma-billing-page-payment-day-1585)

- [Pricing Card](https://www.uidesigndaily.com/posts/figma-pricing-card-day-1534)

- [Price Cards](https://www.uidesigndaily.com/posts/figma-pricing-card-day-1454)

## 🚀 Getting Started

### 1. Clone the repo

git clone https://github.com/yourusername/nextjs-ui-components.git

cd nextjs-ui-components

2. Install dependencies

npm install
# or
yarn install

3. Run the dev server

npm run dev
# or
yarn dev
Visit http://localhost:3000 in your browser to view the components.

🛠 Usage
You can import and use the components in your Next.js app like this:

import { BillingPage, PricingCard, PriceCards } from "@/components/ui";

export default function Home() {
  return (
    <main>
      <BillingPage />
      {/* Or use individual pricing cards */}
      <PriceCards />
    </main>
  );
}

🧱 Tech Stack
-Next.js

-Tailwind CSS

-TypeScript (optional but recommended)

🙌 Contributing
Pull requests and suggestions are welcome!
Please open an issue first to discuss what you would like to change.

📄 License
MIT © Krishna-2115

✨ Credits
Built with ❤️ by Krishna
