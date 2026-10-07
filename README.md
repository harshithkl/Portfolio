# ⚡ Harshith | Software Engineer & Systems Architect Portfolio

> A modern, ultra-performant, responsive developer portfolio engineered with semantic HTML5, Vanilla CSS Glassmorphism design tokens, retro pixel art accents, WCAG AA accessibility, an interactive AI twin assistant, video highlight arcade console, dynamic project modals, and real-time contact form integration.

---

## 🌟 Live Features & Component Architecture

| Component | Features & Interactive Specs |
| :--- | :--- |
| **🧭 Vertical Navigation Dock** | Fixed 260px left dock on desktop; smooth slide-out drawer on mobile/tablet; ScrollSpy active section detection; night/light theme toggle. |
| **👋 Hero Showcase** | Dual-layered glassmorphic hero card; 3D perspective mouse-tracking parallax; animated floating metric badges; responsive portrait display. |
| **👤 Rich Bio & About Me** | Two-column bio layout; pixel art avatar badge; quick career statistics; career highlights; interest tag clouds. |
| **🕹️ Video Spotlight Arcade** | Dedicated 16:9 responsive video highlight embed with privacy mode; authentic CRT scanlines toggle overlay; interactive level chapter timestamps. |
| **⚡ Technical Skills Hub** | Category filter tabs (`All`, `Frontend`, `Backend`, `Databases`, `DevOps`); IntersectionObserver-powered animated progress bars; pixel competency matrix. |
| **⏳ Career & Education Timeline** | Interactive category filtering (`All`, `Career`, `Projects`, `Education`); glowing vertical spine line; accomplishment pill tags. |
| **🚀 Projects Showcase & Modal** | Responsive thumbnail grid (3-col desktop $\rightarrow$ 2-col tablet $\rightarrow$ 1-col mobile); full-screen detailed project modal; keyboard traversal (Escape, Arrow keys); toast copy link. |
| **💬 Client & Peer Testimonials** | Glassmorphic testimonial cards; 5-star ratings; verified relationship badges; project metrics and trust badges. |
| **🤖 Interactive AI Twin Chat** | Real-time chat interface; client-side persona simulation engine; pre-composed prompt suggestion chips; typing indicator; clear chat buffer; OpenAI/Gemini integration blueprint. |
| **📫 Contact Form & Lead Capture** | Client-side validation; loading state animations; confirmation dialog; Resend API backend integration blueprint. |
| **🌐 Pixel Art Social Footer** | Evenly spaced retro social media buttons (GitHub, LinkedIn, Twitter/X, YouTube, Discord, Email) with brand-specific hover glows; quick directory; system specs; Back to Top button. |

---

## 🎓 15 Layered Prompts Sequential Curriculum

This project was built following a 15-step progressive prompt sequence:

1. **Prompt 01: Core Structure & Semantic HTML5 Skeleton** — Establish accessible landmarks (`<aside>`, `<main>`, `<section>`, `<footer>`), doctype, meta tags, and typography.
2. **Prompt 02: Design Tokens & Base Glassmorphism Styles** — Implement CSS Custom Properties, multi-tier backdrop blurs, surface palettes, and typography tokens.
3. **Prompt 03: Fixed Vertical Navigation Bar** — Build the desktop fixed left dock, section icons, live chat pill, and keyboard focus states.
4. **Prompt 04: Dark/Light Mode Theme System** — Add media query theme detection (`prefers-color-scheme`) and interactive toggle with `localStorage` persistence.
5. **Prompt 05: Hero Section Showcase** — Create hero layout with background blur blending, glowing orbs, portrait frame, and floating metrics.
6. **Prompt 06: About Me & Pixel Art Identity** — Build bio layout, pixel avatar container, quick stats cards, and career milestone rows.
7. **Prompt 07: Video Highlight & Retro CRT Arcade Player** — Build responsive 16:9 YouTube video player inside an arcade console with CRT scanlines toggle and chapter markers.
8. **Prompt 08: Interactive Skills Matrix & Animated Progress Bars** — Implement category tabs, animated skill bars, and retro pixel competency grid.
9. **Prompt 09: Dynamic Timeline & Filter System** — Construct an animated vertical spine timeline with category filter buttons.
10. **Prompt 10: Projects Showcase & Interactive Modal Dialog** — Build responsive thumbnail cards and deep-dive modal dialog with keyboard traversal and toast feedback.
11. **Prompt 11: Client & Peer Testimonials Grid** — Create glassmorphic quote cards with 5-star ratings and verified relationship chips.
12. **Prompt 12: AI Twin Interactive Chat Assistant** — Develop interactive chat window, persona knowledge base, typing indicator, and LLM API blueprints.
13. **Prompt 13: Lead Capture Contact Form** — Implement validation, submit animations, success view, and Resend API serverless blueprints.
14. **Prompt 14: Pixel Art Social Footer & Navigation** — Build evenly spaced social links with neon brand hover glows and Back-to-Top anchor.
15. **Prompt 15: Full Responsiveness, Motion Polish & Deployment** — Apply multi-tier media queries, parallax micro-animations, full audit verification, and deployment readiness.

---

## 🚀 Deployment Instructions

### Option 1: GitHub Pages (Recommended for Static Hosting)

1. **Initialize Git & Commit**:
   ```bash
   git init
   git add .
   git commit -m "feat: complete portfolio release v2.0"
   ```

2. **Push to GitHub**:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub $\rightarrow$ **Settings** $\rightarrow$ **Pages**.
   - Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   - Choose `main` branch and `/ (root)` folder, then click **Save**.
   - Your website will be live in ~60 seconds at `https://<your-username>.github.io/<repo-name>/`.

---

### Option 2: Vercel (Zero-Config Deployment)

1. **Install Vercel CLI** (or connect via [vercel.com](https://vercel.com)):
   ```bash
   npm i -g vercel
   vercel
   ```
2. Follow the prompt (accept defaults). Vercel will deploy your project to a global Edge network with HTTPS and custom domain support.

---

### Option 3: Netlify

1. Drag and drop your project folder directly onto the [Netlify Drop](https://app.netlify.com/drop) dashboard.
2. Or connect your GitHub repository for continuous automated deployments on every `git push`.

---

## 🔌 Connecting Live APIs (Optional)

### 1. OpenAI / Gemini LLM Backend for AI Twin (`#chat`)
In `index.html` (inside the `<script>` tag), set:
```javascript
const USE_MOCK_SIMULATION = false;
const API_ENDPOINT = '/api/chat'; // Your serverless endpoint
```

### 2. Resend API Backend for Contact Form (`#contact`)
In `index.html` (inside the `<script>` tag), set:
```javascript
const USE_SIMULATED_EMAIL = false;
const EMAIL_ENDPOINT = '/api/send'; // Your serverless endpoint
```

---

## 📄 License & Credits
- **Designed & Developed by**: Harshith
- **Typography**: [Google Fonts](https://fonts.google.com/) (`Outfit`, `Inter`, `Fira Code`, `Press Start 2P`)
- **License**: MIT
