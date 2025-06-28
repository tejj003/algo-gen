# Algorithmic Art Generator

An interactive web application that transforms your drawings into stunning algorithmic art patterns. Draw freely on the canvas and watch as mathematical algorithms create beautiful, symmetrical artwork from your sketches.

## 🎨 Features

### Drawing Canvas
- **Freehand Drawing**: Draw anything you want with smooth, responsive strokes
- **Touch Support**: Works on tablets and touch devices
- **Visual Feedback**: Real-time drawing indicator shows when you're actively drawing

### Art Algorithms

1. **Spiral** - Creates mesmerizing spiral patterns from your drawings
2. **Mandala** - Generates symmetrical, circular patterns with mirrored segments
3. **Fractal** - Produces self-repeating patterns with recursive transformations
4. **Wave** - Applies flowing wave distortions to your artwork
5. **Particle** - Creates an explosion effect with colorful particles
6. **Geometric** - Transforms drawings into patterns with triangles, squares, and circles

### Customization Options

- **Complexity**: Control the intricacy of the generated patterns (1-10)
- **Size**: Adjust the scale of the output (0.5x - 5x)
- **Rotation**: Rotate patterns from 0° to 360°
- **Opacity**: Set transparency levels (0.1 - 1.0)
- **Colors**: Choose primary and secondary colors for gradients

### Additional Features

- **Dual Canvas View**: Switch between your original drawing and generated art
- **Save Artwork**: Download your creations as PNG images
- **Clear Canvas**: Start fresh with a single click
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Usage

1. **Open the Application**
   - Simply open `index.html` in your web browser
   - Or host it on any web server

2. **Start Drawing**
   - Click and drag on the drawing canvas to create your artwork
   - The empty state message will disappear once you start drawing

3. **Choose an Algorithm**
   - Select one of the six available algorithms
   - Each algorithm creates a unique transformation

4. **Customize Your Art**
   - Adjust the sliders to fine-tune the output
   - Change colors to match your vision

5. **Generate Art**
   - Click "Generate Art" to transform your drawing
   - The result will appear in the Generated Art tab

6. **Save Your Creation**
   - Click "Save Art" to download your masterpiece
   - Files are saved as PNG images with timestamps

## 🛠️ Technical Details

### Technologies Used

- **HTML5 Canvas**: For drawing and rendering
- **Vanilla JavaScript**: No frameworks or dependencies
- **CSS3**: Modern styling with animations and transitions
- **Google Fonts**: Outfit font family for clean typography

### Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Considerations

- Optimized drawing algorithms for smooth performance
- Efficient canvas operations
- Responsive design that adapts to screen size
- Hardware-accelerated CSS animations

## 📁 Project Structure

```
algo-gen/
├── index.html      # Main application file (HTML, CSS, and JavaScript)
└── README.md       # This documentation file
```

## 🎯 Algorithm Details

### Spiral Algorithm
- Creates multiple rotated copies of your drawing
- Each copy is scaled and rotated incrementally
- Produces a spiral effect emanating from the center

### Mandala Algorithm
- Divides the canvas into equal segments
- Mirrors and rotates your drawing in each segment
- Creates perfectly symmetrical patterns

### Fractal Algorithm
- Recursively draws scaled copies of your artwork
- Each level creates smaller versions at different positions
- Depth controlled by complexity setting

### Wave Algorithm
- Applies sinusoidal transformations to drawing coordinates
- Multiple waves with different frequencies and phases
- Creates fluid, organic distortions

### Particle Algorithm
- Samples points along your drawing path
- Generates particles that radiate outward
- Each particle has gradient coloring

### Geometric Algorithm
- Places geometric shapes along your drawing path
- Shapes include triangles, squares, and circles
- Rotation and size vary based on position

## 💡 Tips for Best Results

1. **Simple Drawings Work Best**: Start with basic shapes or patterns
2. **Experiment with Settings**: Each algorithm responds differently to the controls
3. **Try Different Colors**: Gradient effects can dramatically change the output
4. **Combine Algorithms**: Draw something new and try different algorithms
5. **Use Full Canvas**: Larger drawings create more impressive results

## 🤝 Contributing

Feel free to fork this project and add your own algorithms or features! Some ideas:

- New transformation algorithms
- Animation capabilities
- More shape options
- Color palette presets
- Undo/redo functionality
- Layer support

## 📄 License

This project is open source and available for personal and educational use.

## 🎨 Examples

The Algorithmic Art Generator can create:
- Stunning mandala patterns from simple doodles
- Complex fractals from basic shapes
- Flowing abstract art from curved lines
- Geometric tessellations from any drawing
- Particle explosions that follow your paths
- Spiral galaxies from circular motions

## 🐛 Known Issues

- Very complex drawings with thousands of points may cause slight performance lag
- Some mobile browsers may have touch sensitivity variations
- Extremely large canvas sizes may impact generation speed

## 📞 Support

For questions, suggestions, or bug reports, please create an issue in the project repository.

---

**Happy Creating! 🎨✨**
