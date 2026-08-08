# nutriplan-project-
NutriPlan is a React-based meal planning and nutrition app. Users can search recipes (from a local curated library plus a live TheMealDB API integration for real-time results), filter by diet and cuisine, view detailed nutrition breakdowns, plan meals on a weekly calendar, and auto-generate a grocery list. It also shows real-time weather 
# NutriPlan

A meal planning & nutrition app built with React + Vite.

## Features
- Recipe search with diet/cuisine filters (local library)
- Live recipe search via TheMealDB API (real-time, no key needed)
- Real-time weather via Open-Meteo API with meal suggestions
- Recipe detail pages with nutrition charts
- Weekly meal planner + auto-generated grocery list
- Favorites (saved in localStorage)
- Loading and error states handled gracefully throughout

## Run locally
\`\`\`bash
npm install
npm run dev
\`\`\`

## Build
\`\`\`bash
npm run build
\`\`\`

## Tech Stack
React 18, Vite, Tailwind CSS, Recharts, React Router
