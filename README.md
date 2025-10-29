# NEON-NIGHTLIFE-CSS-THEME
A vibrant, dark-mode CSS template inspired by synthwave and cyberpunk aesthetics, featuring pulsing neon glows and energetic colors. Perfect for landing pages, portfolio sections, or blog headers that need a futuristic look.
## Key Features

* **Pulsing Neon Glow:** Achieved using layered `text-shadow` properties and custom `@keyframes neonGlow`.
* **High-Contrast Colors:** Uses deep black (`#1a1a1a`) with vibrant Cyan (`#00ffff`), Magenta (`#ff00ff`), and Lime Green (`#00ff00`).
* **Interactive Elements:** Custom styles for navigation links and a dramatic `.neon-button` hover effect.

## How to use!

1.  **Clone the repository:**
    ```bash
    git clone ____
    ```
2.  **Link the CSS:** Ensure your HTML file is linked to `style.css`.
3.  **Apply Classes:** Use the provided classes like `.neon-button`, `.neon-container`, and `.center-text`.


## Code Snippets + customization

**The Pulsing H1 Glow:**
**Custumize colors to your desire as well! Experiment!
```css
h1 {
    color: #00ffff; 
    text-shadow: 0 0 5px #00ffff, 0 0 10px #00ffff, 0 0 80px #00ffff;
    animation: neonGlow 1.0s infinite alternate;
}

@keyframes neonGlow {
}

