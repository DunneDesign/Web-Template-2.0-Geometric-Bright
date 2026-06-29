@import url('https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=JetBrains+Mono:wght@400;500;600;700&display=swap');

:root {
  --main-color: #ff304f;         /* Neon-Vivid Crimson Red */
  --secondary-color: #00ffcc;    /* Electric Mint Green */
  --neutral-dark: #000000;       /* Onyx Charcoal Carbon */
  --neutral-mid: #2b2e35;        /* Premium Dark Slate Gray for Copy */
  --neutral-light: #fdfaf4;      /* Luxurious Linen Milk White */
  --neutral-light-gray: #f5f1e6; /* Exquisite Oatmeal Warm Gray */
  --border-color: #000000;       /* Thick Bold Black Border */
  --border-color-dark: #000000;
  --transition-speed: 0.25s;     /* Snappy transition for Brutalist interactive styles */
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "JetBrains Mono", monospace;
  -webkit-font-smoothing: antialiased;
}

body {
  background-color: var(--neutral-light);
  color: var(--neutral-dark);
  overflow-x: hidden;
  line-height: 1.6;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Syne", sans-serif;
  font-weight: 800;
  letter-spacing: -0.04em;
  text-transform: uppercase;
  color: var(--neutral-dark);
  line-height: 1.05;
}

h1 {
  font-size: clamp(2.5rem, 6.5vw, 4.5rem);
}

h2 {
  font-size: clamp(1.85rem, 4.8vw, 3rem);
}

h3 {
  font-size: clamp(1.4rem, 3.2vw, 2.1rem);
}

p {
  font-size: 1rem;
  color: var(--neutral-mid);
  max-width: 65ch;
  line-height: 1.65;
}

a {
  text-decoration: none;
  color: inherit;
  transition: all var(--transition-speed) ease;
}

/* Captions and Subheaders */
.section-caption {
  display: block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: var(--main-color);
  margin-bottom: 0.75rem;
}

.section-caption-below {
  display: block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  color: var(--main-color);
  margin-top: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}

.section-caption-secondary {
  display: block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: var(--neutral-dark);
  margin-bottom: 0.75rem;
}

/* Page Scroll Animations */
.scroll-anim {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: transform, opacity;
}

.scroll-anim-slide-left {
  opacity: 0;
  transform: translateX(-30px);
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: transform, opacity;
}

.scroll-anim-slide-right {
  opacity: 0;
  transform: translateX(30px);
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: transform, opacity;
}

.scroll-anim.animate-visible,
.scroll-anim-slide-left.animate-visible,
.scroll-anim-slide-right.animate-visible {
  opacity: 1;
  transform: translate(0, 0);
}

.scroll-delay-1 { transition-delay: 0.08s; }
.scroll-delay-2 { transition-delay: 0.16s; }
.scroll-delay-3 { transition-delay: 0.24s; }
.scroll-delay-4 { transition-delay: 0.32s; }
.scroll-delay-5 { transition-delay: 0.4s; }

/* Navigation */
.navbar {
  position: sticky;
  top: 0;
  z-index: 1000;
  background-color: var(--neutral-dark);
  color: var(--neutral-light);
  padding: 1.35rem 5%;
  border-bottom: 1px solid var(--border-color-dark);
}

.nav-content {
  width: 100%;
  max-width: 1245px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  display: flex;
  list-style: none;
  align-items: center;
  gap: 1.75rem;
}

.nav-links li {
  position: relative;
}

.nav-links li a {
  color: var(--neutral-light);
  font-weight: 500;
  font-size: 0.95rem;
  padding: 0.5rem 0.25rem;
  display: block;
  letter-spacing: 0.03em;
}

.nav-links li a::after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  bottom: -2px;
  left: 0;
  background-color: var(--main-color);
  transform-origin: bottom right;
  transition: transform var(--transition-speed) cubic-bezier(0.16, 1, 0.3, 1);
}

.nav-links li a:hover {
  color: var(--main-color);
}

.nav-links li a:hover::after {
  transform: scaleX(1);
  transform-origin: bottom left;
}

/* Dropdown Menu styling */
.dropdown {
  position: relative;
}

.dropdown-content {
  opacity: 0;
  visibility: hidden;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: var(--neutral-dark);
  min-width: 200px;
  box-shadow: 0 15px 35px rgba(0,0,0,0.3);
  border: 1px solid var(--border-color-dark);
  border-radius: 4px;
  list-style: none;
  padding: 0.5rem 0;
  margin-top: 0.5rem;
  z-index: 1100;
  transition: opacity var(--transition-speed) ease, visibility var(--transition-speed) ease;
  transition-delay: 0.2s;
}

.dropdown-content li a {
  padding: 0.75rem 1.25rem;
  font-size: 0.9rem;
}

.dropdown-content li a::after {
  display: none;
}

.dropdown-content li a:hover {
  background-color: rgba(255, 255, 255, 0.04);
  color: var(--main-color);
}

.dropdown:hover .dropdown-content {
  opacity: 1;
  visibility: visible;
  transition-delay: 0s;
}

/* Layout Blocks */
.mobile-only {
  display: none !important;
}

section {
  padding: 6.5rem 5% 6.5rem 5%;
  background-color: var(--neutral-light);
  position: relative;
}

.container {
  width: 100%;
  max-width: 1245px;
  margin: 0 auto;
}

hr.rounded {
  display: none;
}

/* Layout Grids */
.two-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 4.5rem;
  align-items: center;
}

.three-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 2.5rem;
  width: 100%;
  max-width: 100%;
}

.three-grid > div {
  min-width: 0;
  word-wrap: break-word;
  overflow-wrap: break-word;
}

.bento-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-auto-rows: minmax(220px, auto);
  gap: 1.75rem;
}

.bento-card {
  background: var(--neutral-light);
  border: 2.5px solid var(--border-color);
  padding: 2.75rem;
  border-radius: 0px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  box-shadow: 6px 6px 0px var(--neutral-dark);
  transition: all var(--transition-speed) ease;
}

.bento-card:hover {
  transform: translate(-3px, -3px);
  border-color: var(--main-color);
  box-shadow: 10px 10px 0px var(--neutral-dark);
}

.bento-card.col-span-2 {
  grid-column: span 2;
}

.bento-card.row-span-2 {
  grid-row: span 2;
}

/* Stylized Background Color Sections */
.main-color-section {
  background-color: var(--main-color);
  color: var(--neutral-light);
  border-top: 2.5px solid var(--neutral-dark);
  border-bottom: 2.5px solid var(--neutral-dark);
}

.main-color-section h1,
.main-color-section h2,
.main-color-section h3,
.main-color-section p,
.main-color-section .section-caption-below {
  color: var(--neutral-light) !important;
}

.main-color-section .section-caption {
  color: var(--neutral-dark) !important;
}

.secondary-color-section {
  background-color: var(--secondary-color);
  color: var(--neutral-dark);
  border-top: 2.5px solid var(--neutral-dark);
  border-bottom: 2.5px solid var(--neutral-dark);
}

.secondary-color-section h1,
.secondary-color-section h2,
.secondary-color-section h3,
.secondary-color-section p,
.secondary-color-section .section-caption-below {
  color: var(--neutral-dark) !important;
}

.secondary-color-section .section-caption {
  color: var(--main-color) !important;
}

/* Button Styling */
.button-links {
  display: inline-block;
  padding: 1.15rem 2.25rem;
  border-radius: 0px;
  font-weight: 700;
  font-size: 0.85rem;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  border: 2.5px solid var(--neutral-dark) !important;
  text-align: center;
  cursor: pointer;
  background-color: var(--neutral-light);
  color: var(--neutral-dark);
  box-shadow: 5px 5px 0px var(--neutral-dark);
  transition: all var(--transition-speed) ease;
  text-decoration: none !important;
}

.button-links:hover {
  transform: translate(2px, 2px);
  box-shadow: 2px 2px 0px var(--neutral-dark);
}

.nav-links li a.button-links::after,
footer .nav-links li a.button-links::after,
.button-links::after {
  display: none !important;
}

.nav-links li a.button-links:hover,
footer .nav-links li a.button-links:hover,
.nav-links li a.button-links:focus,
footer .nav-links li a.button-links:focus {
  color: var(--neutral-dark) !important;
}

.nav-links li a.light-button:hover,
footer .nav-links li a.light-button:hover {
  color: var(--neutral-light) !important;
}

.nav-links li a.dark-button:hover,
footer .nav-links li a.dark-button:hover {
  color: var(--neutral-dark) !important;
}

.light-button {
  background-color: var(--neutral-light-gray);
  color: var(--neutral-dark);
  border: 2.5px solid var(--border-color);
}

.light-button:hover {
  background-color: var(--main-color);
  color: var(--neutral-light);
  border-color: var(--neutral-dark);
}

section:not(.dark-section):not(.main-color-section):not(.secondary-color-section) .light-button {
  border: 2.5px solid var(--neutral-dark);
}

.dark-button {
  background-color: var(--neutral-dark);
  color: var(--neutral-light);
}

.dark-button:hover {
  background-color: var(--main-color);
  color: var(--neutral-light);
}

.dark-section .dark-button,
.main-color-section .dark-button,
.secondary-color-section .dark-button,
.navbar .dark-button,
footer .dark-button {
  border: 2.5px solid var(--neutral-light);
}

.accent-button {
  background-color: var(--main-color);
  color: var(--neutral-light);
}

.accent-button:hover {
  background-color: var(--secondary-color);
  color: var(--neutral-dark);
}

.secondary-button {
  background-color: var(--secondary-color);
  color: var(--neutral-dark);
}

.secondary-button:hover {
  background-color: var(--main-color);
  color: var(--neutral-light);
}

.white-button {
  background-color: var(--neutral-light);
  color: var(--neutral-dark);
}

.white-button:hover {
  background-color: var(--neutral-dark);
  color: var(--neutral-light);
}

section:not(.dark-section):not(.main-color-section):not(.secondary-color-section) .white-button {
  border: 2.5px solid var(--neutral-dark);
}

.nav-action-button {
  background-color: var(--main-color) !important;
  color: var(--neutral-light) !important;
  border: 2.5px solid var(--neutral-dark) !important;
  font-weight: 700 !important;
  box-shadow: 4px 4px 0px var(--neutral-dark) !important;
}

.nav-links li a.nav-action-button:hover,
footer .nav-links li a.nav-action-button:hover,
.nav-links li a.nav-action-button:focus,
footer .nav-links li a.nav-action-button:focus,
.nav-action-button:hover,
.nav-action-button:focus {
  background-color: var(--secondary-color) !important;
  color: var(--neutral-dark) !important;
  transform: translate(2px, 2px);
  box-shadow: 1px 1px 0px var(--neutral-dark) !important;
}

/* Sticky Column Layout */
.left-sticky {
  position: sticky;
  top: 150px;
  align-self: start;
}

/* Asymmetric Team Leadership Grid */
.team-grid-asymmetric {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4.5rem;
  align-items: center;
}

.team-grid-asymmetric .left-col,
.team-grid-asymmetric .right-col {
  display: flex;
  flex-direction: column;
  gap: 3.5rem;
}

.team-grid-asymmetric .right-col {
  margin-top: 5rem;
}

.leader-card {
  background: var(--neutral-light);
  padding: 3rem;
  border-radius: 0px;
  box-shadow: 6px 6px 0px var(--neutral-dark);
  border: 2.5px solid var(--border-color);
  transition: all var(--transition-speed) ease;
}

.leader-card:hover {
  transform: translate(-3px, -3px);
  border-color: var(--main-color);
  box-shadow: 10px 10px 0px var(--neutral-dark);
}

.leader-title {
  color: var(--main-color);
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 0.1em;
  margin-bottom: 0.5rem;
}

.leader-bio {
  color: var(--neutral-mid);
  margin-top: 1rem;
}

/* Services Page Tiers Grid */
.services-tier-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2.5rem;
}

.service-card {
  background: var(--neutral-light);
  padding: 3.5rem 2.5rem;
  border-radius: 0px;
  border: 2.5px solid var(--border-color);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  box-shadow: 6px 6px 0px var(--neutral-dark);
  transition: all var(--transition-speed) ease;
}

.service-card h1, .service-card h2, .service-card h3, .service-card p, .service-card li,
.leader-card h1, .leader-card h2, .leader-card h3, .leader-card p, .leader-card li,
.bento-card h1, .bento-card h2, .bento-card h3, .bento-card p, .bento-card li,
.leader-bio {
  color: var(--neutral-dark) !important;
}

.service-card:hover {
  transform: translate(-3px, -3px);
  border-color: var(--main-color);
  box-shadow: 10px 10px 0px var(--neutral-dark);
}

.service-feature-tag {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.8rem;
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 0.12em;
  color: var(--main-color);
  margin-bottom: 1.25rem;
  display: inline-block;
}

/* Vertical bullet-list */
ul.vertical-list {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  list-style: none;
}

ul.vertical-list li {
  padding-left: 1.75rem;
  border-left: 3px solid var(--main-color);
}

ul.vertical-list li h3 {
  margin-bottom: 0.5rem;
}

/* Testimonial Box Styling */
.testimony-div {
  margin-top: 2rem;
  border-left: 5px solid var(--main-color);
  padding-left: 2rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.testimony-div h3 {
  font-family: "Syne", sans-serif;
  font-weight: 700;
  font-size: clamp(1.2rem, 2.5vw, 1.6rem);
  line-height: 1.35;
  margin-bottom: 1.25rem;
}

.testimony-div p {
  font-family: "JetBrains Mono", monospace;
  font-weight: 700;
  font-size: 0.95rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: var(--main-color);
}

/* FAQ Accordion Section */
.faq-container {
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.faq-item {
  border: 2.5px solid var(--border-color);
  border-radius: 0px;
  overflow: hidden;
  background-color: var(--neutral-light);
  box-shadow: 4px 4px 0px var(--neutral-dark);
  transition: all var(--transition-speed) ease;
}

.faq-item:hover {
  border-color: var(--main-color);
}

.faq-question {
  width: 100%;
  padding: 1.75rem 2rem;
  text-align: left;
  background: none;
  border: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-family: "JetBrains Mono", monospace;
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--neutral-dark);
  cursor: pointer;
}

.faq-answer {
  max-height: 0;
  overflow: hidden;
  transition: max-height var(--transition-speed) cubic-bezier(0.16, 1, 0.3, 1), padding var(--transition-speed) ease;
  background-color: var(--neutral-light-gray);
  border-top: 2.5px solid transparent;
}

.faq-item.active .faq-answer {
  max-height: 250px;
  padding: 1.75rem 2rem;
  border-top-color: var(--border-color);
}

.faq-icon {
  font-size: 1.5rem;
  font-weight: 300;
  color: var(--main-color);
  transition: transform var(--transition-speed) ease;
}

.faq-item.active .faq-icon {
  transform: rotate(45deg);
}

/* Statistics Figures & Metric Sections */
.center-figures {
  display: flex;
  justify-content: space-evenly;
  gap: 3rem;
  flex-wrap: wrap;
  width: 100%;
}

.vertical-figure {
  text-align: center;
  flex: 1;
  min-width: 200px;
  padding: 2rem 1.5rem;
}

.vertical-figure h2 {
  font-family: "Syne", sans-serif;
  font-size: clamp(3rem, 8vw, 5.5rem);
  color: var(--main-color);
  font-weight: 800;
  margin-bottom: 0.5rem;
}

.vertical-figure p {
  font-family: "JetBrains Mono", monospace;
  font-weight: 700;
  font-size: 0.9rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: var(--neutral-mid);
}

.dark-section .vertical-figure p {
  color: rgba(255, 255, 255, 0.7);
}

/* Center Container */
.center {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.center h2, .center h3, .center p {
  margin-bottom: 1.25rem;
}

/* Infinite Client Logo Carousel */
.carousel-container {
  overflow: hidden;
  padding: 3rem 0;
  background: var(--neutral-light-gray);
  position: relative;
  width: 100%;
}

.carousel-container::before,
.carousel-container::after {
  background: linear-gradient(to right, var(--neutral-light-gray) 0%, rgba(245, 241, 230, 0) 100%);
  content: "";
  height: 100%;
  position: absolute;
  width: 150px;
  z-index: 2;
  top: 0;
}

.carousel-container::before {
  left: 0;
}

.carousel-container::after {
  right: 0;
  transform: rotateZ(180deg);
}

.carousel-track {
  display: flex;
  width: max-content;
  animation: scroll 30s linear infinite;
}

.carousel-track:hover {
  animation-play-state: paused;
}

.slide {
  width: 250px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.placeholder-logo {
  width: 175px;
  height: 55px;
  background-color: var(--neutral-light);
  border: 2.5px solid var(--neutral-dark);
  border-radius: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "JetBrains Mono", monospace;
  font-weight: 700;
  color: var(--neutral-dark);
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  box-shadow: 4px 4px 0px var(--neutral-dark);
  transition: all var(--transition-speed) ease;
}

.placeholder-logo:hover {
  background-color: var(--secondary-color);
  color: var(--neutral-dark);
  transform: translate(2px, 2px);
  box-shadow: 1px 1px 0px var(--neutral-dark);
  cursor: pointer;
}

@keyframes scroll {
  0% { transform: translateX(0); }
  100% { transform: translateX(-33.3333%); }
}

/* Hero Banners */
.hero-banner {
  padding: 7rem 5% 8rem 5%;
  background: radial-gradient(circle at 85% 20%, rgba(255, 48, 79, 0.08) 0%, rgba(255, 255, 255, 0) 50%),
              radial-gradient(circle at 15% 80%, rgba(0, 255, 204, 0.06) 0%, rgba(255, 255, 255, 0) 50%);
  border-bottom: 2.5px solid var(--border-color);
}

.hero-content {
  display: flex;
  flex-direction: column;
  gap: 1.75rem;
  align-items: flex-start;
}

.hero-content p {
  font-size: 1.2rem;
  line-height: 1.65;
}

/* Interactive SVG Logo and animations */
.logo svg {
  fill: currentColor !important;
  transition: transform var(--transition-speed) ease;
}

.logo:hover svg {
  transform: rotate(15deg) scale(1.1);
  color: var(--main-color);
}

/* Contact Page form layout */
form.vertical-list {
  list-style: none;
  width: 100%;
}

form.vertical-list label {
  display: block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  font-weight: 700;
  color: var(--neutral-dark);
  margin-bottom: 0.5rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

form.vertical-list input, 
form.vertical-list textarea {
  width: 100%;
  padding: 1.1rem 1.25rem;
  border: 2.5px solid var(--border-color);
  border-radius: 0px;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.95rem;
  color: var(--neutral-dark);
  background-color: var(--neutral-light);
  margin-bottom: 1.5rem;
  transition: all var(--transition-speed) ease;
}

form.vertical-list input:focus, 
form.vertical-list textarea:focus {
  outline: none;
  border-color: var(--main-color);
  box-shadow: 4px 4px 0px var(--neutral-dark);
}

form.vertical-list textarea {
  resize: vertical;
  min-height: 150px;
}

/* Footer Section */
footer {
  background-color: var(--neutral-dark);
  color: var(--neutral-light);
  padding: 5.5rem 5% 3rem 5%;
  border-top: 6px solid var(--main-color);
}

footer .footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1245px;
  margin: 0 auto;
  padding-bottom: 3.5rem;
  border-bottom: 2.5px solid var(--neutral-light);
}

footer .nav-links li a {
  color: rgba(255, 255, 255, 0.75);
}

footer .nav-links li a:hover {
  color: var(--main-color);
}

footer .copyright {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.85rem;
  color: rgba(255, 255, 255, 0.4);
  margin: 2.5rem auto 0 auto;
  text-align: center;
  display: block;
  width: 100%;
}

/* Hamburger Responsive Toggle */
.hamburger {
  display: none;
  flex-direction: column;
  justify-content: space-between;
  width: 28px;
  height: 20px;
  cursor: pointer;
  position: relative;
  z-index: 2000;
}

.hamburger span {
  display: block;
  width: 100%;
  height: 2px;
  background-color: var(--neutral-light);
  border-radius: 1px;
  transition: all var(--transition-speed) ease;
}

.hamburger:hover span {
  background-color: var(--main-color);
}

/* Responsive Styles */
@media (max-width: 1024px) {
  .hamburger {
    display: flex;
  }

  .nav-links {
    position: fixed;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100vh;
    background-color: var(--neutral-dark);
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    transition: left 0.4s cubic-bezier(0.16, 1, 0.3, 1);
    z-index: 1500;
  }

  .nav-links.active {
    left: 0;
  }

  .nav-links li a {
    font-size: 1.5rem;
    padding: 0.75rem 1rem;
  }

  .nav-links li a::after {
    height: 3px;
    bottom: -4px;
  }

  .mobile-only {
    display: block !important;
  }

  .desktop-only {
    display: none !important;
  }

  .dropdown-content {
    position: static;
    display: none;
    background-color: rgba(255, 255, 255, 0.05);
    box-shadow: none;
    border: none;
    width: 100%;
    text-align: center;
    margin-top: 0.5rem;
  }

  .dropdown-content.active {
    display: block;
  }

  /* Structural adjustment */
  .two-grid, .three-grid, .bento-grid, .services-tier-grid, .team-grid-asymmetric {
    grid-template-columns: 1fr;
    gap: 3rem;
  }

  .bento-card.col-span-2 {
    grid-column: span 1;
  }

  .left-sticky {
    position: static;
    margin-bottom: 2rem;
  }

  .team-grid-asymmetric .right-col {
    margin-top: 0;
  }

  footer .footer-content {
    flex-direction: column;
    gap: 2.5rem;
    text-align: center;
  }

  footer .nav-links {
    flex-direction: column;
    gap: 1.25rem;
  }
}

@media (max-width: 576px) {
  section {
    padding: 4.5rem 5%;
  }

  .carousel-container::before,
  .carousel-container::after {
    width: 60px;
  }
}
