

## 📌 CSS Overflow – Quick Cheat Sheet

### 1️⃣ `overflow` (shorthand)

Controls overflow on **both axes**.

```css
overflow: visible; /* default */
overflow: hidden;  /* clips content */
overflow: scroll;  /* always shows scrollbars */
overflow: auto;    /* scrollbars only if needed */
```

Shorthand format:

```css
overflow: <x> <y>;
```

Example:

```css
overflow: scroll hidden; /* x = scroll, y = hidden */
```

---

### 2️⃣ `overflow-x` & `overflow-y`

Control overflow **independently**.

```css
overflow-x: hidden;
overflow-y: auto;
```

| Property     | Axis         |
| ------------ | ------------ |
| `overflow-x` | Left ↔ Right |
| `overflow-y` | Top ↕ Bottom |

⚠️ Needs **width** (for x) or **height** (for y) to work.




---

### 3️⃣ `white-space`

Controls **line wrapping**.

```css
white-space: normal;  /* default */
white-space: nowrap;  /* single line only */
```

`nowrap` effects:

* No line breaks
* Text stays in one line
* Overflow happens horizontally

---

### 4️⃣ `text-overflow`

Shows how **hidden text is displayed**.

```css
text-overflow: ellipsis;
```

❗ Works ONLY if **all three** are present:

```css
white-space: nowrap;
overflow: hidden;
text-overflow: ellipsis;
```

Result → `This is very lo...`

---



## 🔥 Common Practical Patterns

### ✔️ Single-line ellipsis (MOST IMPORTANT)

```css
.title {
  width: 200px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
```

---

### ✔️ Vertical scrolling box

```css
.box {
  height: 200px;
  overflow-y: auto;
  overflow-x: hidden;
}
```

---

### ✔️ Horizontal scroll (tables)

```css
.table-wrapper {
  overflow-x: auto;
  overflow-y: hidden;
}
```

---


