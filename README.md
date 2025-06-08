
# Product Preview Card | Frontend Mentor

[![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-Solution-blue)](https://www.frontendmentor.io/solutions/product-preview-card-with-responsive-image-switching-3JvQZ4X2T6)


[![Responsive Preview](https://img.shields.io/badge/Responsive-Yes-green)](https://your-live-demo-url.com)

<div align="center">
  <img src="./images/screenshot.png" alt="Article Listing Preview" width="600">
</div>


A responsive product card component featuring:
- Mobile/desktop image switching
- Fluid typography
- Interactive button
- Accessible pricing

## Features
✅ Responsive `<picture>` element  
✅ CSS clamp() for fluid sizing  
✅ Semantic HTML5  
✅ Hover states  
✅ Mobile-first workflow  

## Tech Stack
- **HTML5**: Semantic structure
- **CSS3**: Flexbox, clamp(), media queries
- **Fonts**: Google Fonts (Fraunces, Montserrat)

## Key Code
```html
<picture>
  <source media="(min-width:37rem)" srcset="image-product-desktop.jpg">
  <img src="image-product-mobile.jpg" alt="Perfume bottle">
</picture>
```

```css
/* Fluid typography */
.title {
  font-size: clamp(1.5rem, 1.071vw + 1.286rem, 2.25rem);
}

/* Responsive layout */
@media (min-width: 37rem) {
  main {
    flex-direction: row;
  }
}
```

## How to Run
1. Clone repo
2. Open `index.html` in browser
3. Resize window to see responsive changes

## Author
[Krowey Richmond Borquaye](https://github.com/77Kromo)  
[Live Demo](https://your-demo-url.com) | [Solution](https://www.frontendmentor.io/solutions/your-solution-id)