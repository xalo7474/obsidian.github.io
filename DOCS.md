# 📚 Obsidian Framework Documentation

> Welcome to the **Obsidian CSS** documentation.
This guide will help you get started, explore components, and implement features with ease.

---

## 🚀 Getting Started

To set up the Obsidian CSS Framework in your project, follow these steps:

### Importing Styles

Include the CSS file in your HTML:

```html
<link rel="stylesheet" href="Obsidian.css">
```

### Font Awesome

To use icons, make sure to include Font Awesome in your project:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
```

---

## 🛠️ Components

The Obsidian Framework provides a variety of components for building your application. Here are some examples:

### Buttons

Use the `.button` class to style your buttons:

```html
<button class="button">Click Me</button>
```

### Cards

A card component can be created as follows:

```html
<div class="card">
    <h4>Card Title</h4>
    <p>This is a sample card with some text.</p>
    <a href="#" class="button">Learn More</a>
</div>
```

### Loading Spinner

To add a loading spinner, use the `.loader` class:

```html
<div class="loader"></div>
```

### Progress Bar

Implement a progress bar like this:

```html
<div class="progress-bar">
    <div class="progress" style="width: 70%;"></div>
</div>
```

---

## 🎨 Examples

Here are some example components built with the Obsidian Framework:

```html
<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 20px; margin-bottom: 20px;">
    <div class="feature" style="padding: 20px; border-radius: 10px; background-color: #1E1E1E; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);">
        <h3>Feature 1</h3>
        <p>Description of Feature 1.</p>
        <a href="#" class="button">View Example</a>
    </div>
    <div class="feature" style="padding: 20px; border-radius: 10px; background-color: #1E1E1E; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);">
        <h3>Feature 2</h3>
        <p>Description of Feature 2.</p>
        <a href="#" class="button">View Example</a>
    </div>
    <div class="feature" style="padding: 20px; border-radius: 10px; background-color: #1E1E1E; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);">
        <h3>Feature 3</h3>
        <p>Description of Feature 3.</p>
        <a href="#" class="button">View Example</a>
    </div>
</div>
```

---

## 🌟 Features

Explore some functionalities you can implement with the Obsidian Framework:

### Custom Scrollbars

> Style your scrollbars with these CSS rules:

```css
/* Custom Scrollbar */
::-webkit-scrollbar {
    width: 8px;
}
::-webkit-scrollbar-track {
    background: #1E1E1E;
}
::-webkit-scrollbar-thumb {
    background: var(--accent-color);
    border-radius: 10px;
}
::-webkit-scrollbar-thumb:hover {
    background: #61428b; /* Darken on hover */
}
```

### Neumorphism Effect

> To create a neumorphic effect, use the following CSS class:

```css
.neumorphic {
    background: #1E1E1E;
    border-radius: 20px;
    padding: 20px;
    box-shadow: 8px 8px 20px #0A0A0A, -8px -8px 20px #292929;
}
```

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for more details.

---

## 💬 Support

For any questions or issues, feel free to open an issue in the repository.

---

> **Happy Coding!** ✨
