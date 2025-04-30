# StayEase: Airbnb Clone Project

## 🏠 Project Overview

StayEase is a simplified clone of Airbnb, focused on giving users the ability to browse properties, view details, and make bookings. Built as part of the ALX ProDev Frontend Program, this project emphasizes real-world frontend architecture using modern technologies and development workflows. The goal is to demonstrate practical skills in UI/UX design, responsive layouts, state management, routing, and API integration.

Key features include:
- A clean homepage listing multiple properties.
- A property detail page with images, amenities, and pricing.
- A streamlined booking interface.
- Search and filter functionality.
- Responsive and mobile-friendly UI.

---

🎨 UI/UX Design Planning
🎯 Design Goals
The primary objective of the UI/UX design is to create an intuitive, responsive, and visually appealing interface that enhances the overall user experience. Our focus is on simplicity, clarity, and accessibility, ensuring users can effortlessly browse, view, and book properties.

Key design goals include:

🧭 Clear navigation to allow users to move between pages with ease.

📱 Responsive design to accommodate various screen sizes and devices.

🏷️ Consistent visual hierarchy to guide user attention to key actions (e.g., booking).

⚡ Minimal friction in search, selection, and checkout flows.

👁️ Clean and modern aesthetic aligned with user expectations for travel and hospitality platforms.

🔑 Key Features
Search functionality with filters (location, date, guests, price).

Property cards with images, brief descriptions, and pricing.

Detailed property view including amenities and availability.

Simple and secure booking interface.

Interactive date picker and guest selector.

Responsive layout with accessible components.

📄 Primary Pages Overview

Page	Description	Design Focus
Property Listing View	Displays a list/grid of available properties with image, title, location, price, and a short description.	Visual appeal, card design, filtering controls
Listing Detailed View	Shows detailed information about a selected property including full description, amenities, image gallery, and reviews.	Readability, image layout, booking CTA placement
Simple Checkout View	Enables users to select dates, guests, and proceed to confirmation or payment.	Simplicity, form usability, clear call to action
🤝 Why User-Friendly Design Matters
In a booking system, user-friendly design is not optional — it's essential. Friction in the booking experience can result in lost conversions, user frustration, and poor retention. Key reasons to prioritize great UX include:

✅ Trust: A clean, modern design builds credibility and encourages users to complete bookings.

🧠 Cognitive ease: Users should not need to think hard to accomplish tasks — intuitive layouts lead to smoother interactions.

💸 Conversions: Streamlined checkout and clear CTAs directly impact the likelihood of completing a booking.

📱 Accessibility: Inclusive design ensures everyone, regardless of ability, can use the platform.

A thoughtful UI/UX is the foundation of a successful digital product — and especially vital in a platform where discoverability, clarity, and flow determine the user’s decision to book or bounce.


🎨 Figma Design Properties
🖍️ Color Styles
Below are the primary color styles used in the Figma mockup:

Primary Color: #FF5A5F (used for CTA buttons and highlights)

Secondary Color: #484848 (text and icons)

Background Color: #FFFFFF (main background)

Accent Color: #00A699 (used for pricing and tags)

Border/Divider: #E0E0E0 (used for separating sections)

✍️ Typography

Property	Value
Font Family	Inter, sans-serif
Font Weights	Regular (400), Medium (500), Bold (700)
Font Sizes	12px, 14px, 16px, 20px, 24px, 32px
Headings typically use larger font sizes (20px–32px) with bold weight.

Body text uses 14px–16px with regular or medium weight.

Captions/labels may use 12px with a lighter color or secondary font weight.

🧠 Why Design Properties Matter
Understanding the design properties of a Figma mockup—like color palette and typography—is essential for translating visual designs into consistent, maintainable frontend code. Here's why:

🎯 Consistency: Design tokens (e.g., colors and fonts) form a shared language between designers and developers, reducing guesswork and misalignment.

🎨 Visual Hierarchy: Font size and weight guide the user's eye and define the importance of content. Skipping this undermines the UX.

🔁 Reusability: When color and typography are defined in tokens or CSS variables, it simplifies updates and scaling.

📐 Pixel-perfect implementation: By adhering to defined design properties, developers ensure fidelity to the original vision.

🧪 Testability: Clear design specs make it easier for QA and designers to validate the implementation visually.

Design isn't just how it looks — it's how it works. Identifying these specs early streamlines the handoff and preserves design intent through to production.



## 💻 Tech Stack

| Layer         | Tech                     |
|---------------|--------------------------|
| Frontend      | React, TypeScript        |
| Styling       | TailwindCSS              |
| Design        | Figma                    |
| Version Control | Git, GitHub             |
| Testing       | Jest (unit testing)      |
| API Protocol  | REST (mock or real API)  |
| Build & Deploy| Next.js (SSG/SSR), Vercel (optional) |

---

## 🔧 Project Setup

```bash
git clone https://github.com/<your-username>/airbnb-clone-project.git
cd airbnb-clone-project
npm install
npm run dev
