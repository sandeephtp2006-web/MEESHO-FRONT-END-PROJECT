# MEESHO-FRONT-END-PROJECT
A fully responsive Netflix landing page rebuilt using clean HTML, CSS Flexbox and Grid. Includes a hero banner, signup form, trending section, feature cards, and FAQs. Designed without absolute positioning for perfect alignment on all screen sizes and devices.
 Netflix Landing Page – Responsive Clone (HTML + CSS)

This project is a fully responsive Netflix landing page built using clean HTML5 and modern CSS (Flexbox + Grid).
It recreates the look and functionality of Netflix’s homepage, including hero sections, forms, trending content, feature cards, and FAQs — all without using absolute positioning.

Project Overview

This Netflix clone focuses on building a clean, scalable and responsive layout.
The entire structure is built using:

Semantic HTML (header, main, section, footer)

CSS Flexbox for horizontal/vertical alignment

CSS Grid for responsive card layout

Responsive typography using clamp()

Mobile-first design

Accessibility support for forms, buttons, and FAQ content

The goal of this redesign is to avoid fixed pixel placements and absolute positioning so the layout adjusts smoothly on all screen sizes—mobile, tablet, and desktop.

Page Structure
 Header

Contains:

Netflix logo

Language selector

Sign-in button
Styled using Flexbox for perfect alignment on all screens.

 Hero Section

Includes:

Full-width background image

Headline and sub-heading

Email form with proper labels and placeholders

The hero uses CSS Grid to keep content centered and responsive.

 Trending Section

Displays thumbnails in a horizontal scrolling list using Flexbox with:

overflow-x: auto;


This allows the user to swipe/scroll through trending titles on any device.

 Features Section

“More reasons to join” block with 4 feature cards.

Built using CSS Grid:

grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));


This makes the cards automatically adjust into 1, 2, or 4 per row depending on screen size.

 FAQ Section

Created using the native HTML:

<details>
  <summary>Question?</summary>
  <p>Answer content…</p>
</details>


This gives built-in expand/collapse support and accessibility without JavaScript.

 Footer

Contains another signup form and standard footer information.

🛠Technologies Used

HTML5

CSS3 (Flexbox + Grid)

Responsive design techniques

Accessibility features

Optimized images and layout

Responsive Design Features

Fluid layout using %, fr, and minmax()

Typography that adjusts using clamp()

Images scaled responsively (object-fit)

Layout adapts at multiple screen breakpoints

Horizontal scrolling for overflowing grids

 Project Structure
/netflix-clone/
│── index.html
│── /css/
│     └── style.css
│── /images/
│     └── (all images)
│── README.md

 How to Run

Download or clone the repository

Open index.html in any web browser
(No framework or server needed)

 Purpose of the Project

This project is designed to:

Practice modern responsive web design

Avoid outdated layout techniques like position:absolute

Build a clean, maintainable structure

Demonstrate UI/UX skills

Provide a realistic Netflix-style UI clone
