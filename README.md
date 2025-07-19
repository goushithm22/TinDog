# TinDog 🐾

A sleek, responsive startup-style landing page for a fictional dog-dating app, built using HTML5, CSS3, and **Bootstrap**.

---

## 📌 Live Demo  
*Put your live demo link here*  
e.g. `https://your-username.github.io/TinDog/`

---

## ✨ Features & Highlights

- **Responsive Grid Layout** – Utilizes Bootstrap’s 12-column grid to seamlessly adapt across mobile, tablet, and desktop screens.  
- **Fixed Navbar** – A clean top nav built with Bootstrap’s navbar component that sticks at the top on scroll.  
- **Hero Section** – Eye-catching full-width section with call-to-action button, styled using Bootstrap utilities.  
- **Feature Cards** – Uses Bootstrap's card components to showcase app features (e.g., “Swipe left, Swipe right”, compatibility).  
- **Testimonial Carousel** – Client feedback presented via Bootstrap’s carousel for smooth sliding transitions.  
- **Download Buttons** – Styled Bootstrap buttons with Font‑Awesome icons for Play Store and App Store links.  
- **Footer** – A responsive footer with social media links and quick access navigation.

---

## 🛠️ Technologies Used

- **Bootstrap** – Core framework powering the layout, components, and responsive utilities.  
- **HTML5** – Semantic markup with Bootstrap class integration.  
- **CSS3** – Custom styling to complement Bootstrap defaults.  
- **Font Awesome** – Icons for social links and download buttons.  
- **Google Fonts** – Typographic enhancements for headings and body text.

---

## 🔍 Bootstrap Implementation

### 1. Grid Layout & Responsiveness  
- Containers (`.container`, `.container-fluid`) wrap content and apply appropriate padding.  
- Row/column system used (`.row`, `.col-md-6`, `.col-lg-4`) to position features and testimonials responsively.

### 2. Navigation Bar  
```html
<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <!-- Brand & toggler -->
</nav>
```
- Collapsible menu for mobile, using Bootstrap’s `.navbar-toggler`.

### 3. Hero Section  
```html
<section class="jumbotron text-center">
  <h1 class="display-4">Find love fur-ever!</h1>
  <a class="btn btn-primary btn-lg" href="#download" role="button">Download Now</a>
</section>
```
- Centered, inviting, and fully responsive.

### 4. Cards & Carousel  
- Cards styled via `.card`, `.card-body`, `.card-title`, `.card-text`.  
- Carousel implemented using `.carousel`, `.carousel-inner`, and controls for sliding quotes. Perfect for testimonials.

### 5. Utility Classes  
Bootstrap utilities like `.text-center`, `.mt-5`, `.py-5`, `.d-flex`, `.justify-content-center`, and `.shadow` were applied to adjust spacing, alignment, and aesthetics—reducing the need for custom CSS.

---

## 🧭 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/goushithm22/TinDog.git
   cd TinDog
   ```
2. **Open in browser**  
   - Double-click `index.html`, or launch with Live Server if using an editor.  
3. **View & Inspect**  
   - Update content, tweak Bootstrap classes, or style via `css/` folder.

---

## 🎓 What I Learned

1. A practical deep dive into Bootstrap—grids, navigation, utilities, components like cards and carousels.  
2. How to build a **fully responsive** landing page with minimal custom CSS.  
3. Best practices for **semantic HTML** when paired with Bootstrap.

---

## 🧩 Inspired By

- The original TinDog Bootstrap lesson in [The App Brewery course](https://appbrewery.com) — demonstrates practical Bootstrap implementation  
- Other open-source takes like m10hit’s version, which also uses Bootstrap-driven components (Carousel, Cards, Navbar)

---

## 💬 Feedback & Contributions

Love to hear your thoughts ✨  
Feel free to submit issues, suggestions, or pull requests!

---

## 📄 License

This project is open source and available under the **MIT License**.
