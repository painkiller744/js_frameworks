# NEXUS — Premium Tech Store

A Vue 3 single-page application for browsing and purchasing electronics.

## Tech Stack
- **Vue 3** with Composition API
- **Vue Router 4** — client-side routing
- **Vuex 4** — global state (cart, saved items, search)
- **Vite** — build tooling

## Features
- Browse products by category
- Search across product names
- Sort by price and rating
- Add/remove items from cart with quantity controls
- Save products for later
- Detailed product page with specs and reviews

## Project Structure
```
src/
├── assets/        # CSS, SVG icons
├── components/    # NavBar, CategoryBrowser, SiteFooter
├── views/         # HomeView, CategoryView, ProductView, CartView, SavedView
├── router.js      # Vue Router config
├── store.js       # Vuex store
├── api.js         # Backend fetch helpers
└── main.js        # App entry point
```

## Setup
```bash
# 1. Start backend first (apple-store-backend, port 1452)
cd apple-store-backend-build
npm install
npm run serve

# 2. Start frontend
cd nexus
npm install
npm run dev
```

Open http://localhost:5173
