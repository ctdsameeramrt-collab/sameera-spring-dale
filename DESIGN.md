---
name: Sameera Spring Dale
colors:
  surface: '#f4fafd'
  surface-dim: '#d4dbdd'
  surface-bright: '#f4fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef5f7'
  surface-container: '#e8eff1'
  surface-container-high: '#e2e9ec'
  surface-container-highest: '#dde4e6'
  on-surface: '#161d1f'
  on-surface-variant: '#414844'
  inverse-surface: '#2b3234'
  inverse-on-surface: '#ebf2f4'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#645d55'
  on-secondary: '#ffffff'
  secondary-container: '#ebe1d6'
  on-secondary-container: '#6a635b'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#ebe1d6'
  secondary-fixed-dim: '#cec5bb'
  on-secondary-fixed: '#1f1b14'
  on-secondary-fixed-variant: '#4c463e'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f4fafd'
  on-background: '#161d1f'
  surface-variant: '#dde4e6'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  unit-xs: 4px
  unit-sm: 8px
  unit-md: 16px
  unit-lg: 32px
  unit-xl: 64px
---

## Brand & Style
The design system is rooted in the intersection of nature-inspired tranquility and high-end residential living. It balances **Minimalism** with subtle **Glassmorphism** to create an interface that feels both grounded and ethereal. The visual narrative emphasizes trust, transparency, and the premium nature of the "Spring Dale" property.

The target audience consists of discerning homeowners and investors looking for stability and luxury. To evoke an emotional response of security and refinement, the system utilizes expansive whitespace, high-quality architectural photography, and a sophisticated typographic hierarchy.

## Colors
The palette is dominated by **Deep Forest Green**, which serves as the anchor for primary actions and brand identity, symbolizing growth and the lush environment of the estate. **Champagne** is used as a sophisticated background alternative for sections and secondary containers to soften the visual experience.

**Subtle Gold** is reserved strictly for trust indicators, such as RERA/DTCP approvals and premium highlights, ensuring they remain prestigious without becoming gaudy. The background remains predominantly off-white (#FAFAFA) to maintain a modern, airy feel.

## Typography
The typography strategy employs a high-contrast pairing. **Playfair Display** provides an authoritative, editorial feel for headlines, reminiscent of luxury real estate brochures. **Inter** is utilized for all functional and body text to ensure maximum legibility and a contemporary, systematic feel.

For mobile devices, headline sizes scale down aggressively to maintain layout integrity while preserving their characteristic serif elegance. Labels and captions use increased letter spacing and uppercase styling to denote metadata and trust categories.

## Layout & Spacing
The design system utilizes a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. Spacing is intentional and generous, favoring large "breathing rooms" (64px+) between major sections to emphasize the premium nature of the brand.

Content containers are centered with a maximum width of 1280px. Internal card padding should consistently use the `unit-lg` (32px) value to maintain a sense of luxury. Vertical rhythm is driven by an 8px base grid, ensuring all components align with mathematical precision.

## Elevation & Depth
Depth is created through a mix of **Ambient Shadows** and **Glassmorphism**. 
- **Surface Level:** The base background is flat off-white.
- **Card Level:** Uses a very soft, diffused shadow (0px 10px 30px rgba(27, 67, 50, 0.04)) to create a gentle lift without looking heavy.
- **Overlays:** Navigation bars and image captions use a glassmorphism effect (Backdrop Blur: 12px, Background: rgba(255, 255, 255, 0.7)) to maintain context of the underlying photography.
- **Interactive Level:** On hover, primary elements should see a slight increase in shadow spread and a subtle upward translation (-4px).

## Shapes
This design system utilizes a highly rounded visual language to communicate approachability and modern luxury. All primary containers and image wrappers use a **1.5rem (24px)** corner radius (`rounded-xl` / `rounded-2xl` equivalent). Smaller interactive components like buttons and input fields follow a **0.5rem (8px)** radius to maintain a crisp, professional edge within the softer layout.

## Components

### Buttons
- **Primary:** Solid Deep Forest Green (#1B4332) with white text. High-contrast, bold, used for "Book a Site Visit."
- **Secondary:** Outlined in Deep Forest Green or Solid Champagne (#F5EBE0) with Green text. Used for "Download Brochure."
- **Specialized Contact:** 
    - **WhatsApp:** Solid Brand Green (#25D366) with a white icon.
    - **Call:** Neutral dark slate or soft blue-gray to remain professional but distinct.

### Cards
Real estate listing cards should feature a full-bleed image at the top with a 24px radius. Content area should have generous padding, utilizing Playfair Display for the price and Inter for the property specs (BHK, Sq.Ft).

### Badges & Status
- **Trust Badges (RERA/DTCP):** Use a subtle Gold (#D4AF37) border or background with a semi-bold Inter label. Icons should be minimal and professional.
- **Approval Badges:** Bank logos should be presented in a grayscale treatment until hovered to maintain the clean aesthetic.

### Input Fields
Forms use a minimal "Floating Label" style. The bottom border is emphasized in Deep Forest Green when focused. Error states use a soft terracotta rather than a harsh red to keep the palette harmonious.