# EDUPRO-STUDENT
Responsive single‑page EduPro landing site built with semantic HTML5 and modern CSS. Includes sticky navbar with CSS burger menu, hero section with CTA, features, program outline, and contact form. Uses CSS variables, one inline style, single meaningful !important, and media queries for full responsiveness.
Features Implemented
Responsive navigation bar

Desktop: horizontal menu links

Mobile: burger menu using the checkbox/label technique (no JavaScript).
​

Hero section with heading, short description, primary call‑to‑action button, and visual hero image.
​

Features section with 3 cards in a grid on desktop and stacked layout on mobile.
​

Program section describing the weekly outline.
​

Contact / enrollment form with: name, email, role (select), message, terms checkbox, and submit button.
​

Technologies Used
HTML5 semantic structure

CSS3 for layout, typography, colors, and responsive design

CSS variables for theme colors (primary, accent, text, muted, background, card, border).
​

No external JavaScript or CSS frameworks are used; the page works fully offline after extraction.
​

Folder Structure
text
EDUPRO-STUDENT
│
├─ index.html
├─ style.css
└─ images/
   ├─ hero.jpg
   └─ logo.svg
The index.html and style.css files are at the top level, and all images are inside the images folder as required.
​

Key Implementation Details
External stylesheet: all global styles are in style.css, linked from index.html.
​

Inline CSS (single usage): the main hero CTA button uses inline style="letter-spacing: 0.5px;" to satisfy the “one inline style” requirement.
​

!important usage: applied once on .btn-primary background to ensure the primary button color stays consistent, as suggested in the assignment.
​

Media queries:

At max-width: 820px for stacking grids, form fields, and hero layout.

At max-width: 700px for switching to the mobile burger menu.

