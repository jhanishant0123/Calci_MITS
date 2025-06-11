
# Calculator Web Application

A modern, responsive calculator web application built with React, TypeScript, and Tailwind CSS. Performs basic arithmetic operations with a clean interface optimized for both desktop and mobile devices.

## Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (−), Multiplication (×), Division (÷)
- **Advanced Functions**: Clear (C), Backspace, Decimal points, Percentage (%)
- **Keyboard Support**: Full keyboard input support for enhanced usability
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Modern UI**: Clean, glassmorphism-inspired design with smooth animations
- **Touch-Friendly**: Optimized button sizes and interactions for touch devices

## Technologies Used

- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Fast build tool and development server
- **Lucide React** - Beautiful icons

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd calculator-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:8080`

## Usage

### Button Controls
- **Numbers (0-9)**: Input digits
- **Operators (+, −, ×, ÷)**: Perform arithmetic operations
- **Equals (=)**: Calculate result
- **Clear (C)**: Reset calculator
- **Plus/Minus (±)**: Toggle number sign
- **Percentage (%)**: Calculate percentage
- **Decimal (.)**: Add decimal point

### Keyboard Shortcuts
- **Numbers (0-9)**: Input digits
- **+, -, *, /**: Arithmetic operations
- **Enter or =**: Calculate result
- **Escape or C**: Clear calculator
- **Backspace**: Delete last digit
- **.**: Decimal point
- **%**: Percentage

## Project Structure

```
src/
├── components/
│   ├── Calculator.tsx      # Main calculator container
│   ├── Display.tsx         # Calculator display component
│   ├── ButtonGrid.tsx      # Button layout grid
│   └── CalcButton.tsx      # Individual button component
├── hooks/
│   └── useCalculatorLogic.ts # Calculator logic and state management
├── pages/
│   └── Index.tsx           # Main page component
├── lib/
│   └── utils.ts            # Utility functions
├── index.css               # Global styles and calculator-specific CSS
└── main.tsx                # Application entry point
```

## Build for Production

```bash
npm run build
```

This will create a `dist` folder with the production-ready files.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Lovable](https://lovable.dev) - AI-powered web development platform
- Icons by [Lucide](https://lucide.dev)
- Styled with [Tailwind CSS](https://tailwindcss.com)

## Live Demo

[View Live Demo](https://your-calculator-app.lovable.app)

---

Made with ❤️ using Lovable
