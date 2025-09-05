Brew Haven — Static Website

Overview
- A modern, warm, and responsive coffee shop website for "Brew Haven".
- Theme: Warm, cozy, premium (deep brown, cream, beige, muted green).
- Location placeholders reference Hyderabad, Telangana, India.
- Copyright year set to 2025.

Pages included
- index.html (homepage with hero, featured items, testimonials, gallery, map, newsletter)
- about.html (shop history, founders, mission & values)
- menu.html (full menu by category)
- shop.html (product catalog — static cards)
- blog.html (sample posts)
- contact.html (contact form + contact info)

Technical notes
- Styling: Tailwind CSS (CDN) — all styling uses Tailwind utility classes.
- Fonts: Inter, Pacifico (handwritten for headings), Playfair Display (serif accents). Fonts are loaded via Google Fonts at the top of each HTML file and applied to sections via inline style where appropriate.
- Animations: Implemented using Tailwind utility classes and a few custom utilities added in a <style> block (animate-fade-in / animate-fade-up). Scroll fade-ins use IntersectionObserver to toggle Tailwind classes.
- Carousel: Swiper.js (CDN) is used for the testimonials slider on the homepage.
- Icons: Inline SVGs are used for social icons and UI icons — they can be styled with Tailwind classes.
- Images: All images are placeholders and use the required format: src="https://pixabay.com/get/ge3aebb65afc3a87d34bf0bd49e9adfdd82fde5ba793dc4bcc40674ef274609f6e9cfd9dd0692f5148a1dd3e69de8e8b977fc133b49e0114326d8c0bdc540ffc9_640.jpg". Replace with real images when integrating.
- Footer: Follows the required 3-column layout with a dark background, light text, brand & socials, quick links, newsletter form, and a centered copyright section.

Accessibility & SEO
- Semantic HTML5 tags are used: header, main, section, article, footer.
- Each page includes a title and meta description.
- Images include descriptive alt text.

Customization
- Replace placeholder images (https://images.unsplash.com/photo-1756758766177-b1213e59c1ae?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw2fHwuLi58ZW58MHwwfHx8MTc1NzA3MDk5Mnww&ixlib=rb-4.1.0&q=80&w=1080) with actual assets.
- Hook up forms and shopping cart to your backend / 3rd-party services as needed.
- To enable a production-ready Tailwind build, consider installing Tailwind via npm and compiling CSS with purging for smaller bundle size.

Local testing
- Open the HTML files in your browser.
- For full map embed functionality, host the files on a server or use Live Server in VS Code.

Credits
- Fonts: Google Fonts (Inter, Pacifico, Playfair Display)
- Slider: Swiper.js

If you want: I can now help replace placeholders with your actual images, connect a real ordering system, or add a working cart checkout flow. Let me know what you'd like next.