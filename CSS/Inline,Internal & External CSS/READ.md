                                         **3 ways to add CSS to an HTML page** 



## **1) Inline CSS**

CSS is written **inside the HTML tag** using the `style` attribute.
**Use when:** You want to style *one specific element*.

```html
<p style="color: red; font-size: 20px;">Hello</p>
```

<!------------------------------------------------------------------------>

## **2) Internal CSS**

CSS is written **inside the `<style>` tag** in the `<head>` section.

```html
<head>
    <style>
        p {
            color: blue;
        }
    </style>
</head>
```

**Use when:** Styling a single HTML page.

---<!------------------------------------------------------------------------><!--------------------------------------------------------------->

## **3) External CSS**

CSS is written in a **separate .css file** and linked using `<link>`.

### HTML:

```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

### style.css:

```css
p {
    color: green;
}
```

**Use when:** Working on real projects — best practice.

<!------------------------------------------------------------------------>