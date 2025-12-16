<div align="center">

# ⚛️ Reactify-Comp

### Beautiful, Animated React Components at Your Fingertips

[![npm version](https://img.shields.io/npm/v/reactify-comp.svg?style=flat-square&color=cb3837)](https://www.npmjs.com/package/reactify-comp)
[![npm downloads](https://img.shields.io/npm/dm/reactify-comp.svg?style=flat-square&color=cb3837)](https://www.npmjs.com/package/reactify-comp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**A CLI tool to download stunning, production-ready React components directly into your project.**

[Live Preview](https://dyon.nu/#/components) • [NPM Package](https://www.npmjs.com/package/reactify-comp) • [Report Bug](https://github.com/Sterrenbos/Reactify/issues)

</div>

---

## ✨ Features

- 🚀 **Zero Dependencies** — Components are standalone `.jsx` files with no external packages required
- ⚡ **Instant Setup** — Just run one command, no installation needed
- 🎨 **50+ Components** — Buttons, loaders, cards, backgrounds, and much more
- 🎯 **Interactive CLI** — Easy-to-use menu to browse and select components
- 📦 **Copy & Paste Ready** — Downloaded components work out of the box
- 🔧 **Fully Customizable** — Each component is yours to modify as needed

---

## 🚀 Quick Start

No installation required! Simply run:

```bash
npx reactify-comp
```

Then use the interactive menu to browse and download components directly into your project.

<div align="center">

<!-- Add your demo GIF here -->
![Demo](https://via.placeholder.com/600x340/1a1a2e/ffffff?text=CLI+Demo+GIF)

*Interactive CLI for browsing and downloading components*

</div>

---

## 📦 How It Works

1. **Run the CLI** in your React project directory
2. **Browse** through categories using the interactive menu
3. **Select** the component you want
4. **Done!** The `.jsx` file is saved to your project, ready to import

```jsx
// After downloading, simply import and use:
import GlowButton from './components/GlowButton';

function App() {
  return <GlowButton>Click Me</GlowButton>;
}
```

---

## 🎨 Component Library

### 🔘 Buttons
| Component | Description |
|-----------|-------------|
| Glow Button | Button with animated glow effect |
| Ripple Button | Material-style ripple on click |
| Particle Button | Explosive particle effects |
| Download Button | Animated download progress |
| Toggle Switch | Smooth animated toggle |

### ⏳ Loaders
| Component | Description |
|-----------|-------------|
| Wave Loader | Animated wave pattern |
| Pulse Loader | Pulsing animation |
| Bounce Loader | Bouncing dots |
| Circular Progress | Circular progress indicator |
| Skeleton Loader | Content placeholder skeleton |
| Death Star Loader | Star Wars themed loader |

### 📑 Sidebars
| Component | Description |
|-----------|-------------|
| Glass Sidebar | Glassmorphism style |
| Neon Sidebar | Neon glow effects |
| Minimal Sidebar | Clean, minimal design |
| Dock Sidebar | macOS dock style |

### 🧭 Navigation
| Component | Description |
|-----------|-------------|
| Floating Nav | Floating navigation bar |
| Animated Tabs | Smooth tab transitions |

### 🃏 Cards
| Component | Description |
|-----------|-------------|
| Animated Card | Interactive hover animations |
| Gradient Card | Dynamic gradient backgrounds |
| Spotlight Card | Mouse-follow spotlight effect |

### 🌌 Backgrounds
| Component | Description |
|-----------|-------------|
| Aurora Waves | Northern lights effect |
| Starfield | Animated star background |
| Particle Vortex | Swirling particle system |
| Hyperspace | Star Wars hyperspace jump |
| Morphing Blob | Organic blob animations |
| Serenity Flow | Calm, flowing gradients |
| Floating Orbs | Ambient floating spheres |

### ✍️ Text Effects
| Component | Description |
|-----------|-------------|
| Gradient Text | Animated gradient colors |
| Glitch Text | Cyberpunk glitch effect |
| Typewriter | Classic typewriter animation |
| Wave Text | Wavy text animation |
| Hologram Text | Futuristic hologram style |
| Crawl Text | Star Wars opening crawl |

### 📝 Inputs
| Component | Description |
|-----------|-------------|
| Glow Searchbar | Searchbar with glow effect |
| Minimal Searchbar | Clean, simple search |
| Expanding Searchbar | Expands on focus |
| Range Slider | Custom styled slider |
| Star Rating | Interactive star rating |

### 💬 Modals
| Component | Description |
|-----------|-------------|
| Glass Modal | Glassmorphism modal |
| Slide Panel | Sliding side panel |

### 🧩 UI Elements
| Component | Description |
|-----------|-------------|
| Tooltip | Animated tooltips |
| Accordion | Expandable sections |
| Animated Counter | Number counting animation |
| Notification Toast | Toast notifications |
| Status Avatar | Avatar with status indicator |
| Avatar Group | Stacked avatar group |
| Glow Badge | Badge with glow effect |
| Gradient Divider | Stylish section divider |
| Lightsaber | Star Wars lightsaber |

---

## 💻 Example Component

Here's what a downloaded component looks like:

```jsx
// GlowButton.jsx
import React from 'react';

const GlowButton = ({ children, onClick, color = '#00d4ff' }) => {
  const styles = {
    button: {
      padding: '12px 32px',
      fontSize: '16px',
      fontWeight: '600',
      color: '#fff',
      background: `linear-gradient(135deg, ${color}, ${color}dd)`,
      border: 'none',
      borderRadius: '8px',
      cursor: 'pointer',
      position: 'relative',
      overflow: 'hidden',
      transition: 'all 0.3s ease',
      boxShadow: `0 0 20px ${color}66, 0 0 40px ${color}33`,
    },
  };

  return (
    <button style={styles.button} onClick={onClick}>
      {children}
    </button>
  );
};

export default GlowButton;
```

*All components include inline styles — no CSS files needed!*

---

## 🌐 Live Preview

Want to see the components in action before downloading?

**👉 [View All Components](https://dyon.nu/#/components)**

Browse the full library with interactive previews and find the perfect components for your project.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add a new component or improve existing ones:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingComponent`)
3. Commit your changes (`git commit -m 'Add AmazingComponent'`)
4. Push to the branch (`git push origin feature/AmazingComponent`)
5. Open a Pull Request

### 💡 Component Guidelines

- Components should be standalone `.jsx` files
- Use inline styles (no external CSS dependencies)
- Include sensible default props
- Keep the code clean and well-commented
- Test across different React versions

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ by [Dyon](https://dyon.nu)**

If you find this helpful, please consider giving it a ⭐

[⬆ Back to Top](#-reactify-comp)

</div>
