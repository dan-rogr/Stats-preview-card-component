# Stats Preview Card Component

A responsive card component that displays business analytics statistics with a clean, modern layout that adapts across desktop, tablet, and mobile screen sizes.

---

## Overview

This component features:

- A headline with highlighted text
- A descriptive paragraph
- Three statistical metrics
- A responsive image with a color overlay
- A layout that adapts to desktop, tablet, and mobile screens

The component was designed to be visually balanced and user-friendly, ensuring a smooth experience across all devices.

---

## Built With

- HTML5
- CSS3
- CSS Grid
- Flexbox
- Media Queries
- Google Fonts (Inter)

---

## Approach

### Layout Structure

The main layout was built using **CSS Grid** to divide the card into two sections: the text content and the image. This enabled a clean two-column layout on desktop while staying flexible for smaller screens. The card is centered vertically on the page for consistent alignment across devices.

### Image Overlay

The purple overlay effect was achieved using positioning and layering techniques, applying the color without modifying the original image — keeping the design flexible and reusable.

### Typography & Styling

- **Font:** Inter (Google Fonts) for a modern, readable look.
- **Colors:** Defined using HSL values for consistency and easy customization.
- **Spacing:** Carefully applied to maintain visual balance across all sections.

### Statistics Section

The statistics section uses **Flexbox** to distribute the three metrics evenly, ensuring proper alignment and spacing. Each stat includes a number and a label, maintaining clear readability and visual hierarchy.

### Responsive Design

The layout is fully responsive using media queries:

| Breakpoint  | Behavior                                                                   |
| ----------- | -------------------------------------------------------------------------- |
| **Desktop** | Two-column grid layout, full font sizes                                    |
| **Tablet**  | Two-column layout maintained, font sizes and spacing slightly reduced      |
| **Mobile**  | Single column, image moves to top, text centered, stats stacked vertically |

---

## What I Learned

Through this project, I strengthened my skills in:

- CSS Grid layout design
- Flexbox alignment
- Responsive design techniques
- Layout organization
- Creating overlays with CSS
- Typography and spacing

---

## Author

**Daniel Rojas**
