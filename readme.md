# Three.js Scroll-Based Animation

A modern web application showcasing smooth scroll-based animations using Three.js. This project demonstrates how to create engaging 3D experiences that respond to user scrolling.

## 🚀 Features

- Smooth scroll-based animations
- 3D scene rendering with Three.js
- Responsive design
- Modern web development practices

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/en/download/) (LTS version recommended)
- npm (comes with Node.js)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd [project-directory]
```

2. Install dependencies:
```bash
npm install
```

## 🚀 Running the Project

### Development
To start the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:8080`

### Production Build
To create a production build:
```bash
npm run build
```
The built files will be available in the `dist/` directory.

## 📁 Project Structure

```
project/
├── src/              # Source files
├── public/           # Static assets
├── dist/            # Production build
└── package.json     # Project configuration
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Bruno Simon
- Three.js for the amazing 3D library
- All contributors and maintainers

## 🔧 Technical Implementation

### 3D Objects and Animations
- Three unique 3D objects (Torus, Cone, and TorusKnot) with custom materials and gradient textures
- Toon material implementation with custom color control
- Smooth rotation and scaling animations for each object
- Dynamic FOV (Field of View) animations for enhanced depth perception

### Interactive Features
- **Scroll-Based Navigation**: 
  - Smooth camera movement synchronized with page scrolling
  - Section-based object animations triggered by scroll position
  - Objects placed at calculated distances for optimal viewing
  
- **Cursor Interaction**:
  - Parallax effect responding to mouse movement
  - Smooth camera group transitions for immersive experience

### Particle System
- Custom particle system with 300 randomly distributed points
- Dynamic particle size animation
- Particles colored to match the main objects
- Creates depth and atmosphere in the scene

### Performance Optimizations
- Efficient renderer setup with pixel ratio limiting
- Responsive design handling through event listeners
- Optimized texture loading with nearest-neighbor filtering
- Smart animation timing using requestAnimationFrame

### Debug Features
- Integration with `lil-gui` for real-time color adjustments
- Live material updates
- Easy-to-use debug interface for development

### Styling and Layout
- Clean, modern aesthetic with dark theme
- Full-viewport sections with centered content
- Responsive typography using viewport units
- Fixed canvas positioning for smooth overlay effects

## 🎨 Customization

You can customize various aspects of the animation:
- Change object colors through the debug UI
- Modify object distances and sizes in the configuration
- Adjust animation speeds and easing functions
- Customize section content and styling

## 🔍 Key Files
- `script.js`: Main Three.js setup and animation logic
- `style.css`: Layout and typography styling
- `index.html`: Page structure and section content

