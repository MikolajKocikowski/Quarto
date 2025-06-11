## Quarto Gallery Layout Examples

This repo contains simple Quarto `.qmd` scripts for experimenting with a website photo gallery - mainly focused on mimicking masonry-style layouts.

### Files

-  `faux-photo-masonry-css.qmd`  
  A CSS approach using `column-count`, simple and clean but stacks images top-to-bottom, column by column.

- `round-robin-photo-masonry-js.qmd`  
  Uses GPT-aided JavaScript that assigns images in round-robin order across columns, giving me ontrol over which image appears in the first row etc.

### Optional: Hover Zoom Effect

You can add a smooth zoom on hover to all images in your gallery by extending the CSS like below. Increasing the number for scale() too high can quickly make the effect annoying:

```
.masonry img {
  transition: transform 0.2s;
}

.masonry img:hover {
  transform: scale(1.05);
}
```

### Preview – CSS Approach

<img src="assets/css.png" width="300" alt="CSS layout">

### Preview – JS Approach

<img src="assets/js.png" width="300" alt="JS layout">
