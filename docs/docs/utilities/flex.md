# Flex
Introduces a few shorthand utility classes for `flex`.

```css
  .flex-col {
    display: flex;
  }

  .flex-between {
    display: flex;
    justify-content: space-between;
    gap: var(--spacing-sm);
  }

  .flex-center {
    display: flex;
    align-items: center;
    gap: var(--spacing-sm);
  }
```

## Examples
Without shorthand classes
```html
<div class="flex flex-col"></div>
<div class="flex justify-between gap-sm"></div>
<div class="flex items-center gap-sm"></div>
```

With shorthand classes
```html
<div class="flex-col"></div>
<div class="flex-between"></div>
<div class="flex-center"></div>
```