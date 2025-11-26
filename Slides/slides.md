---
theme: default
title: Slidev with Shiki Magic Move
info: |
  ## Essential Slidev Template
  Featuring Shiki Magic Move and core awesome features
author: Your Name
presenter: true
export:
  format: pdf
  withClicks: false
---

# Slidev Essentials

### Featuring Shiki Magic Move

---
layout: center
---

## What You Get

- 🎬 **Shiki Magic Move** - Smooth code animations
- 🎨 **Multiple Layouts** - Flexible designs
- 📝 **Monaco Integration** - Live code editing
- 🎭 **Click Animations** - Interactive reveals

---

# Shiki Magic Move Demo

Watch code transform smoothly between steps

````md magic-move
```js
// Step 1: Simple
function add(a, b) {
  return a + b
}
```

```js
// Step 2: Type safety
function add(a: number, b: number): number {
  return a + b
}
```

```js
// Step 3: Validation
function add(a: number, b: number): number {
  if (typeof a !== 'number' || typeof b !== 'number') {
    throw new Error('Arguments must be numbers')
  }
  return a + b
}
```
````

---
layout: two-cols
---

# Side-by-Side Comparison

::left::

## Before

```js
const data = [1, 2, 3]
for (let i = 0; i < data.length; i++) {
  console.log(data[i])
}
```

::right::

## After

```js
const data = [1, 2, 3]
data.forEach(item => {
  console.log(item)
})
```

---

# Interactive Elements

<v-clicks>

- Click to reveal first point
- Then the second appears
- And finally the third
- Combined with code blocks for maximum impact!

</v-clicks>

---

# Key Features

| Feature | Benefit |
|---------|---------|
| Magic Move | Animated transitions |
| Layouts | Design flexibility |
| Shiki | Code highlighting |
| Vue Components | Interactive slides |

---
layout: end
---

# Thank You!

**Learn more:** sli.dev
