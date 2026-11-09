# Awesome-Booking-Reservation-Management

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **"Zoho Reservations" is not the product name**, and **the open-source side is genuinely substantive** for this category.



## The data problems



**"Zoho Reservations" is actually Zoho Bookings.** The Chinese pricing page confirms **Basic ¥504/employee/year** and **Premium ¥756/employee/year**, with a free tier that includes booking links, automatic email notifications, and email support . **List Zoho Bookings, not "Zoho Reservations."**



**Pricing for the restaurant-specific platforms is fragmented but usable:**

- **OpenTable** starts at **$149/month** .

- **Resy** has multiple tiers: **Platform $289/mo**, **Platform 360 $459/mo**, **Essential** (with 3% prepayment fee), **Premium** (2% prepayment fee), and a separate **ResyOS** lineup at **$249–$399/mo** .

- **SevenRooms** shows **$1.00/month** on Software Advice—a placeholder, not a real price . **Do not cite it.**

- **TableCheck** publishes seat-based tiers: **Takeout ¥16,000**, **≤30 seats ¥18,000**, **31–100 seats ¥24,000**, **101+ seats ¥30,000** per month (tax excluded) .

- **Yelp Guest Manager**: Basic **$129–$159/mo** (up to 500 covers), Plus **$279–$349/mo** (unlimited covers), Enterprise custom .

- **Eat App** starts at **$49/month** .

- **Tock** has advertised tiers **from $199/month upward**, with API/webhook access on Premium and Premium Unlimited . Confirm with sales—this is a spec file, not a live pricing page.

- **CoverManager** surfaced only a **WordPress plugin** with one-time pricing (€149–€899), not the SaaS platform . **Do not present it as the platform's pricing.**



## Open-source: what actually exists



The OpenCals analysis is the most useful source, and it is honest about what exists :



| Project | Stars | License | What it actually does |

|---|---|---|---|

| **TastyIgniter** | **3,815**  | MIT | Online ordering platform with a genuine table-reservation module (tables, dining areas, capacity, time slots, lead times, booking widget). **Reservations are secondary to ordering**—no waitlist, no serious floor management, heavy install if reservations are all you need . |

| **openresto** | ~90 | MIT | Bookings only—deliberately narrow. **Early adoption**: small community, young feature set, can go quiet. Best if you have a developer . |

| **Kitchenasty** | ~50 | MIT | Self-hosted ordering + table reservation + management. Same shape as TastyIgniter at a fraction of maturity . |

| **Satisfecho POS** | ~35 | AGPL-3.0 | Restaurant POS with reservations in scope. **AGPL matters** if you host for clients—read the license . |



**The WordPress route is the pragmatic answer for a single independent restaurant**—Five Star Restaurant Reservations and similar GPL plugins give you a booking form, admin list, and email confirmations in ten minutes. No floor plan, no waitlist, no POS link, but bookings stop arriving by phone today .



## What I recommend



**Split into two honest categories:**



**1. SaaS Booking & Reservation Platforms** (proprietary):

- **Zoho Bookings** — ¥504–¥756/employee/year 

- **OpenTable** — from $149/mo 

- **Resy** — $249–$459/mo 

- **TableCheck** — ¥16,000–¥30,000/mo by seats 

- **Yelp Guest Manager** — $129–$349/mo 

- **Eat App** — from $49/mo 

- **Tock** — from ~$199/mo 

- **SevenRooms, CoverManager** — **pricing not surfaced** 



**2. Open-Source Reservation Systems:**

- **TastyIgniter** — 3,815 stars, MIT, ordering-first with reservations module 

- **openresto** — ~90 stars, MIT, bookings-only, early adoption 

- **Kitchenasty** — ~50 stars, MIT, ordering + reservations 

- **Satisfecho POS** — ~35 stars, AGPL-3.0, POS with reservations 



**Flag the TastyIgniter trade-off explicitly:** it is an ordering platform that also does reservations. If reservations are all you need, you are maintaining a payment-integrated Laravel app for a fraction of its capability .



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not present "Zoho Reservations" as a product, cite SevenRooms' $1.00 placeholder, or claim CoverManager's WordPress plugin pricing is the SaaS platform's pricing.
