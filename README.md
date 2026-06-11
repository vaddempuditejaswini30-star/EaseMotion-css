# Horizontal Card Layout

## Overview

A responsive horizontal card component designed for displaying media, content, metadata, and actions in a compact side-by-side layout. The component includes multiple card variants and smooth interactions, making it suitable for dashboards, profiles, articles, and product listings.

## What does this do?

Adds a reusable horizontal card pattern that places visual content and textual information side-by-side for improved readability and faster content scanning.

## How is it used?

```html
<article class="horizontal-card">
  <div class="card-media">UI</div>

  <div class="card-content">
    <span class="card-kicker">Component Pattern</span>
    <h2>Card Title</h2>

    <p>
      Card description goes here.
    </p>

    <div class="card-footer">
      <span>Metadata</span>
      <a href="#">View Details</a>
    </div>
  </div>
</article>
```

## Features

* Responsive horizontal layout
* Standard, compact, and featured card variants
* Smooth hover lift animation
* Media zoom interaction on hover
* Status badge support
* Accessible focus states for keyboard users
* Dark mode support using `prefers-color-scheme`
* Clean and reusable component structure

## Why is it useful?

This component fits EaseMotion CSS by providing a reusable, scan-friendly card pattern that helps developers present information efficiently while maintaining a clean, modern, and responsive user experience. It is suitable for dashboards, activity feeds, profile cards, article previews, and product showcases.

## Files

* `demo.html` — Demonstrates multiple horizontal card variants.
* `style.css` — Contains the component styles, responsive behavior, and animations.
* `README.md` — Component documentation and usage guide.
