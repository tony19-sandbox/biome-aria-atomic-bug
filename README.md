> Demo for `biome` bug: `useValidAriaProps`: aria-atomic incorrectly flagged as invalid ARIA attribute

Run `npm run lint:biome` to reproduce.

```html
  ✖ The element contains invalid ARIA attribute(s)

    5 │     <div>
  > 7 │       <div aria-atomic="true">B</div>
      │       ^^^^^^^^^^^^^^^^^^^^^^^^
    8 │     </div>
    9 │   )

  ℹ aria-atomic is not a valid ARIA attribute.
```

### Environment

 * Biome v1.4.1
 * macOS Sonoma
 * Node v18.18.2
