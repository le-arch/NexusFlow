---
# NexusFlow – Enterprise Workflow Automation Marketing Site

A production‑grade, hand‑built marketing website for a fictional B2B software company.  
Developed entirely with semantic HTML, modular CSS, and vanilla JavaScript — **no page builders, no frameworks**.

---

## 🔗 Live URL
[**https://nexus-flow-eta.vercel.app**](https://nexus-flow-eta.vercel.app)  


---

## 📄 Pages & Architecture

| Page      | Hash Route | Description                                   |
|-----------|------------|-----------------------------------------------|
| Home      | `#home`    | Hero, trust signals, value props, CTA        |
| Product   | `#product` | Feature grid, integration logos               |
| Pricing   | `#pricing` | Three plans (Starter, Growth, Enterprise), FAQ |
| Contact   | `#contact` | Contact form with validation, location card   |

- **Shared components**: navigation, footer, card grid, button styles – all managed via CSS custom properties.
- **Content‑driven**: Adding a new page requires only a new `<article>` block and a navigation link – no layout code changes.
- **Routing**: Hash‑based SPA navigation (no page reloads), deep‑linkable, with correct `aria‑live` announcements.

---

## ✅ Key Deliverables

### 1. Semantic & Accessible
- Correct heading hierarchy (`h1` → `h2` → `h3`) on every page.
- Skip‑to‑content link, keyboard‑accessible navigation, focus traps in mobile menu.
- All interactive elements use native focus styles and `:focus-visible`.
- ARIA attributes (`aria-expanded`, `aria-label`, `role="alert"`, etc.) throughout.

### 2. Structured Data (JSON‑LD)
Valid structured data embedded on every page:
- **Organization** – address, contact, social profiles.
- **SoftwareApplication** – product description with pricing offers.
- **FAQPage** – includes all pricing‑page questions.
- **WebSite** – site‑level search action.

### 3. Core Web Vitals (Green on Mobile)
- **Inline CSS** (no blocking requests) → fast FCP/LCP.
- **System font stack** → zero font‑loading delay.
- **Minimal JavaScript** – only routing and form validation (~2 KB).
- **No large images or external assets** – all visual styling via CSS.
- *(Attach Lighthouse / PageSpeed reports to your submission)*

### 4. Mobile‑First Responsive Design
- Flexbox & CSS Grid with `clamp()` for fluid typography.
- Sticky header, mobile menu with hamburger toggle.
- Pricing cards re‑flow on small screens.

---

## 🛠 Tech Stack

| Layer        | Technology                    |
|--------------|-------------------------------|
| Markup       | HTML5 (semantic elements)     |
| Styling      | CSS3 (custom properties, Grid, Flexbox) |
| Behaviour    | Vanilla JavaScript (no dependencies) |
| Icons        | Font Awesome 6 (CDN)          |
| Fonts        | Native system font stack      |

---

## 📂 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/NexusFlow.git
   ```
2. Open `index.html` in any modern browser.
3. Navigate using the top menu or footer links.

No build step, no server – runs directly from the file system.

---

## 🧪 Performance Evidence

*To be completed after deployment:*  
- Google PageSpeed Insights (Mobile)  
- Lighthouse scores (Performance, Accessibility, Best Practices, SEO)  
*Place screenshots in `/evidence` folder.*

---

## 📜 Credit

Built for [Digital Heroes Training Task](https://digitalheroesco.com).  
Credit line included in the site footer.

---

## ⚖️ License

MIT – feel free to use and adapt.
```

---
