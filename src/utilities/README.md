# Utilities

## Usage

### Margin utilities

```html
<div class="tbds-margin-top-2">
  Some content
</div>
```

#### Breakpoint variants

Margin utilities can also be used to set `margin` at specific breakpoints.
Each variant's styles are applied at the breakpoint and up (using a
`min-width` media query).

```html
<div class="tbds-margin-right-4@medium">
  Some content
</div>
```

### Padding utilities

```html
<div class="tbds-padding-bottom-1">
  Some content
</div>
```

#### Breakpoint variants

Padding utilities can also be used to set `padding` at specific breakpoints.
Each variant's styles are applied at the breakpoint and up (using a
`min-width` media query).

```html
<div class="tbds-padding-bottom-1@small">
  Some content
</div>
```

### Typography utilities

```html
<p class="tbds-font-weight-normal">
  Set text in normal weight
</p>
```

```html
<p class="tbds-font-weight-bold">
  Set text in bold weight
</p>
```

```html
<p class="tbds-font-style-normal">
  Style text normal
</p>
```

```html
<p class="tbds-font-style-italic">
  Style text italicized
</p>
```

```html
<p class="tbds-text-align-right">
  Right-align text
</p>
```

```html
<p class="tbds-text-align-left">
  Left-align text
</p>
```

```html
<p class="tbds-text-align-center">
  Center-align text
</p>
```

#### Breakpoint variants

Typography utilities can also be used to set styles at specific breakpoints.
Each variant's styles are applied at the breakpoint and up (using a
`min-width` media query).

```html
<div class="tbds-text-align-right@large">
  Some content
</div>
```

### Line height utilities

Set `line-height` to `0` to remove extra space from elements that inherit
`line-height` but don't contain any text.

```html
<div class="tbds-line-height-0">
  <svg>…</svg>
</div>
```
