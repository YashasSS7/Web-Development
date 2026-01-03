topics discussed : box models - Margin,Padding & Borders
                   box sizing comaprison (content box vs Border Box )
                   Calculation of width (content box vs Border Box )
                   Margin collapse                                             
                                               
                                               
                                                what `box-sizing: border-box` does.

# 🔥 Imagine a 200px Box

```css
width: 200px;
padding: 20px;
border: 10px solid black; 
```

Now the question:

👉 Will the box actually be **200px wide**? 

<!------------------------------------------------------------------------>

# ❌ Without border-box (default)

The box becomes **BIGGER** than 200px.

Why?

* Padding adds extra space
* Border adds extra space

So the 200px becomes:

```
200px + 20px + 20px + 10px + 10px = 260px
```

So your box becomes **260px** wide.

This is why layouts break.

<!------------------------------------------------------------------------>
# ✅ With border-box

Same code:

```css
width: 200px;
padding: 20px;
border: 10px solid black;
box-sizing: border-box;
```

Now the box stays **EXACT 200px**.

Padding and border will fit **inside** the box.
It will NEVER grow bigger.

---

# 🧠 One-Line Meaning

👉 **`border-box` = whatever width you write, that’s the final size.**



# ⚡ Final summary (most important)

| Property                | Final Size                  | Why                              |
| ----------------------- | --------------------------- | -------------------------------- |
| `content-box` (default) | Gets bigger than you expect | adds padding + border            |
| `border-box`            | Stays exact size you wrote  | padding + border included inside |

