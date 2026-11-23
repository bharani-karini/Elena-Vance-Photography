Elena Vance Photography — Editorial & Fine Art Portfolio

A responsive, single-page editorial photography portfolio built with semantic HTML5, Tailwind CSS, and vanilla JavaScript. Designed with a dark obsidian and warm champagne-gold aesthetic, it showcases curated photography work, services, transparent pricing packages, and an interactive booking workflow.

🔗 Live Demo: https://bharani-karini.github.io/Elena-Vance-Photography/

✨ Features

Editorial Visual Design & Typography: High-contrast dark theme (#0D0D0F Obsidian & #151518 Charcoal) paired with warm cream (#F5F2EB) and champagne gold (#C8A97E) accents, combining Cormorant Garamond serif headings with Plus Jakarta Sans body copy.

Responsive Navigation: Sticky glassmorphic header that adapts on scroll, smooth section anchor scrolling, and a mobile navigation drawer.

Photographer Introduction (#about): Editorial portrait, artistic philosophy, lighting & hybrid film/digital workflow highlights, and career statistics.

Interactive Curated Gallery (#gallery):

Dynamic category filtering (All Works, Portraits, Weddings, Landscapes, Editorial).

Responsive masonry layout with hover overlays displaying camera body and lens EXIF settings.

Full-Screen Lightbox Modal with previous/next navigation, backdrop close, and keyboard controls (Escape, ArrowLeft, ArrowRight).

Photography Services (#services): Four structured service cards covering Portrait & Lifestyle, Weddings & Events, Commercial & Editorial, and Landscape & Fine Art.

Packages & Pricing (#packages): Three transparent tiers (Essential Session, Signature Collection, Luxury Full-Day). Clicking Select Package smoothly scrolls to the booking form and auto-selects the chosen tier.

Interactive Booking & Contact (#contact): Direct studio contact details, social links, and a client-side validated inquiry form with a future-date guard and personalized confirmation screen.

🛠️ Tech Stack

HTML5 — Semantic structure and accessible ARIA attributes

Tailwind CSS (CDN) — Utility-first styling with custom theme colors and font families

Vanilla JavaScript (ES6+) — Gallery filtering, lightbox state & keyboard navigation, package auto-fill, and form validation

Google Fonts — Cormorant Garamond & Plus Jakarta Sans

Lucide Icons — Crisp vector iconography

📂 Project Structure

Elena-Vance-Photography/
├── index.html      # Complete self-contained application (HTML, Tailwind config, & JS)
└── README.md       # Project documentation


🚀 Getting Started

Because the project is self-contained in a single index.html file with CDN dependencies, no build step or package installation is required:

Clone the repository:

git clone https://github.com/bharani-karini/Elena-Vance-Photography.git


Open locally:
Open index.html directly in any modern web browser, or serve it with a local development server (e.g., VS Code Live Server):

npx serve .


🎨 Customization Guide

Portfolio Images: Edit the portfolioItems array inside the <script> tag in index.html to update image URLs, titles, categories, camera bodies, and EXIF settings.

Packages & Pricing: Update the tier cards in #packages and ensure the corresponding <option> values in #package-select match the string passed to selectPackage('...').

Color Palette: Modify the tailwind.config object in the <head> of index.html (obsidian, charcoal, cream, gold) to re-theme the entire site.

📄 License

This project is open source and available for personal and educational use. Photography placeholders are sourced via 
