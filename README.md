# Material Management System 🏭

A modern, responsive web application for managing materials, suppliers, and vendors with multi-language support and intuitive dashboards.

![Material Management System](https://img.shields.io/badge/React-18.3.1-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue)
![Vite](https://img.shields.io/badge/Vite-5.4.2-purple)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-cyan)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Project Overview

The Material Management System is a comprehensive web application designed to streamline material inventory management for businesses. It provides an intuitive interface for tracking materials, managing supplier relationships, and monitoring vendor activities. The system features a modern, responsive design with multi-language support, making it accessible to diverse teams and organizations.

### 🎯 Key Features

- **Material Inventory Management**: Track and manage material stock levels, specifications, and details
- **Multi-Language Support**: Available in English and Hindi with easy language switching
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Advanced Filtering**: Filter materials by category, supplier, availability, and more
- **Search Functionality**: Quick search across all material properties
- **Supplier Dashboard**: Dedicated interface for supplier management and tracking
- **Vendor Dashboard**: Comprehensive vendor management with performance metrics
- **Material Details Modal**: Detailed view of individual materials with comprehensive information
- **Modern UI/UX**: Clean, intuitive interface built with Tailwind CSS

## 🛠️ Technology Stack

- **Frontend Framework**: React 18.3.1
- **Language**: TypeScript 5.5.3
- **Build Tool**: Vite 5.4.2
- **Styling**: Tailwind CSS 3.4.1
- **Icons**: Lucide React 0.344.0
- **Code Quality**: ESLint 9.9.1
- **CSS Processing**: PostCSS 8.4.35 with Autoprefixer 10.4.18

## 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js**: Version 18.0.0 or higher
- **npm**: Version 8.0.0 or higher (comes with Node.js)
- **Git**: For cloning the repository

You can check your current versions by running:
```bash
node --version
npm --version
git --version
```

## 🚀 Installation Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/pranjal2410719/Material-Management-System.git
cd Material-Management-System
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:5173/` (or another port if 5173 is in use).

### 4. Build for Production

```bash
npm run build
```

The production build will be created in the `dist/` directory.

### 5. Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
Material-Management-System/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── FilterPanel.tsx  # Material filtering interface
│   │   ├── LanguageSelector.tsx  # Language switching component
│   │   ├── MaterialCard.tsx # Material display card
│   │   ├── MaterialDetailsModal.tsx  # Material details popup
│   │   └── MaterialsTable.tsx  # Materials table view
│   ├── data/               # Static data and configurations
│   │   ├── materials.ts    # Sample material data
│   │   └── translations.ts # Multi-language translations
│   ├── hooks/              # Custom React hooks
│   │   └── useLanguage.ts  # Language management hook
│   ├── pages/              # Main application pages
│   │   ├── HomePage.tsx    # Main dashboard page
│   │   ├── SupplierDashboard.tsx  # Supplier management
│   │   └── VendorDashboard.tsx    # Vendor management
│   ├── types/              # TypeScript type definitions
│   │   └── index.ts        # Global type definitions
│   ├── App.tsx             # Main application component
│   ├── main.tsx            # Application entry point
│   ├── index.css           # Global styles and Tailwind imports
│   └── vite-env.d.ts       # Vite environment types
├── public/                 # Static assets
├── dist/                   # Production build output
├── package.json            # Project dependencies and scripts
├── vite.config.ts          # Vite configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
├── eslint.config.js        # ESLint configuration
└── README.md               # Project documentation
```

## ✨ Features

### 🏠 Home Dashboard
- **Material Overview**: View all materials in a clean, organized layout
- **Quick Stats**: See total materials, categories, and availability at a glance
- **Search & Filter**: Find materials quickly using the search bar and advanced filters
- **Language Toggle**: Switch between English and Hindi instantly

### 🔍 Material Management
- **Material Cards**: Visual representation of each material with key information
- **Detailed View**: Click on any material to see comprehensive details including:
  - Material specifications and properties
  - Supplier information and contact details
  - Stock levels and availability status
  - Category and classification
  - Pricing and cost information
- **Advanced Filtering**: Filter by:
  - Category (Electronics, Textiles, Metals, etc.)
  - Supplier
  - Availability status
  - Price range

### 🏢 Supplier Dashboard
- **Supplier Management**: Track and manage supplier relationships
- **Performance Metrics**: Monitor supplier performance and reliability
- **Contact Information**: Maintain up-to-date supplier contact details
- **Material Associations**: View which materials are supplied by each vendor

### 🤝 Vendor Dashboard
- **Vendor Tracking**: Comprehensive vendor management system
- **Performance Analytics**: Track vendor performance and delivery metrics
- **Contract Management**: Monitor vendor contracts and agreements
- **Communication Tools**: Maintain vendor communication history

### 🌐 Multi-Language Support
- **Bilingual Interface**: Full support for English and Hindi
- **Dynamic Translation**: All text elements are dynamically translated
- **User Preference**: Language preference is maintained across sessions
- **Localized Content**: Numbers, dates, and currency formatted according to locale

### 📱 Responsive Design
- **Mobile-First**: Optimized for mobile devices with touch-friendly interface
- **Tablet Support**: Perfect layout for tablet devices
- **Desktop Experience**: Full-featured desktop interface with advanced functionality
- **Cross-Browser**: Compatible with all modern web browsers

## 📖 Usage Guide

### Getting Started
1. **Launch the Application**: After installation, run `npm run dev` and open `http://localhost:5173`
2. **Language Selection**: Use the language selector in the top-right corner to switch between English and Hindi
3. **Navigation**: Use the navigation menu to switch between different sections

### Managing Materials
1. **View Materials**: The home page displays all materials in a card layout
2. **Search Materials**: Use the search bar to find specific materials by name, category, or supplier
3. **Filter Materials**: Use the filter panel to narrow down materials by various criteria
4. **View Details**: Click on any material card to open the detailed view modal
5. **Material Information**: In the detail modal, you can view:
   - Complete material specifications
   - Supplier contact information
   - Stock levels and availability
   - Pricing information

### Using Dashboards
1. **Supplier Dashboard**: Navigate to the supplier section to:
   - View all suppliers
   - Track supplier performance
   - Manage supplier relationships
   - View supplier-specific materials

2. **Vendor Dashboard**: Access the vendor section to:
   - Monitor vendor activities
   - Track performance metrics
   - Manage vendor contracts
   - View vendor-related materials

### Customization
- **Language Preference**: Your language selection is automatically saved
- **Filter Preferences**: Applied filters remain active during your session
- **Responsive Layout**: The interface automatically adapts to your screen size

## 🎨 Screenshots

*Note: Screenshots can be added here to showcase the application interface*

### Home Dashboard
```
[Screenshot of the main dashboard showing material cards and navigation]
```

### Material Details Modal
```
[Screenshot of the material details popup with comprehensive information]
```

### Supplier Dashboard
```
[Screenshot of the supplier management interface]
```

### Mobile View
```
[Screenshot showing the responsive mobile interface]
```

## 🤝 Contributing Guidelines

We welcome contributions to the Material Management System! Here's how you can help:

### Getting Started
1. **Fork the Repository**: Click the "Fork" button on GitHub
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/Material-Management-System.git
   cd Material-Management-System
   ```
3. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Development Process
1. **Install Dependencies**: `npm install`
2. **Start Development Server**: `npm run dev`
3. **Make Your Changes**: Implement your feature or bug fix
4. **Test Your Changes**: Ensure everything works correctly
5. **Run Linting**: `npm run lint` to check code quality
6. **Build Project**: `npm run build` to ensure production build works

### Submitting Changes
1. **Commit Your Changes**:
   ```bash
   git add .
   git commit -m "Add: your descriptive commit message"
   ```
2. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
3. **Create Pull Request**: Submit a PR with a clear description of your changes

### Code Standards
- **TypeScript**: Use TypeScript for all new code
- **ESLint**: Follow the existing ESLint configuration
- **Formatting**: Use consistent formatting (Prettier recommended)
- **Comments**: Add comments for complex logic
- **Testing**: Add tests for new features when applicable

### What to Contribute
- 🐛 **Bug Fixes**: Report and fix bugs
- ✨ **New Features**: Add new functionality
- 📚 **Documentation**: Improve documentation and examples
- 🎨 **UI/UX**: Enhance user interface and experience
- 🌐 **Translations**: Add support for more languages
- ⚡ **Performance**: Optimize application performance

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ **Commercial Use**: You can use this project for commercial purposes
- ✅ **Modification**: You can modify the source code
- ✅ **Distribution**: You can distribute the original or modified code
- ✅ **Private Use**: You can use this project privately
- ❗ **Liability**: The authors are not liable for any damages
- ❗ **Warranty**: This project comes with no warranty

## 🙏 Acknowledgments

- **React Team**: For the amazing React framework
- **Vite Team**: For the lightning-fast build tool
- **Tailwind CSS**: For the utility-first CSS framework
- **Lucide**: For the beautiful icon library
- **TypeScript Team**: For bringing type safety to JavaScript

## 📞 Support & Contact

- **Issues**: Report bugs and request features on [GitHub Issues](https://github.com/pranjal2410719/Material-Management-System/issues)
- **Discussions**: Join discussions on [GitHub Discussions](https://github.com/pranjal2410719/Material-Management-System/discussions)
- **Email**: Contact the maintainer at [your-email@example.com]

## 🔄 Version History

### v1.0.0 (Current)
- ✅ Initial release
- ✅ Material management system
- ✅ Multi-language support (English/Hindi)
- ✅ Responsive design
- ✅ Supplier and vendor dashboards
- ✅ Advanced filtering and search
- ✅ Material details modal

## 🚀 Future Roadmap

- 🔐 **User Authentication**: Add login and user management
- 💾 **Database Integration**: Connect to a backend database
- 📊 **Analytics Dashboard**: Add charts and analytics
- 📱 **Mobile App**: Develop native mobile applications
- 🌍 **More Languages**: Add support for additional languages
- 🔔 **Notifications**: Add real-time notifications
- 📈 **Reporting**: Generate detailed reports
- 🔄 **API Integration**: Connect with external systems

## 📚 Additional Resources

- [React Documentation](https://reactjs.org/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs)
- [Vite Guide](https://vitejs.dev/guide)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Material Design Guidelines](https://material.io/design)

---

**Made with ❤️ by the Material Management System Team**

*If you find this project helpful, please consider giving it a ⭐ on GitHub!*