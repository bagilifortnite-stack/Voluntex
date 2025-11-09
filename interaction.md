# VoluntEx Interaction Design

## Core User Journey
The website's primary interaction revolves around connecting students with meaningful volunteer opportunities based on their interests, grade level, and personal profile.

## Main Interactive Components

### 1. Student Matching System (Home Page)
**Primary Interaction**: "Are you ready to make real change?" questionnaire
- **Trigger**: Prominent call-to-action button on hero section
- **Process**: Multi-step form that captures:
  - Student's first and last name
  - Current grade level (dropdown: Grade 9-12)
  - Field of interest (dropdown with 8+ categories: Youth Services, Food Security, Animal Welfare, Mental Health, Senior Support, Environmental, Healthcare, Women's Services)
  - Personal "About Me" paragraph (textarea)
- **Result**: Dynamic display of matching organizations based on selected field
- **Follow-up**: Each matched organization shows as a card with quick details and "Learn More" button

### 2. Organization Filter & Search System (Charities Page)
**Primary Interaction**: Advanced filtering and search functionality
- **Filter Options**:
  - Cause Area (multi-select checkboxes)
  - Location (dropdown: York Region cities)
  - Age Requirements (slider or dropdown)
  - Commitment Level (radio buttons: One-time, Weekly, Monthly)
- **Search Bar**: Real-time text search across organization names and descriptions
- **Results Display**: Grid of organization cards with hover effects revealing quick info
- **Sorting Options**: Alphabetical, Distance, Newest Added

### 3. Interactive Organization Cards
**Hover Effects**: 
- 3D tilt effect revealing additional information
- Color overlay with mission statement preview
- "Quick Match" button showing compatibility percentage

**Click Actions**:
- Navigate to detailed organization page
- "Save to My Opportunities" (for future reference)
- "Contact Now" (opens contact form with pre-filled organization info)

### 4. Dark Mode Toggle
**Location**: Top navigation bar
**Functionality**: 
- Smooth transition between light/dark themes
- Persistent preference using localStorage
- Affects all pages and components

### 5. Language Toggle (English/French)
**Location**: Next to dark mode toggle
**Functionality**:
- Seamless content switching without page reload
- French translations for all core content
- Maintains user session and form data

## Secondary Interactive Elements

### 6. Team Member Profile Cards (About Page)
- Hover effects revealing member roles and fun facts
- Click to expand full biography
- Social media links with animated icons

### 7. Contact Form with Validation
- Real-time form validation with visual feedback
- Success/error animations
- Auto-complete for common fields
- File upload for resumes or additional documents

### 8. Volunteer Hours Tracker (Bonus Feature)
- Simple calculator for tracking volunteer hours
- Progress visualization toward 40-hour requirement
- Achievement badges for milestones

## User Flow Examples

### Student Seeking Animal Welfare Opportunities:
1. Lands on homepage, sees "Are you ready to make real change?"
2. Clicks CTA button, begins questionnaire
3. Enters name, selects Grade 11, chooses "Animal Welfare"
4. Writes brief about me paragraph
5. System displays 6 matching organizations (Ontario SPCA, Etobicoke Humane Society, etc.)
6. Clicks on Ontario SPCA card to view detailed page
7. Reviews requirements, clicks "Contact Now"
8. Fills contact form with specific interest

### Organization Representative:
1. Navigates to Charities page
2. Uses filters to find similar organizations
3. Clicks on organization cards to see detailed templates
4. Uses "Add Your Organization" button (future feature)

## Technical Implementation Notes
- All interactions use vanilla JavaScript with smooth animations
- Form data temporarily stored in sessionStorage
- Responsive design ensures mobile-friendly interactions
- Accessibility features include keyboard navigation and screen reader support
- No external APIs required - all data stored locally

## Success Metrics
- Students can complete matching questionnaire in under 3 minutes
- Organization filtering returns relevant results within 2 seconds
- All interactive elements provide immediate visual feedback
- Mobile interactions feel natural and intuitive