# VoluntEx Design Style Guide

## Design Philosophy

### Visual Language
**Modern Minimalism with Purpose**: Clean, uncluttered design that prioritizes user experience and accessibility. Every element serves a functional purpose while maintaining aesthetic elegance.

### Color Palette
**Primary Colors**:
- **Persian Blue** (#1E3A8A) - From your logo, used for primary CTAs and navigation
- **Soft white** (#FEFEFE) - Clean background for light mode
- **Charcoal** (#374151) - Primary text color for excellent contrast

**Secondary Colors**:
- **Sage Green** (#6B7280) - Secondary text and subtle accents
- **Warm Gray** (#F3F4F6) - Card backgrounds and subtle divisions
- **Accent Orange** (#F59E0B) - Highlights and success states (minimal use)

**Dark Mode Colors**:
- **Deep Navy** (#0F172A) - Primary background
- **Slate Gray** (#1E293B) - Card backgrounds
- **Light Gray** (#E2E8F0) - Primary text

### Typography
**Primary Font**: Inter (Sans-serif)
- Clean, modern, highly readable
- Excellent for both headings and body text
- Strong accessibility characteristics

**Font Hierarchy**:
- **Hero Headlines**: 3.5rem (56px), Bold
- **Section Headers**: 2.25rem (36px), Semibold  
- **Card Titles**: 1.25rem (20px), Medium
- **Body Text**: 1rem (16px), Regular
- **Small Text**: 0.875rem (14px), Regular

### Layout Principles
- **Grid System**: 12-column responsive grid
- **Spacing**: 8px base unit system (8, 16, 24, 32, 48, 64px)
- **Container Max Width**: 1200px
- **Mobile Breakpoints**: 640px, 768px, 1024px, 1280px

## Visual Effects & Styling

### Used Libraries & Effects
1. **Anime.js**: Smooth micro-interactions and form transitions
2. **Typed.js**: Typewriter effect for motto on homepage
3. **Splitting.js**: Text reveal animations for section headers
4. **ECharts.js**: Volunteer hours tracking visualization
5. **Splide.js**: Organization image carousels
6. **p5.js**: Subtle particle background effects
7. **Matter.js**: Interactive floating elements on hero section

### Animation Principles
- **Duration**: 200-400ms for micro-interactions
- **Easing**: Cubic-bezier for natural motion
- **Stagger**: 50ms delays for sequential animations
- **Hover States**: 150ms transitions with subtle scale (1.02x)

### Header Effects
**Hero Section Background**: 
- Subtle particle system using p5.js
- Floating geometric shapes in Persian Blue (20% opacity)
- Parallax scrolling effect on background elements

**Navigation**:
- Glass morphism effect with backdrop blur
- Smooth color transition on scroll
- Sticky positioning with shadow elevation

### Interactive Elements
**Buttons**:
- Primary: Persian Blue background, white text, subtle shadow
- Secondary: Transparent with Persian Blue border
- Hover: Gentle scale and shadow increase
- Active states with color shift

**Cards**:
- Clean white background with subtle border
- Hover: Lift effect with increased shadow
- 8px border radius for modern feel
- Smooth transitions on all interactive states

**Form Elements**:
- Clean borders with focus states in Persian Blue
- Floating labels with smooth animations
- Validation states with color coding
- Consistent padding and typography

### Background Treatment
**Consistent Background**: Soft white/light gray throughout all pages
- No section color changes
- Visual separation through subtle shadows and spacing
- Decorative elements on left/right edges (geometric shapes, 5% opacity)

### Image Treatment
**Photography Style**: 
- Bright, natural lighting
- Authentic volunteer moments
- Warm, inviting color temperature
- Consistent aspect ratios (16:9 for hero, 4:3 for cards)

**Logo Integration**:
- Persian Blue logo prominently displayed
- Consistent sizing across all pages
- Proper contrast against backgrounds

### Accessibility Features
- **Color Contrast**: Minimum 4.5:1 ratio for all text
- **Focus Indicators**: Clear, high-contrast focus rings
- **Alt Text**: Descriptive text for all images
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader**: Semantic HTML and ARIA labels

### Mobile Considerations
- **Touch Targets**: Minimum 44px for all interactive elements
- **Typography**: Responsive scaling for readability
- **Spacing**: Adequate padding for thumb navigation
- **Animations**: Reduced motion for performance

## Component Specifications

### Navigation Bar
- Height: 80px
- Background: Glass morphism with backdrop blur
- Logo: Left-aligned, 120px width
- Navigation: Center-aligned, 16px spacing
- Actions: Right-aligned (dark mode, language toggle)

### Hero Section
- Height: 70vh minimum
- Background: Particle system with gradient overlay
- Content: Center-aligned, max-width 800px
- CTA Button: Large, prominent, with hover animation

### Organization Cards
- Dimensions: 350px width, auto height
- Image: 16:9 aspect ratio, object-fit cover
- Content: Padding 24px, consistent spacing
- Hover: 3D tilt effect with information reveal

### Footer
- Background: Deep Navy (consistent across light/dark modes)
- Height: 200px
- Content: Center-aligned, copyright and links
- Typography: Small, high contrast

This design system ensures a cohesive, professional appearance while maintaining the modern, elegant aesthetic you requested. The Persian Blue from your logo serves as the foundation, creating a trustworthy and approachable brand presence that will resonate with both students and non-profit organizations.