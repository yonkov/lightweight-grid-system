## Lightweight Grid System

A Lightweight and easy-to-use grid system based on flexbox. It supports up to 12 columns and allows you to set custom gutter. No more need to use Bootstrap, Foundation or any other heavy third-party css framework.
Example usage:

### Two-column layout

```html
<div class="grid">
  <div class="grid__col-6">
	Column 1
  </div>
    <div class="grid__col-6">
    Column 2
  </div>
</div>
```

### Three-column layout

```html
<div class="grid">
  <div class="grid__col-4">
	Column 1
  </div>
    <div class="grid__col-4">
    Column 2
  </div>
  <div class="grid__col-4">
    Column 3
  </div>
</div>
```

### Four-column layout

```html
<div class="grid">
  <div class="grid__col-3">
	Column 1
  </div>
    <div class="grid__col-3">
    Column 2
  </div>
  <div class="grid__col-3">
    Column 3
  </div>
   <div class="grid__col-3">
    Column 4
  </div>
</div>
```