
# **Obsolete HTML Tags**

HTML has undergone major evolution over the years. As a result, several old tags have been deprecated or marked obsolete. While many still work in modern browsers, using them is strongly discouraged because they lack semantic value and often break modern standards. This section highlights common obsolete tags and their recommended replacements.

---

## **What Are Obsolete Tags?**

Obsolete (or deprecated) HTML tags are elements that:

* Are no longer part of the modern HTML specification
* May not work consistently across browsers
* Should be avoided in favor of CSS or semantic HTML5 elements

These tags were often used for styling, something that modern CSS handles much more effectively.

---

## **Why Avoid Obsolete Tags?**

Using obsolete tags creates problems:

* **Compatibility Issues** — Not supported reliably in all modern browsers
* **Accessibility Problems** — They don’t follow current web standards and may confuse assistive technologies
* **Poor Maintainability** — Mixing styling with structure makes future updates harder

In short: **they make your code outdated and harder to work with**.

---

## **Examples of Obsolete HTML Tags**

### **1. `<font>` Tag**

Used to define text color, size, and font.

```html
<font color="red" size="3" face="verdana">This is some text</font>
```

### **2. `<center>` Tag**

Used to center-align elements.

```html
<center>This text will be centered</center>
```

### **3. `<u>` Tag**

Used to underline text.

```html
<u>This text will be underlined</u>
```

---

## **Modern Alternatives**

Use **CSS** for styling and layout — it separates content from presentation and follows modern standards.

### **Replacing `<font>`**

```html
<span style="color:red; font-size:16px; font-family:verdana;">
  This is some text
</span>
```

### **Replacing `<center>`**

```html
<div style="text-align:center;">This text will be centered</div>
```

### **Replacing `<u>`**

```html
<span style="text-decoration:underline;">This text will be underlined</span>
```

---

## **Conclusion**

Understanding obsolete HTML tags is more than a look back at early web design — it's a reminder of why web standards evolve. Avoid deprecated tags and use modern, semantic HTML with CSS for styling. This ensures cleaner markup, better accessibility, easier maintenance, and future-proof web development.

