# ImageOptima - Advanced Image Optimization Tool

A modern, accessible, and feature-rich image optimization web application that replaces your files with optimized versions. Built with React, TypeScript, and shadcn/ui.

## ✨ Features

### 🎯 Core Functionality
- **File Replacement**: Optimizes images and replaces original files with optimized versions
- **Multiple Format Support**: JPG, PNG, GIF, WebP, AVIF, and SVG
- **Format Preservation**: Option to preserve original formats (especially useful for SVG files)
- **Batch Processing**: Process multiple images simultaneously
- **Real-time Progress**: Live progress tracking during optimization

### 🚀 Advanced Optimization
- **AI-Powered Compression**: Intelligent compression algorithms
- **Format Conversion**: Convert to modern formats (WebP, AVIF) for better compression
- **Smart Resizing**: Intelligent image resizing with aspect ratio preservation
- **Metadata Removal**: Strip EXIF data to reduce file size
- **Quality Control**: Adjustable quality settings for each format

### 🎨 User Experience
- **Modern UI**: Beautiful, responsive design with glass morphism effects
- **Mobile Optimized**: Fully responsive design for all devices
- **Accessibility**: WCAG 2.1 compliant with keyboard navigation and screen reader support
- **Dark Mode**: Automatic dark mode detection and support
- **PWA Support**: Installable as a progressive web app

### 📊 Analytics & Insights
- **Detailed Statistics**: Comprehensive optimization metrics
- **Visual Comparisons**: Before/after image comparisons with slider
- **Format Distribution**: Charts showing format usage and compression ratios
- **Performance Metrics**: Processing time and efficiency tracking

## 🛠️ Technology Stack

- **Frontend**: React 18, TypeScript, Vite
- **UI Components**: shadcn/ui, Radix UI
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **State Management**: React Hooks
- **Build Tool**: Vite
- **PWA**: Service Worker, Web App Manifest

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd shadcn-ui
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start development server**
   ```bash
   pnpm run dev
   ```

4. **Build for production**
   ```bash
   pnpm run build
   ```

## 📱 PWA Features

The application is a Progressive Web App (PWA) with the following features:

- **Offline Support**: Basic offline functionality with service worker caching
- **Installable**: Can be installed on desktop and mobile devices
- **App-like Experience**: Full-screen mode and native app feel
- **Background Sync**: Handles offline operations when connection is restored

## ♿ Accessibility Features

- **Keyboard Navigation**: Full keyboard support for all interactions
- **Screen Reader Support**: Proper ARIA labels and semantic HTML
- **High Contrast Mode**: Support for high contrast display preferences
- **Reduced Motion**: Respects user's motion preferences
- **Focus Management**: Clear focus indicators and logical tab order

## 📊 Performance Optimizations

- **Lazy Loading**: Images load only when needed
- **Worker Threads**: Image processing in background threads
- **Memory Management**: Automatic cleanup of object URLs
- **Bundle Optimization**: Code splitting and tree shaking
- **Caching**: Service worker caching for static assets

## 🎨 Design System

### Color Palette
- **Primary**: Blue gradient (#3b82f6 to #8b5cf6)
- **Secondary**: Purple accents
- **Success**: Green (#10b981)
- **Warning**: Amber (#f59e0b)
- **Error**: Red (#ef4444)

### Typography
- **Headings**: Inter font family
- **Body**: System font stack
- **Responsive**: Scales appropriately on all devices

### Components
- **Cards**: Glass morphism effect with backdrop blur
- **Buttons**: Gradient backgrounds with hover effects
- **Forms**: Accessible form controls with validation
- **Charts**: Interactive data visualization

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/                 # shadcn/ui components
│   ├── ImageUploader.tsx   # File upload component
│   ├── ImagePreview.tsx    # Image preview component
│   ├── ImageComparison.tsx # Before/after comparison
│   ├── Statistics.tsx      # Analytics and charts
│   └── OptimizationSettings.tsx # Settings panel
├── hooks/
│   ├── usePerformance.ts   # Performance monitoring
│   └── use-toast.ts        # Toast notifications
├── lib/
│   ├── imageOptimizer.ts   # Image processing logic
│   ├── zipUtils.ts         # ZIP file creation
│   └── utils.ts            # Utility functions
├── pages/
│   ├── Index.tsx           # Main application
│   └── NotFound.tsx        # 404 page
└── index.css               # Global styles
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:

```env
VITE_APP_NAME=ImageOptima
VITE_APP_VERSION=1.0.0
VITE_MAX_FILE_SIZE=26214400
```

### Build Configuration
The application uses Vite for building. Key configurations:

- **TypeScript**: Strict mode enabled
- **Tailwind**: Custom configuration with design tokens
- **PWA**: Service worker and manifest generation
- **Optimization**: Code splitting and tree shaking

## 📈 Performance Metrics

- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🔒 Security Features

- **File Validation**: Strict file type and size validation
- **XSS Protection**: Content Security Policy headers
- **Input Sanitization**: All user inputs are sanitized
- **Secure Headers**: HTTPS enforcement and security headers

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Bug Reports

Please use the [GitHub Issues](https://github.com/your-repo/issues) page to report bugs or request features.

## 📞 Support

For support, email support@imageoptima.com or join our Discord community.

---

**Made with ❤️ by the ImageOptima Team**
