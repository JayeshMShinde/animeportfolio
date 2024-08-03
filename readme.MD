# Anime Coder Portfolio

Welcome to the Anime Coder Portfolio project! This is a unique, interactive portfolio website designed for developers who love anime aesthetics and want to showcase their projects in a cyberpunk-inspired digital environment.

## 🌟 Features

- **Responsive Design**: Looks great on both desktop and mobile devices
- **Anime-Inspired Visuals**: Cyberpunk aesthetics with glowing elements and dynamic animations
- **Interactive Background**: Parallax scrolling effect for an immersive experience
- **Floating Anime Character**: An animated character that follows cursor movement
- **Project Showcase**: Glowing project cards with hover effects
- **Animated Coding Effect**: A matrix-like overlay that adds to the tech atmosphere
- **Easy to Customize**: Well-structured HTML and CSS for easy personalization

## 🚀 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/anime-coder-portfolio.git
   ```

2. Open `index.html` in your preferred web browser.

3. Customize the content in `index.html` to reflect your personal information and projects.

4. Modify the styles in the `<style>` section or create a separate CSS file to adjust the look and feel.

## 🛠️ Customization

### Changing Colors

The color scheme is defined using CSS variables at the top of the `<style>` section:

```css
:root {
    --primary-color: #00FFFF;
    --secondary-color: #FF00FF;
    --accent-color: #FFD700;
    --background-color: #1A1A2E;
    --text-color: #FFFFFF;
}
```

Modify these values to change the overall color scheme of the portfolio.

### Adding Projects

To add a new project, copy the following HTML structure and paste it within the `<div class="projects">` section:

```html
<div class="project">
    <h3>Your Project Name</h3>
    <p>Brief description of your project.</p>
</div>
```

### Changing the Anime Character

Replace the `images/itachi.png` file with your preferred character image. Make sure to keep the same file name or update it in the CSS:

```css
#anime-coder {
    background-image: url('images/itachi.png');
}
```

## 📦 Dependencies

This project is built with vanilla HTML, CSS, and JavaScript. No external libraries or frameworks are required.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/yourusername/anime-coder-portfolio/issues).

## 📄 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

## 🙏 Acknowledgements

- Background image: [Source Name](https://link-to-source.com)
- Anime character image: [Source Name](https://link-to-source.com)

---

Made with ❤️ by Jayesh Shinde