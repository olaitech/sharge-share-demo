ROLE
You are a senior frontend engineer. Build a DEMO-ONLY UX prototype for “Sharge Share”.

CONTEXT
Sharge Share is a concept marketplace where private EV charger owners can rent out home chargers.
This demo is only for showcasing UX on a portfolio website (FutureBrief). No real backend.

HARD RULES (non-negotiable)
- Next.js App Router + TypeScript + Tailwind CSS
- Frontend only: NO backend, NO database, NO auth, NO payments
- Use mock data only stored in code (/lib/mock-data.ts)
- Mobile-first and responsive
- Keep dependencies minimal (no UI kits)
- Provide complete file tree + full code for each file
- Output code with FILE PATH headers (example: FILE: app/demo/sharge-share/page.tsx)

ROUTES (must exist)
1) /demo/sharge-share
   - Hero section
   - Short explanation
   - CTA: “Explore chargers”
   - Badge: “Concept demo”

2) /demo/sharge-share/chargers
   - List of chargers
   - Search input
   - Simple filters (price, availability)

3) /demo/sharge-share/chargers/[id]
   - Charger detail page
   - Availability preview
   - CTA: “Book”

4) /demo/sharge-share/booking/confirm
   - Summary (charger, time, estimated price)
   - Fake confirmation message

UI STYLE
- Dark minimal UI
- Subtle glass panels
- Soft borders
- Clean typography
- Consistent header with back button on inner pages

MOCK DATA
Create 6 chargers with:
- id
- name
- city/area
- pricePerHour
- rating
- availability (example: “Today 18:00–22:00”)
- distanceKm

Do not use external images.
Use simple gradient blocks as placeholders.

COPY
English only.
Short, neutral, product-like copy.
Mention “Demo / mock data” subtly.

DELIVERABLE
Generate code that can be dropped into an existing Next.js App Router project with Tailwind already configured.
Start by listing the file tree, then output each file with its full contents.
