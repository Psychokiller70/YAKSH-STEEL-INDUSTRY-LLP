
---

## 🚀 Getting Started

### For Designers
1. Review the design tokens in `design-system.yml`
2. Apply components from the component library to your designs
3. Follow the spacing and grid guidelines for layout
4. Use the typography scales for consistent visual hierarchy

### For Developers
1. Implement design tokens as CSS variables or design system packages
2. Build components following the corner radius and color specifications
3. Maintain spacing rhythm using 8px base units
4. Test responsive behavior at mobile breakpoints

---

## 🔧 Design Tokens

All design decisions are token-based for consistency across applications:

- **Colors:** Primary, secondary, tertiary, surface layers, error states
- **Typography:** Type scales with family, size, weight, and line height
- **Spacing:** 8px-based rhythm for margins, padding, and gutters
- **Shapes:** Border radius levels for component categories
- **Shadows:** Minimal, tonal-based elevation system

---

## 💡 Usage Examples

### Example: Product Card
```html
<div class="card">
  <h3 class="headline-md">Steel Grade A</h3>
  <p class="body-md">Premium quality steel for industrial applications</p>
  <button class="button-primary">Request Quote</button>
</div>
