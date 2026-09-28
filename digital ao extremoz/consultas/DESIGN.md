---
name: Public Health Tech
colors:
  surface: '#f5fbf1'
  surface-dim: '#d6dcd2'
  surface-bright: '#f5fbf1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff5eb'
  surface-container: '#e9f0e6'
  surface-container-high: '#e4eae0'
  surface-container-highest: '#dee4da'
  on-surface: '#171d17'
  on-surface-variant: '#3e4a3e'
  inverse-surface: '#2c322b'
  inverse-on-surface: '#ecf3e9'
  outline: '#6e7a6d'
  outline-variant: '#bdcabb'
  surface-tint: '#006d31'
  primary: '#006b30'
  on-primary: '#ffffff'
  primary-container: '#00873e'
  on-primary-container: '#f7fff3'
  inverse-primary: '#6edd88'
  secondary: '#256b3a'
  on-secondary: '#ffffff'
  secondary-container: '#aaf4b5'
  on-secondary-container: '#2c7140'
  tertiary: '#275e99'
  on-tertiary: '#ffffff'
  tertiary-container: '#4477b3'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#8afaa2'
  primary-fixed-dim: '#6edd88'
  on-primary-fixed: '#00210a'
  on-primary-fixed-variant: '#005323'
  secondary-fixed: '#aaf4b5'
  secondary-fixed-dim: '#8fd79b'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#015224'
  tertiary-fixed: '#d3e4ff'
  tertiary-fixed-dim: '#a3c9ff'
  on-tertiary-fixed: '#001c38'
  on-tertiary-fixed-variant: '#004882'
  background: '#f5fbf1'
  on-background: '#171d17'
  surface-variant: '#dee4da'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system is built upon the principles of universal access, reliability, and modern efficiency. It draws inspiration from the spirit of Brazilian public health—inclusive and expansive—while applying a rigorous, tech-forward "SaaS" layer to ensure the interface feels professional and high-performing.

The aesthetic follows a **Modern Corporate** approach with a focus on **Universal Accessibility**. It prioritizes clarity over decoration, using ample whitespace and a structured layout to reduce cognitive load for citizens and health professionals. The emotional response should be one of "calm authority"—a system that works predictably, remains approachable, and feels like a premium public utility.

## Colors

The palette is anchored in a spectrum of greens and blues that signal growth, health, and institutional stability.

- **Primary Green (#008A40):** Used for primary actions, success states, and brand identification.
- **Secondary Deep Green (#005224):** Used for hover states, deep headers, and high-contrast text elements.
- **Supportive Blues (#004882, #001C38):** Employed for informational alerts, navigation sidebars, and footer sections to provide a professional "tech" contrast to the organic green.
- **Off-White Background (#F2F0EF):** A soft, low-glare foundation that improves long-term readability compared to pure white.
- **Functional Colors:** Use standard semantic reds for errors and ambers for warnings, ensuring they meet WCAG AA contrast ratios against the off-white background.

## Typography

This design system utilizes **Manrope** for its exceptional legibility and modern, geometric character that remains warm. 

- **Scale:** A modular scale ensures a clear hierarchy, helping users scan complex medical or administrative data.
- **Weight:** Use Semibold (600) and Bold (700) sparingly for emphasis and headers. Regular (400) is the standard for all body text to ensure maximum clarity on various screen types.
- **Accessibility:** Never use a font size smaller than 12px. Ensure a minimum contrast ratio of 4.5:1 for all text against its background.

## Layout & Spacing

The system uses a **Fluid Grid** model with a base-8 increment system.

- **Desktop (1440px+):** 12-column grid with 24px gutters and 40px side margins. Max-width content containers are capped at 1280px to prevent excessive line lengths.
- **Tablet (768px - 1024px):** 8-column grid with 24px gutters and 24px margins.
- **Mobile (Up to 767px):** 4-column grid with 16px gutters and 16px margins.
- **Rhythm:** Vertical spacing should be generous to allow the UI to "breathe," signaling a calm and non-urgent environment even during complex workflows.

## Elevation & Depth

This design system avoids heavy shadows, opting instead for **Tonal Layers** and **Low-Contrast Outlines** to define hierarchy.

- **Level 0 (Background):** The off-white background (#F2F0EF).
- **Level 1 (Cards/Surfaces):** Pure white (#FFFFFF) with a 1px border in a muted neutral (10% opacity of secondary color).
- **Level 2 (Interactive/Floating):** A very soft, diffused shadow (0px 4px 20px rgba(0, 28, 56, 0.08)) used only for dropdowns, modals, and active tooltips.
- **Interaction:** On hover, interactive cards should shift slightly in background color (e.g., a 2% darken) rather than increasing shadow depth, maintaining a flat and accessible profile.

## Shapes

The shape language is defined by **Soft Roundedness** (8px / 0.5rem) to evoke a friendly and approachable feel without appearing juvenile.

- **Components:** Buttons, input fields, and cards all share the 8px corner radius.
- **Nested Elements:** Elements within cards (like internal chips or images) should use a smaller radius (4px) to maintain visual harmony.
- **Full Rounding:** Only used for status indicators, notification badges, or "Pill" style tags to differentiate them from actionable buttons.

## Components

### Buttons
- **Primary:** Solid #008A40 with white text. 8px radius.
- **Secondary:** Outline 2px #008A40 with #008A40 text. 
- **Critical:** Solid #D32F2F for destructive actions.

### Input Fields
- White background with a 1px #001C38 (at 20% opacity) border. 
- Focused state: 2px border using the Primary Green.
- Labels are always positioned above the input field for maximum readability.

### Chips & Tags
- Used for categories (e.g., "Vaccination," "Appointed").
- Light tinted backgrounds (10% opacity of the category color) with high-contrast text.

### Cards
- Pure white background, 1px border, 8px radius. 
- Use cards to group related patient information or service options.

### Lists
- Clean, unboxed rows with 1px horizontal dividers. 
- High touch-target height (min 48px) for accessibility on mobile devices.

### Additional Components
- **Progress Steppers:** Used for multi-stage forms (like health registrations), utilizing the supportive blue to indicate "Step in Progress."
- **Status Banners:** Full-width alerts at the top of pages for system-wide announcements, using high-contrast supportive colors.