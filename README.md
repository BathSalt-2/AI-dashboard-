# C2 AI Dashboard

A modern, interactive 3D dashboard for AI model development and monitoring. Built with React, Three.js, and TypeScript.

![C2 Dashboard Preview](preview.png)

## Features

- 🤖 **AI Model Management**
  - Real-time model training monitoring
  - Performance metrics visualization
  - Architecture configuration interface

- 🎨 **Modern UI/UX**
  - Interactive 3D environment
  - Dynamic particle effects
  - Glass-morphism design
  - Responsive layout

- 🛠 **Technical Stack**
  - React + TypeScript
  - Three.js with React Three Fiber
  - TailwindCSS for styling
  - Real-time 3D rendering

## Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/c2-ai-dashboard.git

# Install dependencies
npm install

# Start development server
npm run dev
```

## Project Structure

```
src/
├── components/
│   ├── logo/           # C2 logo components
│   ├── scene/          # 3D scene components
│   └── ui/             # Reusable UI components
├── constants/          # Global constants and configs
└── types/             # TypeScript type definitions
```

## Key Components

### Scene3D
The main 3D environment that renders the interactive background and logo.

### Dashboard
Displays AI model metrics and controls in a glass-morphism UI.

### ParticleField
Creates an animated particle effect background.

## Configuration

### Colors
Edit `src/constants/colors.ts` to modify the theme:

```typescript
export const colors = {
  primary: '#00a2ff',    // Neon blue
  secondary: '#ff6b4a',  // Neon orange
  dark: '#0a0a0f',      // Dark background
  // ...
}
```

## Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT License - see LICENSE.md

## Acknowledgments

- Three.js for 3D rendering
- React Three Fiber for React integration
- TailwindCSS for styling