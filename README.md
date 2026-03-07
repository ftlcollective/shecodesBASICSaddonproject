# 🌟 SheCodes Basics Add-on — Advanced Front-End Skills
### by Tasneem Mahomed

---

## 📌 Table of Contents

- [Workshop Overview](#workshop-overview)
- [Why the Add-on?](#why-the-add-on)
- [Technologies Used](#technologies-used)
- [What I Learned](#what-i-learned)
- [Project Breakdown](#project-breakdown)
  - [Project 1 — Hometown Web Page: Lenasia](#project-1--hometown-web-page-lenasia-south-africa-)
  - [Project 2 — Seychelles Collage Gallery](#project-2--seychelles-collage-gallery-)
  - [Project 3 — 3D Printed Fashion Hobby Page](#project-3--3d-printed-fashion-hobby-page-)
- [Lessons & Challenges](#lessons--challenges)
- [How to Run](#how-to-run)
- [Folder Structure](#folder-structure)
- [Reflection](#reflection)
- [Author](#author)

---

## Workshop Overview

**SheCodes Basics Add-on** is the natural next step after completing SheCodes Basics. After building my first interactive landing page from scratch, this workshop pushed me further — introducing more advanced CSS techniques, dynamic HTML manipulation with JavaScript, and project-level design thinking.

Over the course of this add-on, I built **three distinct projects**, each one targeting a specific set of skills:

1. 🏡 A **Hometown Web Page** focused on backgrounds, overlays, and layout fundamentals
2. 🌴 A **Seychelles Collage Gallery** exploring CSS transforms, hover effects, and visual creativity
3. 👗 A **3D Printed Fashion Hobby Page** — the final, most technically advanced project, combining CSS Grid, animations, dark/light theme toggling, and custom design systems

Each project was intentionally designed to build on the last, turning individual skills into a cohesive, confident front-end workflow.

---

## Why the Add-on?

After finishing SheCodes Basics, I felt the momentum. The Add-on gave me the opportunity to move beyond the basics and explore what makes modern websites feel *polished* — things like smooth transitions, responsive grid layouts, keyframe animations, and a dark mode that users actually enjoy using.

What excited me most was learning that professional-looking results don't require complex frameworks — they can be achieved with well-crafted, clean HTML, CSS, and a little JavaScript. This workshop proved that.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure and class-based targeting |
| **CSS3** | Advanced styling: transforms, grids, animations, custom properties |
| **JavaScript (Vanilla)** | Class manipulation, theme toggling, interactive behaviour |
| **CSS Custom Properties (Variables)** | Light/dark theme design system |
| **CSS Keyframe Animations** | SVG animations, marquee banners, entrance effects |
| **CSS Grid** | Responsive multi-column card layouts |
| **CSS Transforms** | Rotate, scale, skew, and translate effects |
| **CSS Filters** | Visual effects on images |
| **VS Code** | Primary development environment |
| **GitHub** | Version control and portfolio hosting |

---

## What I Learned

### Advanced CSS Techniques

**CSS Backgrounds:**
- Applying full-page and section-level background images
- Using `background-size: cover` and `background-position` for responsive imagery
- Creating semi-transparent overlays using `rgba()` and `opacity`
- Layering radial gradients and repeating grid patterns for visual depth

**CSS Transforms:**
- Using `rotate()`, `scale()`, `skew()`, and `translate()` to reposition and reshape elements
- Combining `transition` with transforms for smooth, interactive hover effects
- Applying `filter` properties (blur, brightness, contrast) to create image effects
- Understanding `transform-origin` to control the pivot point of animations

**CSS Grid:**
- Creating flexible multi-column layouts using `grid-template-columns`
- Using `gap`, `auto-fill`, and `minmax()` for fully responsive grids
- Structuring card-based layouts that adapt cleanly across screen sizes
- Combining Grid with hover transform effects for interactive card UIs

**CSS Animations & Keyframes:**
- Writing `@keyframes` sequences to define multi-step animations
- Animating SVG elements (a 3D printer) with keyframe sequences
- Building a scrolling marquee banner using continuous CSS animation
- Controlling animation timing with `animation-duration`, `animation-delay`, and `animation-iteration-count`

### Dynamic JavaScript

**HTML Class Manipulation:**
- Using `classList.add()`, `classList.remove()`, and `classList.toggle()` to dynamically change element styling
- Targeting elements with `querySelector` and `getElementById`
- Responding to button clicks with event listeners to trigger class-based UI changes

**Dark / Light Theme Toggle:**
- Implementing a full theme system using CSS custom properties (`--variable-name`)
- Switching themes by updating a `data-theme` attribute on the `<html>` or `<body>` element
- Designing two complete colour palettes (light and dark) that swap seamlessly without page reload
- Persisting theme preference with `localStorage`

---

## Project Breakdown

---

### Project 1 — Hometown Web Page: Lenasia, South Africa 🏡

**Focus:** HTML structure, background images, overlays, and semantic layout

#### About the Project

This project was a personal one — a web page celebrating **Lenasia, South Africa**, the place I call home. The goal was to use a full-page background image, apply a semi-transparent overlay for readability, and structure the content using clean, semantic HTML.

It was the first time I properly worked with background image techniques beyond simple colours, and learning how to balance visual impact with readable content was a valuable design lesson.

#### Skills Practised

| Skill | Detail |
|---|---|
| **Background images** | Using `background-image`, `background-size: cover`, `background-position: center` |
| **Semi-transparent overlays** | Layering `rgba()` divs over images to improve text legibility |
| **Opacity** | Controlling element transparency for visual layering |
| **Responsive image styling** | Ensuring images scale correctly across viewport sizes |
| **Semantic HTML** | Using appropriate heading levels, sections, and containers |
| **Layout basics** | Structuring page sections with `div`, padding, and margin |

#### Key Takeaway

> A beautiful background image means nothing without thoughtful contrast and layout. This project taught me to think about *readability* as a design value, not just aesthetics.

---

### Project 2 — Seychelles Collage Gallery 🌴

**Focus:** CSS transforms, hover interactions, filters, and creative visual styling

#### About the Project

The Seychelles Gallery was a creative challenge — building a multi-image collage where each image could be styled and rotated independently, and where hovering over images triggered smooth, engaging visual effects. It was the most visually expressive project of the add-on and taught me that CSS alone can create stunning interactive experiences.

#### Skills Practised

| Skill | Detail |
|---|---|
| **`transform: rotate()`** | Tilting images at different angles for a natural collage feel |
| **`transform: scale()`** | Scaling images up on hover to create a zoom effect |
| **`transform: skew()`** | Adding visual flair to image positioning |
| **`transition`** | Smooth animations when hovering over elements |
| **`filter`** | Applying brightness, contrast, and saturation effects to images |
| **Transition timing functions** | Using `ease`, `ease-in-out`, and `cubic-bezier` for natural movement |
| **Creative layout** | Positioning multiple images for a visually dynamic collage |

#### Key Takeaway

> CSS transforms are one of the most powerful — and underused — tools in front-end design. This project showed me that with just a few lines of CSS, you can make a static page feel alive and interactive.

---

### Project 3 — 3D Printed Fashion Hobby Page 👗

**Focus:** Full project build — CSS Grid, keyframe animations, dark/light theme toggle, design system

#### About the Project

The **3D Printed Fashion Hobby Page** was the final and most ambitious project of the Add-on. It combined everything learned across both the Basics and the Add-on workshops into a single, polished, production-quality landing page.

The page is themed around the intersection of technology and fashion — specifically, the emerging world of **3D-printed clothing and accessories**. It features an animated SVG 3D printer, a scrolling marquee banner, a responsive card grid, a full dark/light theme system, and a custom footer with smooth scroll navigation.

#### Full Skills & Features

**Layout & Structure:**
- Responsive card grid built with **CSS Grid** (`auto-fill`, `minmax()`, `gap`)
- Mobile-friendly layout that adapts gracefully from small screens to large displays
- Smooth scroll CTA button linking to the main content section

**Visual Design:**
- Background gradients using `linear-gradient` and `radial-gradient`
- Repeating grid patterns for texture and depth
- Glowing radial effects behind hero elements for a futuristic feel
- Custom card hover effects using `transform: translateY()` and `box-shadow` transitions

**Animations:**
- **Keyframe animation** for an SVG 3D printer — bringing the hero illustration to life
- **Scrolling marquee banner** using infinite CSS `animation` and `@keyframes`
- Entrance animations for page elements on load

**Dark / Light Theme Toggle:**
- Full **CSS custom properties** design system with `--color-bg`, `--color-text`, `--color-accent`, etc.
- Theme switch triggered by a button using JavaScript `classList.toggle()`
- `data-theme` attribute on the root element controls which variable set is active
- Smooth transition between themes with `transition: background-color 0.3s, color 0.3s`

**JavaScript Interactivity:**
- Theme toggle button with dynamic icon/label update
- `localStorage` used to remember the user's last theme preference across page visits
- Class manipulation to show/hide elements and trigger CSS animation states

**Personal Branding:**
- Custom footer with name, links, and personal touch
- Consistent colour palette and typography across all sections

#### Technical Highlights

```css
/* Example: CSS custom properties for theme system */
:root[data-theme="light"] {
  --color-bg: #ffffff;
  --color-text: #1a1a2e;
  --color-accent: #7c3aed;
  --color-card: #f3f4f6;
}

:root[data-theme="dark"] {
  --color-bg: #0f0f1a;
  --color-text: #e2e8f0;
  --color-accent: #a78bfa;
  --color-card: #1e1e2e;
}
```

```javascript
// Example: Theme toggle logic
const toggleBtn = document.querySelector(".theme-toggle");
toggleBtn.addEventListener("click", () => {
  const current = document.documentElement.getAttribute("data-theme");
  const next = current === "dark" ? "light" : "dark";
  document.documentElement.setAttribute("data-theme", next);
  localStorage.setItem("theme", next);
});
```

#### Key Takeaway

> This project felt like the moment I went from *learning to code* to *building something I'm genuinely proud of*. The dark mode toggle alone taught me more about design systems and CSS architecture than any single lesson. It's the project I'll be pointing employers to first.

---

## Lessons & Challenges

| Lesson | What I Covered |
|---|---|
| Add-on Overview | Setting expectations and understanding the advanced scope |
| CSS Background | Beyond colours — images, overlays, positioning, gradients |
| CSS Transform | Rotate, scale, skew, translate — and combining them |
| CSS Grids | Flexible, responsive multi-column layouts |
| HTML Class Manipulation | Dynamic class changes using JavaScript |
| Project Overview | Planning the 3D Fashion final project |
| Project Setup | File structure, linking stylesheets and scripts |
| Project Styling | Applying the full visual design system |
| Project Animations | Keyframes, SVG animation, marquee banner |
| Project Grid | Implementing the card grid layout |
| Project Dark Theme 🌙 | Building and toggling a complete light/dark design system |
| Add-on Summary | Reviewing progress and looking ahead |

---

## How to Run

All projects are pure HTML/CSS/JavaScript — no frameworks, no build tools, no installation needed.

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/shecodes-basics-addon.git

# Navigate to a project
cd shecodes-basics-addon/project-3-3d-fashion

# Open in browser
open index.html
```

Or simply double-click any `index.html` file to open it in your browser.

---

## Folder Structure

```
shecodes-basics-addon/
│
├── project-1-hometown-lenasia/
│   ├── index.html
│   └── style.css
│
├── project-2-seychelles-gallery/
│   ├── index.html
│   └── style.css
│
├── project-3-3d-fashion/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md                   # This file
```

---

## Reflection

### How the Add-on Changed My Thinking

Before the Add-on, I thought of CSS as mostly colours and spacing. After it, I see CSS as a full design and animation engine. Learning transforms, grids, keyframes, and custom properties in quick succession completely changed how I approach building a page — I now start by thinking about the *system* before writing individual styles.

### The Hardest Part

The **dark theme toggle** was the most conceptually challenging thing I built. It wasn't just about flipping colours — it was about designing two coherent, harmonious palettes and making them swap seamlessly without any jarring transitions. Getting the CSS variable structure right took several iterations, but when it finally worked smoothly, it was one of my most satisfying moments as a developer.

### The Most Fun Part

The **Seychelles Gallery** was pure joy. There were no strict requirements — just creativity. Tilting photos, adding hover effects, playing with filters — it reminded me that coding can be genuinely playful and artistic.

### What's Next

With SheCodes Basics and the Basics Add-on complete, I have a solid foundation in HTML, CSS, and JavaScript. My next goals are:

- **SheCodes Plus** — deepening JavaScript and API skills
- **SheCodes React** — learning component-based UI development
- Building a **personal portfolio website** using everything I've learned
- Deploying projects live using **GitHub Pages** or **Netlify**

---

## Author

**Tasneem Mahomed**
*SheCodes Basics & Basics Add-on Graduate*

- 🌐 GitHub: [github.com/ftlcollective](https://github.com/ftlcollective)
- 💼 LinkedIn: [linkedin.com/in/tasneemmahomed](https://linkedin.com/in/tasneemmahomed)
- 📧 Email: ftlcollective@gmail.com

---

*Created with 💜 as part of the SheCodes Basics Add-on*
*#SheCodes #WomenWhoCode #LearnToCode #CSS #JavaScript #DarkMode #3DFashion*
