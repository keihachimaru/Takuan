# Takuan

**Description:** AI-powered pantry coordinator that bridges the gap between curated recipes and current inventory. It eliminates the "What can I cook right now?" decision fatigue.

**Features:**
- Pantry management (add/remove/track items with expiry dates)
- Recipe saving from any source (manual input, URL parsing, Instagram/TikTok/YouTube import)
- Smart recipe matching (shows which saved recipes you can make RIGHT NOW)
- Unused ingredient alerts (pantry items not used in any saved recipe)
- Smart shopping list (auto-removes items you already have)
- Barcode scanner for pantry items
- Recipe collections and tags
- Meal planning calendar
- Nutritional tracking per recipe
- Export shopping list to WhatsApp

**Stack:** React Native, TypeScript, NestJS, PostgreSQL, Supabase, OpenAI API (recipe parsing), TailwindCSS, Expo, Vercel

## 10-Hour Session Plan

**Hours 1-2: Project setup**

- Expo + React Native init
- NestJS backend scaffold
- Supabase database setup
- Auth (email or Google OAuth)

**Hours 3-4: Pantry module**

- Pantry item CRUD (name, quantity, unit, expiry)
- Simple list UI
- Add/edit/delete items

**Hours 5-6: Recipe module**

- Recipe CRUD (title, ingredients, steps, source URL)
- Manual recipe input UI
- Tag system

**Hours 7-8: Matching engine**

- Algorithm: compare recipe ingredients vs pantry items
- "Can make now" filter
- "Missing X ingredients" filter
- Unused pantry items view

**Hours 9-10: Shopping list**

- Generate shopping list from recipe
- Auto-subtract pantry items already owned
- Export/share list