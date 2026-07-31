🏏 IPL Fan Zone

A responsive, single-page fan website celebrating the Indian Premier League — built with pure HTML and CSS, no frameworks or build tools required.

Overview

IPL Fan Zone is a static site that showcases IPL teams, captains, and star players in a clean, dark stadium-night theme. It's designed to be dropped straight into a browser or hosted on any static file server.

Features
Sticky, blurred navigation bar with smooth scroll-to-section links and a mobile hamburger menu
Hero section with a stadium background image and a scoreboard-style stat strip
Team grid — all 10 IPL franchises, each with a color accent matching its real team colors
Captains section — jersey-style monogram avatars (initials on a team-colored badge) for each captain
Star players section — highlighted legends with the same avatar treatment
Contact section with quick links
Fully responsive down to mobile (768px and 500px breakpoints)
Accessible focus states and prefers-reduced-motion support
File Structure
├── index.html    # Page markup and content
├── style.css     # All styling, including the team color system
└── README.md     # This file
Tech Stack
HTML5 — semantic sectioning (header, nav, section, footer)
CSS3 — CSS custom properties (variables), CSS Grid, Flexbox, color-mix()
Google Fonts — Poppins (body/display) and JetBrains Mono (stats/labels)
No JavaScript frameworks — a small vanilla JS snippet powers the mobile nav toggle
Getting Started
Download index.html and style.css into the same folder.
Open index.html in any modern browser — that's it, no build step or server needed.
To host it, upload both files to any static hosting service (GitHub Pages, Netlify, Vercel, etc.).
Customizing
Team colors live at the top of style.css under :root (--csk, --rcb, --mi, etc.) — change a hex value and every card/avatar using that team updates automatically.
Captain/player avatars are currently initials-based monograms. To swap in real photos, replace the <div class="avatar">...</div> markup with an <img> tag and add matching image styles.
Content (team names, captains, players, contact info) can be edited directly in index.html.
Credits

Designed and built by Mohith B.
