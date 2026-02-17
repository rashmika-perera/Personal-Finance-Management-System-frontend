# Personal Finance Management System - Frontend

A modern, responsive web application for managing personal finances built with React, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Dashboard Overview** - Visualize your financial data at a glance
- **Transaction Management** - Track income and expenses
- **Data Visualization** - Interactive charts and graphs using Recharts
- **Document Export** - Generate financial reports in DOCX format
- **Responsive Design** - Fully optimized for desktop and mobile devices
- **Modern UI** - Beautiful interface with Tailwind CSS and Heroicons

## 🛠️ Tech Stack

- **Framework:** React 19.1.0
- **Language:** TypeScript 5.8.3
- **Build Tool:** Vite 6.3.5
- **Styling:** Tailwind CSS 4.1.14
- **Routing:** React Router DOM 7.9.3
- **Charts:** Recharts 3.2.1
- **Icons:** Heroicons 2.2.0
- **Document Generation:** docx 9.5.1
- **File Management:** file-saver 2.0.5

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (version 16.x or higher)
- **npm** (version 8.x or higher) or **yarn**

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rashmika-perera/Personal-Finance-Management-System-frontend.git
   cd Personal-Finance-Management-System-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

## 🚀 Running the Application

### Development Mode

Start the development server with hot-reload:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

### Production Build

Build the application for production:

```bash
npm run build
# or
yarn build
```

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
# or
yarn preview
```

## 📁 Project Structure

```
Personal-Finance-Management-System-frontend/
├── src/
│   ├── assets/         # Static assets (images, fonts, etc.)
│   ├── components/     # Reusable React components
│   ├── contexts/       # React context providers
│   ├── data/          # Mock data and constants
│   ├── pages/         # Page components
│   ├── utils/         # Utility functions and helpers
│   ├── App.tsx        # Main application component
│   ├── main.tsx       # Application entry point
│   └── index.css      # Global styles
├── public/            # Public static files
├── index.html         # HTML template
├── package.json       # Project dependencies
├── tsconfig.json      # TypeScript configuration
├── vite.config.ts     # Vite configuration
└── tailwind.config.js # Tailwind CSS configuration
```

## 🧪 Code Quality

### Linting

Run ESLint to check code quality:

```bash
npm run lint
# or
yarn lint
```

## 🔗 Backend Integration

This frontend application is designed to work with a backend API. To test the backend connection:

```bash
node test-connection.js
```

Make sure to configure your API endpoint in the appropriate configuration file before running the application.

## 🎨 Styling

This project uses Tailwind CSS for styling. The configuration can be found in:
- `tailwind.config.js` - Tailwind configuration
- `src/index.css` - Global styles and Tailwind directives

## 📦 Key Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| React | ^19.1.0 | UI framework |
| TypeScript | ~5.8.3 | Type safety |
| Vite | ^6.3.5 | Build tool |
| React Router DOM | ^7.9.3 | Routing |
| Tailwind CSS | ^4.1.14 | Styling |
| Recharts | ^3.2.1 | Data visualization |
| Heroicons | ^2.2.0 | Icons |
| docx | ^9.5.1 | Document generation |

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview production build |

## 🐛 Troubleshooting

### Port Already in Use
If port 5173 is already in use, Vite will automatically use the next available port.

### Build Errors
Make sure all dependencies are installed:
```bash
rm -rf node_modules package-lock.json
npm install
```

### TypeScript Errors
Check your TypeScript configuration in `tsconfig.json` and ensure all type definitions are installed.

## 📄 License

This project is private and not licensed for public use.

## 👨‍💻 Author

**Rashmika Perera**
- GitHub: [@rashmika-perera](https://github.com/rashmika-perera)

## 🙏 Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Recharts for beautiful and customizable charts
- All other open-source contributors

---

**Note:** This is the frontend application. Make sure the backend server is running for full functionality.
