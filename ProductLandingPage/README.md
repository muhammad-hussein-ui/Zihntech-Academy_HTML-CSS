# 🌿 Flores

A skin care product landing page built with semantic HTML5 and pure CSS, developed as part of my Frontend Development training with Zihntech Academy.

---

## 📸 Overview

Flores is a product landing page for a natural skin care brand, translated directly from a Figma design. It features:

- Header with navigation, a centered logo with a decorative watermark, and account/search/cart icons
- Hero section with a large product photo and call-to-action, with the image and text columns matched in width and height
- Store benefits bar (Quick Delivery, Pick Up In Store, Special Packaging, Return Policy)
- "Who Are We" about section
- Trending Products grid with a hover "Add To Cart" overlay
- Customer testimonial with prev/next controls
- Latest Drops (reusing the Trending Products layout)
- Recent Blogs section
- Email subscription form with a styled, italicized placeholder
- Instagram photo gallery
- Footer with navigation, social links, and copyright

---

## 🚀 Features

- Semantic HTML5 structure, with headings placed before descriptive text in every section
- Accessible markup — ARIA labels on icon-only buttons, `aria-hidden` on decorative icons, and a visually-hidden heading on the Instagram section for screen reader context
- Custom typography matched from Figma specs (Nanum Myeongjo for headings, Open Sans for body text)
- Icons and the logo watermark exported directly from Figma as SVG, pre-colored to match the design
- Hover interactions built with pure CSS (no JavaScript) — product "Add To Cart" overlay, nav/footer link colors, social icon backgrounds
- CSS Grid used for precise layout control (three-column centered header, equal-height hero columns)
- Reusable CSS classes shared across sections with identical layouts (Trending Products and Latest Drops)
- Fully responsive with a dedicated mobile breakpoint
- Styled entirely with pure CSS — no frameworks
- Progress documented with section-by-section screenshots in `asset/screenshots/`

---

## 🛠 Technologies Used

- HTML5
- CSS3 (pure CSS, no frameworks)
- Figma (design reference, icon and logo export)
- Google Fonts (Nanum Myeongjo, Open Sans)

---

## 📂 Project Structure

```
ProductLandingPage/
├── asset/
│   ├── images/
│   ├── icons/
│   └── screenshots/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ▶️ How to View It

Open `index.html` in your browser.

---

## 🖼️ Build Progress

| Section | Screenshot |
|---|---|
| Header | `asset/screenshots/01-header.png` |
| Hero | `asset/screenshots/02-hero.png` |
| Services | `asset/screenshots/03-services.png` |
| Who Are We | `asset/screenshots/04-who-we-are.png` |
| Trending Products | `asset/screenshots/05-trending-products.png` |
| Testimonial | `asset/screenshots/06-testimonial.png` |
| Latest Drops | `asset/screenshots/07-latest-drops.png` |
| Recent Blogs | `asset/screenshots/08-recent-blogs.png` |
| Subscribe | `asset/screenshots/09-subscribe.png` |
| Instagram Gallery | `asset/screenshots/10-instagram-gallery.png` |
| Footer | `asset/screenshots/11-footer.png` |

---

## 📚 What I Learned

- Reading and translating exact design specs (colors, typography, spacing) from Figma into working CSS
- Converting Figma's percentage-based letter-spacing into CSS-compatible `em` units
- The difference between Flexbox and CSS Grid, and when each is the right tool — Grid for defining exact column proportions and centering a middle element between two unequal sides; Flexbox for simpler one-directional alignment
- How `box-sizing: border-box` affects padding on fixed-size elements, and why padding should live on the same element as `max-width` when trying to align two separate sections
- Flexbox's default `align-items: stretch` behavior, and how it can silently stretch child elements (like a button) to full width unless explicitly overridden
- Using `::placeholder` as a distinct, separately-stylable pseudo-element, so hint text can be styled (italic, faint) without affecting real typed input
- Using `aspect-ratio` and `object-fit: cover` together to keep images proportionally correct without distorting them
- Reusing a single set of CSS classes across two visually identical sections instead of duplicating styles
- Exporting and applying custom icons and a logo watermark from Figma, and the difference between icons that carry their own styling versus icons that need CSS-driven backgrounds
- Debugging a single-character typo (`0.2rem` vs `0 2rem`) that caused a real, hard-to-spot layout misalignment
- Git line-ending warnings (LF vs CRLF) and why they are safe, automatic conversions rather than errors
- Documenting build progress with screenshots alongside code, and being transparent in commit messages and reports when something was done imperfectly or retroactively

---

## 🔮 Future Improvements

- A working product image carousel (currently static dots)
- A functional subscribe form and live cart count (JavaScript)
- Mobile navigation menu for the header
- Further accessibility testing with a screen reader

---

## 👨‍💻 Author

**Muhammad Hussein**
GitHub: [muhammad-hussein-ui](https://github.com/muhammad-hussein-ui)

---

## 📄 License

This project was created for educational purposes as part of Zihntech Academy's Frontend Development program.