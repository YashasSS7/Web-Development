### 🧱 **Block-level Elements**

**Definition:**
Block elements always start on a **new line** and take up the **full width** available (as much as possible).

**Examples:**

```html
<div>, <p>, <h1> to <h6>, <section>, <article>, <header>, <footer>, <ul>, <ol>, <li>, <form>, <table>
```

**Characteristics:**

* Starts on a **new line**.
* Takes up the **entire width** of its container.
* Can contain **inline elements** and **other block elements**.
* You can set **width**, **height**, **margin**, **padding**, etc.

**Example:**

```html
<p>This is a paragraph.</p>
<div>This is a div.</div>
```

✅ Each appears on a new line.

---

### 🧩 **Inline Elements**

**Definition:**
Inline elements **do not start on a new line** — they appear **in the same line** as surrounding text.

**Examples:**

```html
<span>, <a>, <img>, <strong>, <em>, <b>, <i>, <u>, <label>, <small>
```

**Characteristics:**

* Does **not** start on a new line.
* Takes up only as much **width as necessary**.
* Can contain **only text or other inline elements**.
* **width** and **height** properties usually **don’t apply**.

**Example:**

```html
<p>This is <strong>bold</strong> and <em>italic</em> text.</p>
```

✅ All appear in the same line.

---

| Feature                    | Block Elements              | Inline Elements          |
| -------------------------- | --------------------------- | ------------------------ |
| Starts on new line         | ✅ Yes                       | ❌ No                     |

| Takes full width           | ✅ Yes                       | ❌ Only content width     |

| Can set width/height       | ✅ Yes                       | ⚠️ Usually no            |

| Can contain block elements | ✅ Yes                       | ❌ No                     |

| Common examples            | `<div>`, `<p>`, `<section>` | `<span>`, `<a>`, `<img>` |

<!---------------------------------------------------------------------------->

### ⚙️ **Bonus: Inline-Block**

There’s also a middle ground:
`display: inline-block;` — it **behaves like inline**, but **accepts width and height**.

**Example:**

```html
<span style="display:inline-block; width:100px; height:50px; background:lightblue;">Box</span>
```

