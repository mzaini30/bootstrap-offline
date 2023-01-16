# CSS Grid

## Three columns

```html
<div class="grid text-center">
  <div class="g-col-4">.g-col-4</div>
  <div class="g-col-4">.g-col-4</div>
  <div class="g-col-4">.g-col-4</div>
</div>
```

## Responsive

```html
<div class="grid text-center">
  <div class="g-col-6 g-col-md-4">.g-col-6 .g-col-md-4</div>
  <div class="g-col-6 g-col-md-4">.g-col-6 .g-col-md-4</div>
  <div class="g-col-6 g-col-md-4">.g-col-6 .g-col-md-4</div>
</div>
```

```html
<div class="grid text-center">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>
</div>
```

## Wrapping

```html
<div class="grid text-center">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>

  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>
</div>
```

## Starts

```html
<div class="grid text-center">
  <div class="g-col-3 g-start-2">.g-col-3 .g-start-2</div>
  <div class="g-col-4 g-start-6">.g-col-4 .g-start-6</div>
</div>
```

## Auto columns

```html
<div class="grid text-center">
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
</div>
```

```html
<div class="grid text-center">
  <div class="g-col-6">.g-col-6</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
</div>
```

## Nesting

```html
<div class="grid text-center" style="--bs-columns: 3;">
  <div>
    First auto-column
    <div class="grid">
      <div>Auto-column</div>
      <div>Auto-column</div>
    </div>
  </div>
  <div>
    Second auto-column
    <div class="grid" style="--bs-columns: 12;">
      <div class="g-col-6">6 of 12</div>
      <div class="g-col-4">4 of 12</div>
      <div class="g-col-2">2 of 12</div>
    </div>
  </div>
  <div>Third auto-column</div>
</div>
```

## No grid classes

```html
<div class="grid text-center" style="--bs-columns: 3;">
  <div>Auto-column</div>
  <div>Auto-column</div>
  <div>Auto-column</div>
</div>
```

## Columns and gaps

```html
<div class="grid text-center" style="--bs-columns: 4; --bs-gap: 5rem;">
  <div class="g-col-2">.g-col-2</div>
  <div class="g-col-2">.g-col-2</div>
</div>
```

```html
<div class="grid text-center" style="--bs-columns: 10; --bs-gap: 1rem;">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-4">.g-col-4</div>
</div>
```

## Adding rows

```html
<div class="grid text-center" style="--bs-rows: 3; --bs-columns: 3;">
  <div>Auto-column</div>
  <div class="g-start-2" style="grid-row: 2">Auto-column</div>
  <div class="g-start-3" style="grid-row: 3">Auto-column</div>
</div>
```

## Gaps

```html
<div class="grid text-center" style="row-gap: 0;">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>

  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>
</div>
```

```html
<div class="grid text-center" style="--bs-gap: .25rem 1rem;">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>

  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>
</div>
```
