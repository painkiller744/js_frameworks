# NEXUS — Premium Tech Store

A Vue 3 single-page application for browsing and purchasing electronics.

## Tech Stack
- **Vue 3** with Composition API
- **Vue Router 4** — client-side routing
- **Vuex 4** — global state (cart, saved items, search)
- **Vite** — build tooling

## Project Structure
```
src/
- assets/        # CSS, SVG icons
- components/    # NavBar, CategoryBrowser, SiteFooter
- views/         # HomeView, CategoryView, ProductView, CartView, SavedView
- router.js      # Vue Router config
- store.js       # Vuex store
- api.js         # Backend fetch helpers
- main.js        # App entry point
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
```
apple-store-backend-build/package.json ("serve ...") -> ("serve": "cross-env DATABASE_URL=file:../prisma/dev.db node dist/index.js")
```

Open http://localhost:5173
