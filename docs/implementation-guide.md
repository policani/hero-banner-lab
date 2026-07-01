# Implementation Guide

Hero Banner Lab is intentionally static. The page needs only HTML, CSS, and JavaScript.

## Embed Shape

Use a full-screen stage for consistent screenshots and predictable first-viewport composition:

```html
<section class="hero-stage">
  <div class="banner-renderer"></div>
  <div class="hero-copy">
    <p>Eyebrow text</p>
    <h1>Hero headline</h1>
    <p>Supporting copy.</p>
  </div>
</section>
```

Recommended stage sizing:

```css
.hero-stage {
  position: relative;
  height: 100vh;
  min-height: 680px;
  overflow: hidden;
}
```

## Capture Workflow

Open a sample with `capture=1` at the same viewport size for each banner:

```text
index.html?banner=signal&capture=1
index.html?banner=decision-gates&capture=1
index.html?banner=filament-network&capture=1
```

Use the same browser viewport, such as 1600x900 or 1920x1080, for every capture.

## Public-Safe Defaults

Keep default labels synthetic and generic. Replace visible hero copy and any sample data before embedding a banner in a real public page.
