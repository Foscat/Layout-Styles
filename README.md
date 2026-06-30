# Layout Styles

**Layout Styles** is a responsive CSS layout library for building flexible, style-aware web app templates. It provides a shared class contract for common layout primitives while allowing each layout style to dramatically alter structure, rhythm, density, spacing, and page composition.

The library is designed to work alongside **`ui-style-kit-css@2.0.1`**, keeping visual UI styling and layout behavior separate but compatible. This makes it possible to combine UI styles, layout styles, themes, and modes freely.

```html
<body
  data-ui="cyberpunk"
  data-layout="maximalist"
  data-theme="arctic-indigo"
  data-mode="dark"
>
```

Use it to rapidly prototype or deploy distinct app experiences from the same underlying markup.

## Core idea

Layout Styles separates **how a page is arranged** from **how a page is visually themed**.

* `ui-style-kit-css` controls visual presentation, color systems, surfaces, and UI personality.
* `layout-styles` controls page structure, spacing, responsive flow, shell behavior, grids, sections, panels, and composition.

That separation allows a template app to support many design combinations without maintaining separate page implementations.

## Suggested tagline

**One markup structure. Many layout personalities.**

