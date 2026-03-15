# Muralikrishnan.net Theme Template

A boutique dark theme with gold accents — premium editorial aesthetic.

---

## CSS Variables (Copy into your CSS)

```css
:root {
    /* Backgrounds */
    --bg-deep: #050507;
    --bg-primary: #0a0a0d;
    --bg-elevated: #111115;
    --bg-card: #18181d;
    
    /* Text */
    --text-primary: #f4f4f5;
    --text-secondary: #a1a1aa;
    --text-muted: #6b6b70;
    
    /* Accent (Gold) */
    --accent: #c9a962;
    --accent-subtle: rgba(201, 169, 98, 0.12);
    --accent-soft: rgba(201, 169, 98, 0.4);
}
```

---

## Color Palette

| Name | Hex | Usage |
|------|-----|-------|
| **bg-deep** | `#050507` | Page background, deepest layer |
| **bg-primary** | `#0a0a0d` | Main background |
| **bg-elevated** | `#111115` | Cards, nav, elevated surfaces |
| **bg-card** | `#18181d` | Content cards, sections |
| **text-primary** | `#f4f4f5` | Headings, main text |
| **text-secondary** | `#a1a1aa` | Body text, descriptions |
| **text-muted** | `#6b6b70` | Captions, metadata |
| **accent** | `#c9a962` | Primary accent (gold) |
| **accent-subtle** | `rgba(201, 169, 98, 0.12)` | Hover backgrounds, subtle highlights |
| **accent-soft** | `rgba(201, 169, 98, 0.4)` | Glows, shadows |

---

## Typography

### Font Families
- **Headings:** Cormorant Garamond (serif) — elegant, editorial
- **Body:** Outfit (sans-serif) — clean, modern

### Font Sizes
```css
--font-hero: 2.5rem;
--font-h1: 1.75rem;
--font-h2: 1.35rem;
--font-h3: 1.1rem;
--font-body: 0.95rem;
--font-small: 0.8rem;
--font-caption: 0.7rem;
```

---

## Common Effects

### Gold Border
```css
border: 1px solid var(--accent);
```

### Gold Glow
```css
box-shadow: 0 0 20px var(--accent-soft), 0 0 40px rgba(201, 169, 98, 0.3);
```

### Gradient Background (Nav)
```css
background: linear-gradient(180deg, var(--bg-deep) 0%, var(--bg-deep) 80%, transparent 100%);
```

### Fade Animation
```css
@keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}
```

---

## Quote Card Template (For Quote Cards)

```html
<div style="
    background: #18181d;
    border-left: 3px solid #c9a962;
    padding: 1.5rem;
    border-radius: 0 0.5rem 0.5rem 0;
    font-family: 'Cormorant Garamond', serif;
">
    <p style="
        color: #f4f4f5;
        font-size: 1.1rem;
        font-style: italic;
        line-height: 1.7;
        margin: 0 0 0.75rem 0;
    ">Your quote here.</p>
    <p style="
        color: #c9a962;
        font-size: 0.8rem;
        font-family: 'Outfit', sans-serif;
        margin: 0;
    ">— Source Name</p>
</div>
```

---

## Button Template

```html
<a href="#" style="
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background: #c9a962;
    color: #050507;
    font-family: 'Outfit', sans-serif;
    font-weight: 600;
    font-size: 0.85rem;
    border-radius: 2rem;
    text-decoration: none;
    box-shadow: 0 4px 20px rgba(201, 169, 98, 0.4);
    transition: all 0.3s ease;
;">Button Text</a>
```

---

## Icon Style (Gold Stroke)

```html
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#c9a962" stroke-width="1.5">
    <!-- Your icon path here -->
</svg>
```

---

## Card Template

```html
<div style="
    background: #18181d;
    border: 1px solid rgba(201, 169, 98, 0.2);
    border-radius: 0.75rem;
    padding: 1.25rem;
    margin-bottom: 1rem;
">
    <h3 style="
        color: #f4f4f5;
        font-family: 'Cormorant Garamond', serif;
        font-size: 1.1rem;
        margin: 0 0 0.5rem 0;
    ">Title</h3>
    <p style="
        color: #a1a1aa;
        font-family: 'Outfit', sans-serif;
        font-size: 0.9rem;
        line-height: 1.6;
        margin: 0;
    ">Description text here.</p>
</div>
```

---

## Profile Ring (Gold Border + Glow)

```css
.profile-pic {
    border-radius: 50%;
    border: 3px solid #c9a962;
    box-shadow: 0 0 20px rgba(201, 169, 98, 0.4), 0 0 40px rgba(201, 169, 98, 0.3);
}
```

---

## Usage Notes

1. **Import Fonts:**
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
   ```

2. **Apply Theme:** Copy `:root` variables to your CSS

3. **Quote Cards:** Use the Quote Card Template for consistent styling

4. **Icons:** Use stroke-based SVG icons with `stroke="#c9a962"`

---

*Generated from muralikrishnan.net — March 2026*
