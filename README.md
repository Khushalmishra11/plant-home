# 🌿 PlantHome - Your Ultimate Plant Shopping Destination

> Transform your space with our curated collection of beautiful, healthy plants. From beginner-friendly succulents to statement monstera, find your perfect green companion.

![PlantHome Homepage](https://img.shields.io/badge/Status-Production%20Ready-green?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.3.1-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.2-blue?style=for-the-badge&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4.17-blue?style=for-the-badge&logo=tailwindcss)

## 📖 About PlantHome

PlantHome is a modern, responsive e-commerce website dedicated to bringing the beauty of nature into your home. We offer a carefully curated selection of indoor plants, expert care guides, and exceptional customer service to help both novice and experienced plant parents create their perfect green sanctuary.

### ✨ Key Features

- **🌱 Curated Plant Collection**: Over 300+ varieties of healthy, beautiful plants
- **📚 Expert Care Guides**: Detailed care instructions and tips from plant specialists
- **🚚 Free Delivery**: Complimentary shipping on orders over $50
- **🛡️ Plant Guarantee**: 30-day guarantee with free replacements
- **📱 Responsive Design**: Seamless experience across all devices
- **💚 Plant Parent Community**: Join thousands of satisfied customers
- **🔍 Smart Search**: Find plants by care requirements, size, or room type
- **⭐ Customer Reviews**: Real feedback from our plant parent community

## 🛠️ Tech Stack

### Frontend
- **React 18.3.1** - Modern React with hooks and concurrent features
- **TypeScript 5.9.2** - Type-safe development
- **React Router 6.30.1** - Client-side routing (SPA mode)
- **TailwindCSS 3.4.17** - Utility-first CSS framework
- **Vite 7.1.2** - Fast build tool and development server

### Backend
- **Express 5.1.0** - Node.js web framework
- **TypeScript** - Type-safe server development
- **Zod 3.25.76** - Runtime type validation

### UI Components
- **Radix UI** - Accessible, unstyled UI primitives
- **Lucide React** - Beautiful SVG icons
- **Framer Motion** - Smooth animations
- **Sonner** - Toast notifications

### Development Tools
- **Vitest** - Fast unit testing
- **pnpm** - Efficient package manager
- **ESLint & Prettier** - Code formatting and linting
- **TanStack Query** - Data fetching and caching

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/planthome.git
   cd planthome
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:8080`

## 📁 Project Structure

```
planthome/
├── client/                 # React frontend application
│   ├── components/         # Reusable UI components
│   │   ├── ui/            # Base UI components (buttons, cards, etc.)
│   │   └── Navigation.tsx  # Main navigation component
│   ├── pages/             # Route components
│   │   ├── Index.tsx      # Homepage
│   │   └── NotFound.tsx   # 404 page
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility functions
│   ├── App.tsx            # Main app component with routing
│   └── global.css         # Global styles and theme variables
├── server/                # Express backend
│   ├── routes/           # API route handlers
│   └── index.ts          # Server configuration
├── shared/               # Shared types and interfaces
└── public/              # Static assets
```
---

<div align="center">
  <strong>Made with 💚 for plant lovers everywhere by Khushal Mishra</strong>
  <br>
  <sub>Bringing nature home, one plant at a time</sub>
</div>
