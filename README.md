# Responsive UI Project

A modern, responsive web UI built with HTML and CSS, featuring dynamic layout changes based on screen size. The layout adapts gracefully from mobile phones to large desktops using media queries and flexible design patterns.

## 🚀 Features

- Fully responsive layout
- Flexbox-based grid system
- Adaptive spacing and alignment for different devices
- Components include:
  - Header section
  - Cards with overlay/positioning
  - Chip containers
  - Chat box
  - Configure button

## 🛠️ Technologies Used

- HTML5
- CSS3
- Media Queries (Mobile-first approach)
- Flexbox

## 📱 Responsive Breakpoints

The design responds to the following screen widths:

| Device Size        | Breakpoint        |
|--------------------|-------------------|
| Extra small (phones) | `< 576px`        |
| Small (tablets)     | `≥ 576px`         |
| Medium (landscape tablets) | `≥ 768px` |
| Large (desktops)    | `≥ 992px`         |
| Extra large (large desktops) | `≥ 1200px` |

## 💡 Media Query Example

```css
@media (max-width: 575.98px) {
  .container-heading {
    flex-direction: column;
    gap: 1rem;
  }
}
