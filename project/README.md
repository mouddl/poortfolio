# My Portfolio Website

A simple static website built with HTML and CSS.

![Site Preview](img.png)

## How to Run

No setup needed. Just open `index.html` in your browser and you're good to go.

## How it's Built

Started with HTML and structured the page by splitting everything into sections, each with its own `id` so they're easy to target and style.

For the CSS, I kept things clean by declaring 3 CSS variables at the top in `:root`:
```css
:root {
    --primary: #667eea;
    --dark: #2c3e50;
    --light: #f5f5f5;
}
```

Then used those variables throughout the stylesheet instead of hardcoding colors everywhere — makes it much easier to tweak the theme later.