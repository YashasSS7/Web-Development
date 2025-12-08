## 🧩 1️⃣ Where They Are Used

When you create a form in HTML like this:

<form action="/login" method="post">
  <input type="text" name="username">
  <input type="password" name="password">
  <input type="submit">
</form>


The `method` attribute decides **how the form data is sent** to the server.

<--------------------------------------------------------------------------------------------------------------------------------------------------------------------->

## 1- GET Method 

GET IS USED ADD FILETERS IN WEBSITES
EG:LIKE APPLYING RAM,ROM,DISPLAY SIZE OF PRODUCT

GET” means just looking — not changing anything.

| Feature                 | Description                      |
| ----------------------- | -------------------------------- |
| 🔎 **Purpose**          | To *get* data from the server    |
| 🌐 **Data location**    | Sent in the URL (visible)        |
| 💾 **Effect on server** | Doesn’t change or save anything  |
| 📚 **Use for**          | Searches, filters, viewing pages |
| ⚠️ **Not for**          | Passwords or private info        |


Syntax:
<form action="/search" method="get">


Behavior:

* The **data is appended to the URL** as query parameters.
* Example:

  /search?username=Yashas&age=20

* You can **see it in the address bar** of the browser.

### 🧠 Characteristics:

| Feature                      | Explanation                                                           |
| ---------------------------- | --------------------------------------------------------------------- |
| 🔓 **Visible data**          | Data is shown in the URL — not secure for passwords or personal info. |

| 🔁 **Bookmarkable**          | You can save or share the URL (e.g., search queries).                 |

| 🚀 **Faster**                | Because it just requests a URL (no body).                             |

| ⚙️ **Default method**        | If you don’t write `method`, it defaults to `GET`.                    |

| 📦 **Limited data size**     | Around 2048 characters max (browser-dependent).                       |

| 💾 **Used for reading data** | Should only **retrieve** data, not modify it.                         |

### ✅ Example use case:

* Search forms
* Filters (like “?category=phones&sort=price”)
* Pagination links

<--------------------------------------------------------------------------------------------------------------------------------------------------------------------->

## 🔒 3️⃣ POST Method

### 📖 Syntax:

<form action="/register" method="post">


### 🔍 Behavior:

* The **data is sent inside the request body**, **not visible in the URL**.
* The browser sends data like:

  ```
  POST /register HTTP/1.1
  Content-Type: application/x-www-form-urlencoded

  username=Yashas&password=12345
  ```

### 🧠 Characteristics:

| Feature                            | Explanation                                                                        |
| ---------------------------------- | ---------------------------------------------------------------------------------- |
| 🔒 **Hidden data**                 | Data is not visible in the URL (more secure for sensitive info).                   |

| 💾 **Not bookmarkable**            | You cannot save the form data as a link.                                           |

| 📤 **Used for writing data**       | Used for actions that **change data on the server** (login, signup, upload, etc.). |

| 📦 **No size limit (practically)** | Can send large amounts of data (e.g., file uploads).                               |

| 🧰 **Supports files**              | Required for forms with file uploads (`enctype="multipart/form-data"`).            |

### ✅ Example use case:

* Login forms
* Signup forms
* Uploading files
* Submitting feedback or orders



<!------------------------------------------------------------------------>


## ⚠️ 5️⃣ Common Mistakes to Avoid

* ❌ Using `GET` for login/password forms → exposes data in URL.
* ❌ Using `POST` when you only need to **view** something (like search).
* ✅ Always match the method to the purpose:

  * “Read” → GET
  * “Write / Change” → POST

---

### 💡 In short:

> **GET = Asking for information**
> **POST = Sending information**

---

Would you like me to show a **live example** (code) that demonstrates both methods — showing how URLs differ when you submit a form?
