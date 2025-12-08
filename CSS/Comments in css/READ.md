# **CSS Comments**

Comments in CSS are used to explain code, add notes, and improve readability. They **do not affect** how the browser renders the page — the browser simply ignores them.

CSS comments are always written between:

```
/* comment here */
```

There are **two types of comments** in CSS:

1. **Single-line comments**
2. **Multi-line comments**

<!------------------------------------------------------------------------>

## **1. Single-line Comment**

Used for short notes or explanations.

### **Syntax**

```css
selector {
    /* property: value */
}
```

### **Example**

```css
/* This is a single-line comment */

p {
    /* color: red */
}
```

<!------------------------------------------------------------------------>

## **2. Multi-line Comment**

Used when you need to write long descriptions, notes, or disable multiple lines of code.

### **Syntax**

```css
selector {
    /* property1: value1
       property2: value2
       property3: value3 */
}
```

### **Example**

```css
/* This is a
multi-line
comment */

p {
    /* color: red;
       background-color: purple; */
    color: purple;
    background-color: red;
}
```

---

## **Tip**

In **VS Code**, you can toggle comments quickly using:

**Ctrl + /**


