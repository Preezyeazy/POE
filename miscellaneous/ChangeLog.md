


Changelog

2025-09-25— Initial Responsive Design V.1.1.0
- Created style.css and applied base styles.
- Implemented responsive layout using Grid.
- Styled elements using visual CSS properties.
- Added responsive breakpoints at 768px and 480px.
- Added responsive images using <picture> and srcset

2025-09-26 — Testing & Image Optimization V.1.1.0
- Addes srcset and sizes for image responsiveness.
- Performed responsive testing across devices.
- Included screenshots of desktop, tablet and mobile views.

2025-11-19 — Contact Page: Live Validation & Email Confirmation V.1.3.0
- Added per-field, real-time validation with clear inline error messages for `name`, `email`, `phone`, `message type`, and `message` fields. Validation runs on `input` and `change` events and provides immediate feedback to users.
- The Send button now shows a `Sending...` state, then a `Thank you for your message` state, and is temporarily disabled during processing to prevent duplicate submissions.
- On successful validation the page generates a short approval reference (e.g. `MY-20251119-4823`) and displays it in the modal as confirmation.
- Added EmailJS SDK and configuration placeholders (`EMAILJS_SERVICE_ID`, `EMAILJS_TEMPLATE_ID`, `EMAILJS_PUBLIC_KEY`) so I can enable client-side email confirmations without a backend. When configured, the page will send a confirmation email including the approval reference.
- Added `aria-live` to key message areas, clearer focus and error states, and modal feedback for confirmed submissions.
- Developer notes form uses `novalidate` client-side handling; recommended next steps: (1) configure EmailJS or add a backend endpoint to persist submissions, (2) add server-side validation, and (3) optionally archive submissions to a simple CSV or database.
- Merged duplicated/reset and scattered style rules into a single, cleaned `css/style.css`. Added CSS variables (design tokens), consistent base typography, layout utilities, and responsive breakpoints (1024px, 768px, 480px).
- Reworked gallery layouts to CSS grid with responsive sizing, hover effects and an accessible lightbox/modal. Added tall/wide item modifiers and smooth transitions.
- Live header clock and footer timestamp (auto-updates), accordion panels on About page, lightbox navigation with keyboard + touch swipe support, and improved contact form scaffolding with client-side validation and feedback box.
- Standardized header, banner, footer and navigation across all pages and ensured they reference the consolidated stylesheet and consistent component classes.
- Added focus styles for interactive elements, ensured meaningful `alt` text, improved color contrast, and visible focus outlines for keyboard users.
- Added `loading="lazy"` to all gallery, artist, and banner images in index.html, about.html, gallery.html, and artists.html for improved performance and faster page loads.



