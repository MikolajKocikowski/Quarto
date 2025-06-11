## Quarto Gallery Layout Examples

This repo contains simple Quarto `.qmd` scripts for experimenting with website photo gallery layouts - mainly focused on mimicking masonry-style layouts.

### Files

- `faux-photo-masonry-css.qmd`  
  A CSS approach using `column-count`, simple and clean but stacks images top-to-bottom, column by column.

- `round-robin-photo-masonry-js.qmd`  
  Uses GPT-aided JavaScript that assigns images in round-robin order across columns, giving me ontrol over which image appears in each visual row.

### Preview

<p float="left">
  <img src="css.png" width="45%" alt="CSS column-count layout"/>
  <img src="js.png" width="45%" alt="JS round-robin layout"/>
</p>

### Preview

<div style="display: flex; gap: 1em; align-items: flex-start;">
  <img src="css.png" width="45%" alt="CSS column-count layout"/>
  <img src="js.png" width="45%" alt="JS round-robin layout"/>
</div>
