# Cursor Landing Page Recreation

A desktop-first developer tool landing page inspired by the [Cursor website](https://www.cursor.com). This project focuses on **visual and structural accuracy**, recreating the design and layout of the original Cursor landing page.

## 🎯 Project Goal

The goal of this assignment is to achieve visual and structural accuracy in recreating the Cursor landing page, prioritizing faithful reproduction of the design over creativity or interactivity.

## 📋 Sections Recreated

This landing page includes the following sections from the original Cursor website:

### 1. **Header/Navigation**

- Sticky navigation bar with logo (animated on hover)
- Navigation links: Features, Enterprise, Pricing, Resources
- Sign in and Download buttons

### 2. **Hero Section**

- Main headline: "Built to make you extraordinarily productive"
- Subheading about Cursor being the best way to code with AI
- Call-to-action download button
- Hero image showcasing the product

### 3. **Trust Section (Section 2)**

- Social proof text: "Trusted every day by teams that build world-class software"
- Brand logo grid featuring companies like:
  - Stripe
  - OpenAI
  - Linear
  - Datadog
  - Nvidia
  - Figma
  - Ramp
  - Adobe

### 4. **Features Section (Section 3)**

Three feature highlights with images:

- **Agent turns ideas into code** - Accelerate development by delegating tasks
- **Magically accurate autocomplete** - Tab model for predictions
- **In every tool, at every step** - PR reviews, Slack collaboration, terminal integration

### 5. **Testimonials Section (Section 4)**

- Heading: "The new way to build software"
- Six testimonial cards from industry leaders:
  - Diana Hu (Y Combinator)
  - shadcn (Creator of shadcn/ui)
  - Andrej Karpathy (Eureka Labs)
  - Patrick Collison (Stripe)
  - ThePrimeagen
  - Greg Brockman (OpenAI)

### 6. **Product Features Section (Section 5)**

- Heading: "Stay on the frontier"
- Three feature cards:
  - Use the best model for every task
  - Complete codebase understanding
  - Develop enduring software (Enterprise focus)

### 7. **Changelog Section (Section 6)**

- Recent updates with version numbers and dates:
  - v2.4 - Subagents, Skills, and Image Generation
  - CLI Agent Modes and Cloud Handoff
  - New CLI Features and Improved CLI Performance
  - v2.3 - Layout Customization and Stability Improvements

### 8. **Team/Careers Section (Section 7)**

- Mission statement about Cursor being an applied research team
- "Join us" call-to-action button
- Team photo

### 9. **Blog/Highlights Section (Section 8)**

- Heading: "Recent highlights"
- Three featured blog posts:
  - Introducing Cursor 2.0 and Composer
  - Improving Cursor Tab with online RL
  - 1.5x faster MoE training with custom MXFP8 kernels

### 10. **Final CTA Section (Section 9)**

- Large heading: "Try Cursor now"
- Download button

### 11. **Footer**

Five column layout with links:

- **Product**: Features, Enterprise, Web Agents, Bugbot, CLI, Pricing
- **Resources**: Download, Changelog, Docs, Learn, Forum, Status
- **Company**: Careers, Blog, Community, Workshops, Students, Brand
- **Legal**: Terms of Service, Privacy Policy, Data Use, Security
- **Connect**: X, LinkedIn, Youtube

Copyright section with:

- SOC 2 Certification badge
- Theme toggles (Desktop, Light, Dark)
- Language selector

## 📸 Screenshot

### Full Page View

![Full Cursor Landing Page](screenshots/full-page.png)

## 🎨 Fonts and Colors Used

### Fonts

The project uses the **CursorGothic** custom font family with the following variants:

```css
@font-face {
  font-family: CursorGothic;
  src: url("./CursorGothic-main/fonts/CursorGothic-Regular.woff2")
    format("woff2");
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: CursorGothic;
  src: url("./CursorGothic-main/fonts/CursorGothic-Italic.woff2")
    format("woff2");
  font-weight: 400;
  font-style: italic;
}

@font-face {
  font-family: CursorGothic;
  src: url("./CursorGothic-main/fonts/CursorGothic-Bold.woff2") format("woff2");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: CursorGothic;
  src: url("./CursorGothic-main/fonts/CursorGothic-BoldItalic.woff2")
    format("woff2");
  font-weight: 700;
  font-style: italic;
}
```

**Font fallback stack:**

```css
font-family:
  CursorGothic, "CursorGothic Fallback", system-ui, "Helvetica Neue", Helvetica,
  Arial, sans-serif;
```

### Colors

The color scheme uses a dark theme with warm undertones:

#### CSS Custom Properties:

```css
:root {
  --color-theme-bg: #14120b; /* Main background - dark brown-black */
  --color-theme-fg: #edecec; /* Primary foreground - off-white */
  --color-theme-fg-02: #d7d6d5; /* Secondary foreground - lighter gray */
  --color-theme-card-hex: #1b1913; /* Card background - dark brown */
  --color-theme-card-rgb: 27 29 39; /* Card RGB values */
  --color-theme-card-01-hex: #1d1b15; /* Card variant 1 */
  --color-theme-card-02-hex: #201e18; /* Card variant 2 */
  --color-theme-card-03-hex: #26241e; /* Card variant 3 */
  --color-theme-card-04-hex: #2b2923; /* Card variant 4 */
  --color-theme-card-hover-hex: #201e18; /* Card hover state */
  --color-theme-card-hover-light-hex: #1d1b15; /* Card hover light variant */
  --color-theme-product-chrome: var(--color-theme-bg);
  --color-theme-product-editor: var(--color-theme-card-hex);
}
```

#### Key Colors:

- **Background**: `#14120b` - Deep brown-black
- **Text (Primary)**: `#edecec` - Off-white
- **Text (Secondary)**: `rgb(168, 162, 150)` - Muted gray-brown
- **Text (Muted/Transparent)**: `oklab(0.943853 0.00107113 0.000336707 / 0.6)` - Semi-transparent white
- **Accent/Links**: `rgb(233, 62, 62)` / `rgb(233, 61, 61)` / `rgb(245, 78, 0)` / `rgb(221, 71, 1)` - Red/orange variations
- **Cards**: Various shades from `#1b1913` to `#2b2923` - Layered dark brown tones
- **Buttons**: Uses foreground color `#edecec` with transparency effects

### Installation

1. Clone or download this repository
2. Ensure the font files are in the correct directory structure:
3. Ensure all assets are in the `./assets/` directory
4. Open `index.html` in your web browser
