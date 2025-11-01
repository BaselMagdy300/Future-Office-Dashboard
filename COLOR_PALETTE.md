# Modern Color Palette for Future Construction Management System

## Overview
A sophisticated, minimal color scheme based on the architecture brand's gold tone logo (#C1B283), designed for elegance and professionalism.

---

## Primary Colors

### Gold (from logo)
- **Primary**: `#C1B283` - Main brand color
- **Primary Dark**: `#A89C6F` - Hover states, emphasis
- **Primary Light**: `#D4C89A` - Subtle highlights
- **Primary Lighter**: `#E3DABC` - Soft backgrounds
- **Primary Lightest**: `#F5F1E6` - Ultra-light backgrounds

---

## Complementary Colors

### Cool Accent Gray-Blue
- **Accent**: `#4A5568` - Secondary actions, borders
- **Accent Dark**: `#2D3748` - Deep contrast
- **Accent Light**: `#718096` - Disabled states, placeholders

---

## Neutrals

### Backgrounds
- **Primary**: `#FAFAF9` - Main page background
- **Secondary**: `#FFFFFF` - Cards, panels
- **Tertiary**: `#F5F5F4` - Subtle elevations

### Text
- **Primary**: `#1F2937` - Main content
- **Secondary**: `#6B7280` - Supporting text
- **Tertiary**: `#9CA3AF` - Muted text
- **Inverse**: `#FFFFFF` - Text on colored backgrounds

---

## Semantic Colors

### Success
- **Success**: `#10B981` - Green
- **Success Light**: `#D1FAE5` - Light backgrounds

### Error
- **Error**: `#EF4444` - Red
- **Error Light**: `#FEE2E2` - Light backgrounds

### Warning
- **Warning**: `#F59E0B` - Amber
- **Warning Light**: `#FEF3C7` - Light backgrounds

### Info
- **Info**: `#3B82F6` - Blue
- **Info Light**: `#DBEAFE` - Light backgrounds

---

## Shadows & Borders

### Shadows
- **sm**: Subtle elevation
- **base**: Standard elevation
- **md**: Medium elevation
- **lg**: High elevation

### Borders
- **Default**: `#E5E7EB`
- **Light**: `#F3F4F6`

---

## Design Principles

### 1. **Hierarchy**
- Primary gold for main actions and active states
- Accent gray-blue for secondary actions
- Neutrals for backgrounds and borders

### 2. **Contrast**
- Minimum 4.5:1 ratio for text readability
- Gold on white for primary actions
- White on gold for active states

### 3. **Modern & Minimal**
- Clean, professional aesthetic
- Architectural precision
- Elegant simplicity

### 4. **Accessibility**
- WCAG AA compliant
- Clear visual hierarchy
- High contrast combinations

---

## Usage Examples

### Navigation
- **Active**: Primary gold (#C1B283) with white text
- **Inactive**: Light gray background (#F5F5F4) with dark text
- **Hover**: Subtle gold tint

### Buttons
- **Primary**: Gold (#C1B283) with white text
- **Secondary**: White with accent gray (#4A5568) border

### Cards
- **Background**: White (#FFFFFF)
- **Border**: Light gray (#E5E7EB)
- **Shadow**: Subtle elevation for depth

### Messages
- Use semantic colors (success/error/warning) for context

---

## CSS Variables

All colors are available as CSS variables in `:root`:

```css
:root {
  --primary: #C1B283;
  --primary-dark: #A89C6F;
  --primary-light: #D4C89A;
  --primary-lighter: #E3DABC;
  --primary-lightest: #F5F1E6;
  /* ... and more */
}
```

---

## Custom Classes

### Backgrounds
- `.bg-brand-primary` - Main background
- `.bg-brand-gradient` - Gradient background

### Buttons
- `.btn-primary` - Primary gold button
- `.btn-secondary` - Secondary outlined button

### Cards
- `.card` - Standard card styling

### Navigation
- `.nav-active` - Active navigation state
- `.nav-inactive` - Inactive navigation state

---

## Implementation Notes

- Uses system fonts for performance and consistency
- Smooth transitions for interactive elements
- Responsive design principles
- RTL language support

