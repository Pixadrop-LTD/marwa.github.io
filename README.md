# Marwa Safaris Website

A modern, responsive website for Marwa Safaris, built with Tailwind CSS, Alpine.js, and Vite.

## Features

- 🎨 Custom design system based on brand guidelines
- 🚀 Optimized for performance and accessibility
- 📱 Fully responsive layout
- 🎭 Smooth animations and transitions
- 🛠️ Developer-friendly setup

## Prerequisites

- Node.js (v16 or later)
- npm (v7 or later) or yarn

## Getting Started

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd marwa-safaris
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open in browser**
   The development server will start at `http://localhost:3000`

## Building for Production

```bash
# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
.
├── public/              # Static files
├── src/
│   └── styles.css      # Main CSS file with Tailwind imports
├── index.html           # Main HTML entry point
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── vite.config.js       # Vite configuration
└── package.json         # Project dependencies and scripts
```

## Design System

### Colors

| Name | Value |
|------|-------|
| Primary | `#000080` (Deep Navy Blue) |
| Secondary | `#483C32` (Warm Taupe) |
| Accent | `#8B0000` (Rich Crimson Red) |
| Plum | `#8E4585` (Deep Plum) |

### Typography

- **Headings**: Montserrat (sans-serif)
- **Body Text**: Source Serif Pro (serif)
- **Accent Text**: Poppins (sans-serif)

### Breakpoints

- `sm`: 640px
- `md`: 768px
- `lg`: 1024px
- `xl`: 1280px
- `2xl`: 1536px

## Development Guidelines

1. **Styling**
   - Use Tailwind's utility classes for styling
   - Create custom components in `src/styles.css` using `@layer components`
   - Follow the design system for colors, typography, and spacing

2. **JavaScript**
   - Use Alpine.js for interactivity
   - Keep JavaScript minimal and focused on UI interactions

3. **Accessibility**
   - Use semantic HTML elements
   - Ensure proper color contrast
   - Add ARIA attributes where necessary
   - Test with keyboard navigation

## License

MIT#   m a r w a . g i t h u b . i o  
 