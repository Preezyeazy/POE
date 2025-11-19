This project demonstrates CSS styling, layout structuring, and responsive design using external stylesheets. It covers typography, visual styles, Flexbox/Grid layout, and media queries for different screen sizes.


Features

    Responsive layout for desktop and mobile

    Navigation menu with linked pages

    "About Us","Artist","Donate","Events","Gallery","Programs" and "Contact" sections

    Font Awesome icons integration

    Basic CSS styling


File & Folder Structure

    Maboneng Youth Arts Collective/
    │__ Pages  
    |    ├── about.html          # About page  
    |    ├── contact.html        # Contact page  
    │    ├── artists.html        # Artists page
    |    ├── donate.html         # Donate page
    |    ├── events.html         # Events page
    |    ├── gallery.html        # Gallery page
    |    ├── poe.html            # POE page
    |    ├── programs.html       # Programs page
    ├── css/
    │   └── styles.css           # Main stylesheet   
    │
    └── assets/
    |     ├── images             # Images used in the site  
    |     |__ Icons
    |
    |__ index.html               #Home page (entry point)

Installation / How to Run

    Open 'index.html' in your browser.

    Use DevTools to test different screen sizes.

    Review the layout, typography and image behavior.

Usage Instructions

    Edit the index.html file to update homepage content.

    Modify css/styles.css to change colors, fonts, or layout.

    Add new pages and link them through the navigation bar.

Author

Phago Magoshi

## Changelog
2025-08-25– Initial Release V.1.0.0

    Added homepage (index.html)

    Created, "About Us","Artist","Donate","Events","Gallery","Programs" and "Contact" pages

    Added navigation bar and footer

    

2025-09-25– Latest Update V.1.1.0
    Added css for decoration, layout, and typography

    Improved mobile responsiveness

    Integrated Font Awesome icons

    Added responsive CSS styling

SEE WEBSITE RESPONSIVE SCREENSHOTS:
./assets/Mobile Screenshot.png
./assets/Tablet Screenshot.png
./assets/Desktop screenshot.png

## Improvements from part 2 feedbaCK
Equally resized the images on the artists page for an improved layout.

Maked usage of pseudo selectors/classes.

Improved the form layout.

Responsive Design: Adjustment Typography defined properly.

The images on the artists page are now responsive.
## PART3 CHANGELOG
- Merged duplicated/reset and scattered style rules into a single, cleaned `css/style.css`. 
- Added CSS variables (design tokens), consistent base typography, layout utilities, and responsive breakpoints (1024px, 768px, 480px).
- Reworked gallery layouts to CSS grid with responsive sizing, hover effects and an accessible lightbox/modal. Added tall/wide item modifiers and smooth transitions.
- Live header clock and footer timestamp (auto-updates), accordion panels on About page, lightbox navigation with keyboard + touch swipe support, and improved contact form scaffolding with client-side validation and feedback box.
- Standardized header, banner, footer and navigation across all pages and ensured they reference the consolidated stylesheet and consistent component classes.
- Added focus styles for interactive elements, ensured meaningful `alt` text, improved color contrast, and visible focus outlines for keyboard users.
- Added `loading="lazy"` to all gallery, artist, and banner images in index.html, about.html, gallery.html, and artists.html for improved performance and faster page loads.
- Added per-field, real-time validation with clear inline error messages for `name`, `email`, `phone`, `message type`, and `message` fields. Validation runs on `input` and `change` events and provides immediate feedback to users.
- The Send button now shows a `Sending...` state, then a `Thank you for your message` state, and is temporarily disabled during processing to prevent duplicate submissions.
- On successful validation the page generates a short approval reference (e.g. `MY-20251119-4823`) and displays it in the modal as confirmation.
- Added EmailJS SDK and configuration placeholders (`EMAILJS_SERVICE_ID`, `EMAILJS_TEMPLATE_ID`, `EMAILJS_PUBLIC_KEY`) so I can enable client-side email confirmations without a backend. When configured, the page will send a confirmation email including the approval reference.
- Added `aria-live` to key message areas, clearer focus and error states, and modal feedback for confirmed submissions.
- Developer notes form uses `novalidate` client-side handling; recommended next steps: (1) configure EmailJS or add a backend endpoint to persist submissions, (2) add server-side validation, and (3) optionally archive submissions to a simple CSV or database.


## REFRENCES

Simplified, W.D., 2023. Youtube. [Online] (1.0) Available at: https://www.youtube.com/watch?v=1PnVor36_40 [Accessed 25 September 2025].

SuperSimpleDev, 2025. Youtube. [Online] (1.0) Available at: https://www.youtube.com/watch?v=EerdGm-ehJQ&t=337s [Accessed 10 November 2025].



