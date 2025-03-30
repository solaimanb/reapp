# REAPP

[![TypeScript](https://img.shields.io/badge/TypeScript-5.7.2-blue.svg)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19.0.0-61DAFB.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-6.2.0-646CFF.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.0.17-38B2AC.svg)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18+-339933.svg)](https://nodejs.org/)
[![ESLint](https://img.shields.io/badge/ESLint-9.21.0-4B32C3.svg)](https://eslint.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A modern React application built with TypeScript, Vite, and TailwindCSS.

## 🚀 Features

- ⚡️ [Vite](https://vitejs.dev/) - Lightning fast build tool
- ⚛️ [React 19](https://reactjs.org/) - UI library
- 📘 [TypeScript](https://www.typescriptlang.org/) - Type safety
- 🎨 [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- 🔍 [ESLint](https://eslint.org/) - Code linting
- 📱 Responsive design
- 🏗️ Atomic Design pattern
- 🔄 Modern React practices

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or bun

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/solaimanb/reapp.git
cd reapp
```

2. Install dependencies:

```bash
npm install
# or
bun install
```

3. Create environment file:

```bash
cp .env.example .env.local
```

4. Start the development server:

```bash
npm run dev
# or
bun run dev
```

## 🏗️ Project Structure

```
src/
├── assets/                # Static assets (images, fonts)
├── components/            # UI Components (Atomic Design)
│   ├── atoms/            # Basic building blocks (Button, Input)
│   ├── molecules/        # Combinations of atoms
│   ├── organisms/        # Complex UI components
│   └── templates/        # Page layouts
├── lib/                  # Utilities and shared logic
├── pages/                # Page components
├── routes/               # Routing configuration
├── services/             # API services
│   ├── products/         # Product-related services
│   └── user/            # User-related services
└── styles/              # Global styles
```

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🔧 Configuration

- `vite.config.ts` - Vite configuration
- `tsconfig.json` - TypeScript configuration
- `eslint.config.js` - ESLint configuration
- `.env.local` - Environment variables

## 📦 Dependencies

### Core

- React 19
- TypeScript
- Vite 6
- TailwindCSS

### Development

- ESLint
- TypeScript ESLint
- React ESLint plugins

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- S010 | The Architect
- 0xDEAD | The Phantom
- root@void | The Catalyst
- nullbyte | The Oracle
- syscall | The Sentinel

## 🙏 Acknowledgments

- React team
- Vite team
- TailwindCSS team
