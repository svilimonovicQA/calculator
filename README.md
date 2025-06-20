# Calculator App

A modern, responsive calculator web application built with HTML, CSS, and vanilla JavaScript. This project implements a fully functional calculator with a clean user interface and comprehensive features.

## 🚀 Features

### Core Functionality

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Clear Function**: Reset calculator to initial state
- **Delete Function**: Remove last entered digit
- **Decimal Support**: Handle decimal numbers with validation
- **Chaining Operations**: Perform multiple calculations in sequence
- **Number Formatting**: Display large numbers with comma separators

### User Experience

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean interface with gradient background and smooth animations
- **Visual Feedback**: Button hover effects and press animations
- **Dual Display**: Shows current input and previous operation context

### Advanced Features

- **Keyboard Support**: Full keyboard navigation and input
- **Error Handling**: Division by zero protection with user alerts
- **Input Validation**: Prevents multiple decimal points in a single number
- **Edge Case Handling**: Robust handling of various input scenarios

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Grid layout, Flexbox, and animations
- **JavaScript (ES6+)**: Object-oriented programming with classes and modern syntax
- **CSS Grid**: Responsive calculator button layout
- **CSS Custom Properties**: Maintainable color scheme and spacing

## 📁 Project Structure

```
calculator/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and layout
├── script.js           # JavaScript calculator logic
├── README.md           # Project documentation
└── LICENSE             # License file
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation & Usage

1. **Clone or Download**: Get the project files to your local machine
2. **Open**: Navigate to the project directory
3. **Run**: Open `index.html` in your web browser
4. **Use**: Start calculating!

### Alternative Methods

**Method 1: Direct File Opening**

```bash
# Navigate to project directory
cd calculator
# Open in default browser (Windows)
start index.html
# Open in default browser (macOS)
open index.html
# Open in default browser (Linux)
xdg-open index.html
```

**Method 2: Local Server**

```bash
# Using Python 3
python -m http.server 8000
# Then visit: http://localhost:8000

# Using Node.js (with http-server)
npx http-server
```

## 🎮 How to Use

### Mouse/Touch Input

- Click number buttons (0-9) to input numbers
- Click operation buttons (+, -, ×, ÷) to select operations
- Click equals (=) to calculate result
- Click Clear (C) to reset calculator
- Click Delete (DEL) to remove last digit
- Click decimal (.) to add decimal point

### Keyboard Input

| Key            | Function          |
| -------------- | ----------------- |
| `0-9`          | Number input      |
| `+`            | Addition          |
| `-`            | Subtraction       |
| `*`            | Multiplication    |
| `/`            | Division          |
| `Enter` or `=` | Calculate result  |
| `Escape`       | Clear calculator  |
| `Backspace`    | Delete last digit |
| `.`            | Decimal point     |

### Example Calculations

```
Basic: 5 + 3 = 8
Decimal: 10.5 × 2 = 21
Chaining: 8 - 3 = 5, then × 4 = 20
Large numbers: 1,234 + 5,678 = 6,912
```

## 🏗️ Architecture

### HTML Structure

- Semantic HTML5 with proper accessibility considerations
- Grid-based layout for calculator buttons
- Separate display area for current and previous operands

### CSS Design

- Mobile-first responsive design
- CSS Grid for button layout
- CSS Custom Properties for consistent theming
- Smooth transitions and hover effects
- Modern gradient background

### JavaScript Implementation

- **Calculator Class**: Object-oriented approach for maintainability
- **Event Handling**: Comprehensive mouse and keyboard event management
- **Error Handling**: Robust error checking and user feedback
- **Input Validation**: Prevents invalid input combinations
- **Display Management**: Handles number formatting and display updates

## 🧪 Testing

The calculator has been thoroughly tested for:

### Functionality Testing

- ✅ All basic arithmetic operations
- ✅ Decimal number calculations
- ✅ Chaining multiple operations
- ✅ Clear and delete functions
- ✅ Keyboard input support

### Error Handling Testing

- ✅ Division by zero scenarios
- ✅ Multiple decimal point prevention
- ✅ Invalid operation sequences
- ✅ Edge cases with large numbers

### UI/UX Testing

- ✅ Responsive design on various screen sizes
- ✅ Button interactions and animations
- ✅ Display formatting and readability
- ✅ Accessibility considerations

## 🎨 Customization

### Color Scheme

Modify CSS custom properties in `styles.css`:

```css
:root {
  --primary-color: #2196f3;
  --secondary-color: #ffb700;
  --danger-color: #ff5252;
  --background-gradient: linear-gradient(to right, #00aaff, #00ff6c);
}
```

### Layout Modifications

- Adjust grid layout in `.calculator` class
- Modify button sizing and spacing
- Customize display area appearance

### Functionality Extensions

- Add memory functions (M+, M-, MR, MC)
- Implement scientific calculator features
- Add calculation history
- Include unit conversions

## 🐛 Known Issues & Limitations

- Very large numbers may exceed JavaScript's precision limits
- No calculation history feature
- No memory functions (planned for future versions)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and enhancement requests.

### Development Setup

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the [App Ideas Collection](https://github.com/florinpop17/app-ideas)
- Modern CSS techniques and best practices
- Accessibility guidelines and standards

## 📞 Support

If you encounter any issues or have questions:

1. Check the existing issues in the repository
2. Create a new issue with detailed description
3. Include browser information and steps to reproduce

---

**Made with ❤️ using vanilla HTML, CSS, and JavaScript**
