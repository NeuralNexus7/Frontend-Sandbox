# 🎴 3D Flip Card Carousel

A modern and interactive 3D card carousel built using pure HTML and CSS. Each card features a smooth flip animation and unique styling, making it suitable for portfolios, team showcases, product displays, and creative web projects.

![3D Card Flip Demo](card-flip.gif)

## ✨ Features

* 3D Flip Animation
* Carousel Card Layout
* Smooth Hover Effects
* Responsive Design
* Unique Gradient Themes
* Pure HTML & CSS
* Easy to Customize
* No JavaScript Required

## 📂 Project Structure

```text
.
├── card.html
├── card.css
└── README.md
```

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `card.html` in your browser.
3. Customize the card content, colors, and images.

## 🛠️ Customization

### Change Card Titles

Edit the heading inside each card:

```html
<h2 class="heading">Card 1</h2>
```

### Change Card Colors

Modify the gradient backgrounds in `card.css`:

```css
.card1 .card-front {
    background: linear-gradient(...);
}
```

### Add Content to Card Back

Insert your own content inside:

```html
<div class="card-back">
    Your Content Here
</div>
```

## ⭐ Optional Features

### Circular Profile Image

Add inside `.card-back`:

```html
<div class="logo-container">
    <img src="your-image.jpg" class="logo" alt="Profile Image">
</div>
```

Add:

```css
.card-front img,
.card-back img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 16px;
}

.logo-container {
    width: 120px;
    height: 120px;
    border: 3px solid #55e439;
    border-radius: 50%;
    overflow: hidden;
}
```

### Front Card Background Image

Add inside `.card-front`:

```html
<img src="your-image.jpg" class="card-bg-image" alt="Card Background">
```

Add:

```css
.card-bg-image {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
    border: 1px solid;
}
```

## 📸 Preview

A stylish 3D carousel featuring four interactive flip cards with customizable content, images, and color themes.

## 👨‍💻 Author

**Rudra Sharma**