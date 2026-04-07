# Digital System for Personalized mRNA Vaccine Compatibility Assessment - Login Page Specification

## 1. Project Overview
- **Project Name**: Digital System for Personalized mRNA Vaccine Compatibility Assessment
- **Project Type**: Login Page (Single Page Web Application)
- **Core Functionality**: A professional login interface for a biomedical AI system
- **Target Users**: Researchers, medical professionals, healthcare administrators

## 2. UI/UX Specification

### Layout Structure
- **Page Sections**:
  - Background layer with animated molecular graphics
  - Main container centered vertically and horizontally
  - Login card with glassmorphism effect
  - Footer at bottom
- **Layout**: Flexbox, centered content
- **Responsive Breakpoints**:
  - Mobile: < 640px (card fills 90% width)
  - Tablet: 640px - 1024px (card 420px width)
  - Desktop: > 1024px (card 460px width)

### Visual Design

#### Color Palette
- **Primary**: `#4F90D4` (Soft Blue)
- **Secondary**: `#8B7EC9` (Light Purple)
- **Accent Gradient**: `linear-gradient(135deg, #4F90D4 0%, #8B7EC9 50%, #B87CD6 100%)`
- **Background Base**: `#F0F4FA` (Very Light Blue-Gray)
- **Card Background**: `rgba(255, 255, 255, 0.7)` (Glassmorphism)
- **Text Primary**: `#1E3A5F` (Dark Navy Blue)
- **Text Secondary**: `#5A7A9A` (Muted Blue-Gray)
- **Input Background**: `rgba(255, 255, 255, 0.9)`
- **Input Border**: `rgba(79, 144, 212, 0.3)`
- **Button Gradient**: `linear-gradient(135deg, #4F90D4 0%, #6B8DD4 100%)`
- **Button Hover**: `linear-gradient(135deg, #6B8DD4 0%, #8B7EC9 100%)`

#### Typography
- **Font Family**: 
  - Headings: 'Outfit', sans-serif (Google Fonts)
  - Body: 'DM Sans', sans-serif (Google Fonts)
- **Title**: 28px, font-weight 700
- **Subtitle**: 15px, font-weight 400
- **Input Labels**: 14px, font-weight 500
- **Button**: 16px, font-weight 600
- **Links**: 14px, font-weight 500

#### Spacing System
- **Card Padding**: 48px
- **Input Gap**: 20px
- **Button Margin Top**: 28px
- **Border Radius (Card)**: 24px
- **Border Radius (Inputs)**: 12px
- **Border Radius (Button)**: 12px

#### Visual Effects
- **Card Shadow**: `0 25px 50px -12px rgba(79, 144, 212, 0.15)`
- **Input Focus Shadow**: `0 0 0 4px rgba(79, 144, 212, 0.15)`
- **Glassmorphism Blur**: `backdrop-filter: blur(20px)`
- **Floating Animation**: Subtle up-down float on decorative elements

### Components

#### Logo/Title Section
- App icon: Stylized DNA/molecule icon (SVG)
- Main title: "Digital System for Personalized mRNA Vaccine Compatibility Assessment"
- Subtitle: "AI-powered personalized vaccine safety analysis"
- Centered above login card

#### Login Card
- Glassmorphism background with blur
- Contains: Email input, Password input, Remember me, Forgot password, Login button

#### Input Fields
- Email: With envelope icon
- Password: With lock icon, toggle visibility eye icon
- States: Default, Focus (blue glow), Error (red border)
- Placeholder text in light gray

#### Login Button
- Full width
- Gradient background
- Hover: Slight lift + gradient shift
- Active: Scale down slightly
- Loading state: Spinner animation

#### Animated Background Elements
- Floating DNA helix shapes (CSS animated)
- Small nanoparticle circles
- Subtle gradient orbs moving slowly
- All elements with low opacity to not distract

#### Footer
- Text: "Research Prototype | Biomedical AI System"
- Small, muted text at bottom of page
- Centered

## 3. Functionality Specification

### Core Features
1. **Email Input**: Validates email format, shows error for invalid
2. **Password Input**: Toggle visibility button, minimum 6 characters
3. **Remember Me**: Checkbox functionality (stores preference in localStorage)
4. **Forgot Password**: Link (placeholder href)
5. **Login Button**: 
   - Shows loading spinner on click
   - Simulates 2-second authentication
   - Shows success/error message

### User Interactions
- Tab navigation between inputs
- Enter key submits form
- Input focus states with smooth transitions
- Button hover/active states

### Edge Cases
- Empty field submission shows validation messages
- Invalid email format shows error
- Password < 6 characters shows error
- Network error simulation shows retry option

## 4. Acceptance Criteria

### Visual Checkpoints
- [ ] Background has animated molecular/DNA elements
- [ ] Login card has glassmorphism effect with blur
- [ ] Color scheme is soft blue, white, light purple
- [ ] All elements have rounded corners (12-24px)
- [ ] Shadows are soft and subtle
- [ ] Typography is clean and professional
- [ ] Responsive on mobile, tablet, desktop

### Functional Checkpoints
- [ ] Email input accepts and validates email format
- [ ] Password field has visibility toggle
- [ ] Login button shows loading animation on click
- [ ] Form validation works for empty/invalid inputs
- [ ] Remember me checkbox is functional
- [ ] Smooth animations throughout

### Professional Requirements
- [ ] Looks suitable for university major project
- [ ] Professional enough for research prototype demo
- [ ] Clean, minimalistic medical AI aesthetic

