# surplus
# SurplusLink 🍲

> Surplus meal tracking + hyperlocal redistribution.
> Rescue surplus meals. Feed the neighbourhood. Before the clock runs out.

**Live demo:** <your-link-here>

## Problem
Canteens, hostels, caterers and restaurants have edible leftover food,
while NGOs and shelters nearby go hungry. Cooked food is only safe for a
few hours, so timing and logistics are the real challenge.

## Solution
SurplusLink lets donors log surplus meals in seconds, starts a food-safety
timer, and matches the food to verified receivers and volunteers within
1-5 km, with OTP-verified pickup and delivery.

## Features
- Quick surplus logging with automatic safe-until timer
- Hyperlocal feed with distance and diet filters
- Colour-changing countdown (green, amber, red) and auto-expiry
- OTP-based pickup and delivery confirmation
- Live impact counters (meals, kg saved, CO2 avoided)

## Tech stack
**Prototype:** HTML5, CSS3, vanilla JavaScript, inline SVG
**Proposed production:** Flutter/React, Node.js, PostgreSQL + PostGIS,
Redis, WebSockets, Firebase Cloud Messaging

## How to run
1. Clone the repo: `git clone https://github.com/<username>/surpluslink.git`
2. Open `index.html` in any browser.

## Workflow
Donor posts surplus → timer starts → nearby match → receiver accepts
→ volunteer pickup with OTP → delivery confirmed → impact logged

## Future scope
- AI surplus prediction to reduce overproduction
- Route optimisation for volunteers
- WhatsApp bot and SMS fallback
- CSR impact certificates and reports

## Author
<Aditya Gupta>, <Iter Soa University/Gdg>
