# GlimmerStore 🛍️

A modern, fast, and fully responsive e-commerce storefront. This is the customer-facing side of the **Glimmer** ecosystem, designed for a smooth shopping experience from product discovery to checkout.

> [!IMPORTANT]
> This is the **Storefront** part of the project. To see the management dashboard that powers this store, visit [GlimmerAdmin](https://github.com/ibragmv/GlimmerAdmin).


## 🏗 Project Architecture
Glimmer is a decoupled e-commerce solution:
1. **GlimmerStore** (This repo): The high-performance shopping interface for users.
2. **[GlimmerAdmin](https://github.com/ibragmv/GlimmerAdmin)**: The central hub for inventory, orders, and business logic.

## ✨ Store Features
- **Dynamic Product Catalog:** Instant searching, filtering by categories, and sorting.
- **Interactive Shopping Cart:** Real-time updates and persistent storage for a seamless user journey.
- **Product Details:** High-quality image galleries, descriptions, and variant selection.
- **Optimized Checkout:** A streamlined flow designed for high conversion rates.
- **Mobile First:** Fully responsive design that looks stunning on every device.
- **SEO Ready:** Optimized for search engines to ensure maximum visibility.

## 🛠 Tech Stack
- **Runtime:** [Bun](https://bun.sh)
- **Frontend:** React / Next.js (Change if you use Vite/other)
- **Styling:** Tailwind CSS / Framer Motion (for animations)
- **State Management:** Zustand / Redux Toolkit
- **Data Fetching:** TanStack Query (React Query)
- **Language:** [TypeScript](https://www.typescriptlang.org)

## 🚀 Getting Started

Ensure you have [Bun](https://bun.sh) installed.

### 1. Clone the repository
```bash
git clone https://github.com/ibragmv/GlimmerStore.git
cd GlimmerStore
```

### 2. Install dependencies
```bash
bun install
```

### 3. Configure environment
Rename a `.env.example` file with your API endpoints:
```env
NEXT_PUBLIC_API_URL="your_admin_public_api"
```

### 4. Run development server
```bash
bun run dev
```

## 🔄 The Ecosystem
GlimmerStore is built to consume the API provided by the Glimmer backend/admin. It fetches real-time data managed via **GlimmerAdmin**, ensuring that stock levels, pricing, and new arrivals are always up to date for the customer.

## 📄 License
This project is licensed under the MIT License.

---
