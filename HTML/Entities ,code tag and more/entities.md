# ✅ **What Are HTML Entities?**

HTML **entities** are special codes used to display **reserved characters**, **symbols**, or **characters that cannot be typed directly** in HTML.

They **start with `&` and end with `;`**.

---

# ✅ **Why Do We Use HTML Entities?**

We use entities when:

### **1. Character has special meaning in HTML**

Example:
`<` and `>` are used for tags, so to display them you must use:

* `&lt;` → `<`
* `&gt;` → `>`


### **2. Keyboard cannot type the symbol**

Example:
`©` (copyright), `₹` (Indian Rupee), `€` (Euro)


### **3. To avoid browser confusion / errors**

---

# ✅ **Most Common HTML Entities (Easy Table)**

| Entity Code | Symbol  | Meaning            |
| ----------- | ------- | ------------------ |
| `&lt;`      | <       | less than          |
| `&gt;`      | >       | greater than       |
| `&amp;`     | &       | ampersand          |
| `&quot;`    | "       | double quote       |
| `&apos;`    | '       | single quote       |
| `&copy;`    | ©       | copyright          |
| `&reg;`     | ®       | registered         |
| `&trade;`   | ™       | trademark          |
| `&nbsp;`    | (space) | non-breaking space |
| `&cent;`    | ¢       | cent               |
| `&pound;`   | £       | pound              |
| `&yen;`     | ¥       | yen                |
| `&euro;`    | €       | euro               |
| `&#8377;`   | ₹       | Indian Rupee       |

---

# ✅ **HTML Example**

```html
<p>2 &lt; 5 and 5 &gt; 2</p>
<p>&copy; 2025 My Website</p>
<p>Price: &#8377; 499</p>
```

---

# ✅ **Shortcut Explanation**

**HTML Entities = Special codes to show special characters.
They prevent HTML from breaking.**


