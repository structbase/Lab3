## Projects

### 1. Blog Preview Card

**Description:**
A card layout showing a blog post preview with:

* Image
* Category label
* Published date
* Title and description
* Author info

**Folder structure:**

```
blog-preview-card/
├── index.html
├── style.css
├── assets/
│   ├── fonts/
│   └── images/
└── design/
```

**Picture**
![alt text](./blog-preview-card/preview.jpg)

---

**How to run:**

1. Open `index.html` in a browser.
2. All styling is included in `style.css`.

---

### 2. QR Code Component

**Description:**
A simple card displaying a QR code with:

* QR image
* Heading
* Description

**Folder structure:**

```
qr-component/
├── index.html
├── style.css
├── images/
└── design/
```

**Picture**
![alt text](./qr-component/preview.jpg)

---

**How to run:**

1. Open `index.html` in a browser.
2. All styling is included in `style.css`.

---

Here’s a clean, concise way to include the required reflection in your **README** for Canvas submission:

---

# Frontend Refactoring Lab – Bootstrap

## Projects

* **QR Code Component** – refactored to use Bootstrap card, text utilities, spacing, and responsive layout.
* **Blog Preview Card** – refactored to use Bootstrap card, badge, typography, spacing, flex utilities, and responsive grid.

## Reflection

**1. Challenges faced when refactoring:**

* Some challenges with this project included handling fixed widths and making elements responsive with Bootstrap, as well as adjusting the shadow radius in the Blog Preview Card.

**2. How Bootstrap simplified styling:**

* Bootstrap simplified styling through utility classes like `text-center`, `fw-bold`, `text-muted`, `img-fluid`, `d-flex`, and components like `card`. Applying these classes directly to elements made them more flexible and responsive without writing custom CSS for every style.

**3. When custom CSS might be preferred:**

* CSS is still very useful. Although Bootstrap provides pre-made styling and sizing for elements, CSS allows fine-grained control. For example, when controlling font size, `fs-4` was too large and `fs-5` too small, so I created a custom style in CSS with the exact size I wanted (converted to `rem`) and applied it alongside Bootstrap classes. Additional CSS is also important for maintaining separation of concerns and customizing beyond what Bootstrap provides.