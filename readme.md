# Center a Div

This project demonstrates different methods to center a `<div>` both **horizontally**, **vertically**, and **both** using HTML and CSS.

## 💡 Methods Covered

1. **Using Flexbox**
2. **Using Grid**
3. **Using Position + Transform**
4. **Using Margin Auto**

---

## 📁 Files

* `index.html` – HTML structure
* `style.css` – CSS styling to center the div

---

## 📌 Examples

### 1. Flexbox

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

---

### 2. CSS Grid

```css
.container {
  display: grid;
  place-items: center;
  height: 100vh;
}
```

---

### 3. Position + Transform

```css
.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

---

### 4. Margin Auto (Horizontal only)

```css
.centered {
  width: 200px;
  margin: 0 auto;
}
```

---

## ✅ How to Use

1. Clone or download this repo
2. Open `index.html` in your browser
3. Check `style.css` for centering techniques

---

## 🧠 Notes

* `flex` and `grid` are the most modern and reliable ways.
* Use `transform` for absolute/fixed centering.
* `margin: auto` works best for horizontal centering when width is known.

