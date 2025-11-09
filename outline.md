# VoluntEx Project Outline

## File Structure
```
/mnt/okcomputer/output/
├── index.html              # Homepage with motto and student matching
├── about.html              # Team information and organization background
├── charities.html          # Organization listings with filtering
├── contact.html            # Contact form and information
├── main.js                 # Core JavaScript functionality
├── resources/              # Media assets folder
│   ├── hero-volunteers.jpg # Generated hero image
│   ├── team-*.jpg          # Team member photos (searched)
│   ├── org-*.jpg           # Organization images (searched)
│   ├── logo.png            # Persian Blue logo (uploaded)
│   └── bg-particles.js     # Particle background system
├── interaction.md          # Interaction design document
├── design.md              # Design style guide
└── outline.md             # This file
```

## Page Specifications

### 1. index.html - Homepage
**Purpose**: Engage visitors with motto and enable student-organization matching

**Sections**:
- **Navigation Bar**: Logo, menu items, dark mode toggle, language switcher
- **Hero Section**: 
  - Background: Particle system with generated hero image
  - Typewriter animation: "Are you ready to make real change?"
  - Subtitle about connecting students with meaningful volunteer opportunities
  - Primary CTA button leading to matching questionnaire
- **Student Matching System**:
  - Multi-step form with smooth transitions
  - Fields: Name, Grade, Field of Interest, About Me
  - Dynamic results showing matching organizations
  - Organization cards with hover effects and "Learn More" buttons
- **Statistics Section**: 
  - Animated counters: Students matched, Organizations partnered, Volunteer hours completed
  - Visual representation using ECharts
- **How It Works**: 3-step process visualization
- **Featured Organizations**: Carousel of highlighted charities
- **Footer**: Copyright and essential links

### 2. about.html - About Us
**Purpose**: Build trust and showcase team behind VoluntEx

**Sections**:
- **Navigation Bar**: Consistent with homepage
- **Hero Section**: Smaller banner with team photo
- **Our Story**: 
  - Background on Ontario's 40-hour graduation requirement
  - Problem statement about superficial volunteering
  - Mission to create meaningful connections
- **Team Section**:
  - Grid of team member cards with hover effects
  - Each card: Photo, name, role, brief bio, social links
  - Search for diverse, professional team photos
- **Our Values**: Visual representation of core principles
- **Impact Metrics**: Success stories and achievements
- **Partners**: Logos of key non-profit partners
- **Footer**: Consistent with other pages

### 3. charities.html - Organization Directory
**Purpose**: Comprehensive listing of non-profit partners with advanced filtering

**Sections**:
- **Navigation Bar**: Consistent design
- **Search & Filter Panel**:
  - Text search with real-time results
  - Cause area filters (multi-select checkboxes)
  - Location filters (York Region cities)
  - Age requirement sliders
  - Sort options (alphabetical, distance, newest)
- **Results Grid**: 
  - Masonry layout of organization cards
  - Each card: Logo, name, cause area, brief description, contact info
  - Hover effects revealing additional details
  - "View Details" buttons leading to individual pages
- **Map View**: Optional toggle showing organization locations
- **Pagination**: Load more functionality with smooth animations
- **Add Organization**: CTA for non-profits to join (leads to contact form)

### 4. contact.html - Contact & Support
**Purpose**: Enable communication and provide support resources

**Sections**:
- **Navigation Bar**: Consistent design
- **Contact Options**:
  - General inquiry form
  - Organization partnership form
  - Student support form
  - Technical support form
- **Contact Information**:
  - Email addresses for different purposes
  - Office location (if applicable)
  - Response time expectations
- **FAQ Section**:
  - Common questions for students
  - Organization onboarding process
  - Technical support topics
- **Help Resources**:
  - Volunteer hour tracking guide
  - Tips for meaningful volunteering
  - Ontario graduation requirements explanation
- **Live Chat**: Simulated chat widget for immediate assistance

### 5. Individual Organization Pages (Template)
**Purpose**: Detailed information about specific non-profits

**Dynamic Content**:
- Organization name and logo
- Mission statement and values
- Detailed volunteer opportunities
- Requirements and time commitments
- Contact information and application process
- Photo gallery of volunteer activities
- Success stories and testimonials
- Interactive "Apply Now" button

## Interactive Components

### 1. Student Matching System
- **Location**: Homepage
- **Functionality**: Multi-step form with validation
- **Data**: Uses organization data from Excel file
- **Output**: Filtered list of relevant organizations

### 2. Advanced Filtering System
- **Location**: Charities page
- **Functionality**: Real-time filtering with multiple criteria
- **Data**: All 25 organizations from spreadsheet
- **Output**: Dynamically updated grid of results

### 3. Dark Mode Toggle
- **Location**: Navigation bar (all pages)
- **Functionality**: Smooth theme switching
- **Persistence**: LocalStorage to remember preference
- **Scope**: Affects all pages and components

### 4. Language Toggle
- **Location**: Navigation bar (all pages)
- **Functionality**: English/French content switching
- **Implementation**: JSON-based translation system
- **Scope**: All static content, form labels, navigation

### 5. Volunteer Hours Tracker
- **Location**: Contact/Support page
- **Functionality**: Simple calculator with visual progress
- **Features**: Track hours, show progress toward 40-hour goal
- **Visualization**: Animated progress bar with ECharts

## Content Requirements

### Text Content
- **Homepage**: ~800 words across all sections
- **About Page**: ~1200 words including team bios
- **Charities Page**: ~300 words plus organization descriptions
- **Contact Page**: ~500 words including FAQ content

### Visual Content
- **Hero Image**: Generated image of diverse volunteers
- **Team Photos**: 6-8 searched professional headshots
- **Organization Images**: 3-4 images per organization category
- **Background Elements**: Subtle geometric patterns
- **Icons**: Custom SVG icons for consistency

### Data Content
- **Organizations**: All 25 from Excel file, categorized and formatted
- **Cause Areas**: 8 main categories with subcategories
- **Location Data**: York Region cities and postal codes
- **Success Metrics**: Realistic statistics for impact visualization

## Technical Implementation

### Core Libraries Integration
1. **Anime.js**: Form transitions, button animations, page transitions
2. **Typed.js**: Homepage motto typewriter effect
3. **Splitting.js**: Text reveal animations for section headers
4. **ECharts.js**: Statistics visualization and progress tracking
5. **Splide.js**: Image carousels and testimonials
6. **p5.js**: Particle background system for hero section
7. **Matter.js**: Floating elements for visual interest

### Responsive Design
- **Mobile First**: Progressive enhancement approach
- **Breakpoints**: 640px, 768px, 1024px, 1280px
- **Touch Optimization**: 44px minimum touch targets
- **Performance**: Optimized images and lazy loading

### Accessibility Features
- **WCAG 2.1 AA Compliance**: Color contrast, keyboard navigation
- **Screen Reader Support**: Semantic HTML, ARIA labels
- **Focus Management**: Clear focus indicators
- **Reduced Motion**: Respects user preferences

This comprehensive outline ensures we deliver a professional, feature-rich website that meets all your requirements while maintaining the modern, elegant aesthetic you've requested. Each page serves a specific purpose in the student-volunteer matching journey, with interactive elements that create an engaging user experience.