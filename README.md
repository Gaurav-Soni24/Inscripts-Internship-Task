# Inscripts Table - React Intern Assignment

A pixel-perfect spreadsheet interface implementation built with Next.js, TypeScript, and Tailwind CSS. This project recreates the Google Sheets/Excel-like experience as specified in the Figma design.

## 🚀 Live Demo

[Live Application URL](https://inscripts-internship-task.vercel.app/)

## 📋 Assignment Overview

This project fulfills the React Intern Assignment requirements by creating a static, front-end-only prototype that visually matches the provided Figma design for a spreadsheet view interface.

**Original Requirements:**
- Build a pixel-perfect experience matching the Figma design
- Implement Google Sheet/Excel-like spreadsheet functionality
- Ensure all interactive elements are functional (buttons/tabs change state)
- Clean, maintainable code with TypeScript strict mode

## 🛠 Tech Stack

- **Framework:** Next.js 15.2.4 (instead of Vite React)
- **Language:** TypeScript 5+ (strict mode)
- **Styling:** Tailwind CSS 4
- **UI Components:** Radix UI primitives
- **Icons:** Lucide React
- **Runtime:** React 19

## 📦 Dependencies

### Core Dependencies
- `next` - Next.js framework for React applications
- `react` & `react-dom` - React library and DOM bindings
- `typescript` - TypeScript for type safety

### UI & Styling
- `tailwindcss` - Utility-first CSS framework
- `@tailwindcss/postcss` - PostCSS integration for Tailwind
- `tailwind-merge` - Utility for merging Tailwind classes
- `clsx` - Utility for constructing className strings
- `class-variance-authority` - Creating variant-based component APIs
- `tw-animate-css` - Additional animations for Tailwind

### Components
- `@radix-ui/react-avatar` - Accessible avatar component
- `@radix-ui/react-slot` - Composition utility for components
- `lucide-react` - Beautiful icon library

## 🏃‍♂️ Getting Started

### Prerequisites
- Node.js 18.17 or later
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd inscripts-table
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🧪 Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality checks

## 📁 Project Structure

```
inscripts-table/
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles and Tailwind imports
│   ├── layout.tsx         # Root layout component
│   └── page.tsx          # Main page component
├── components/            # Reusable UI components
│   ├── ui/               # Base UI components (buttons, etc.)
│   └── spreadsheet/      # Spreadsheet-specific components
├── lib/                  # Utility functions and helpers
├── public/               # Static assets
├── package.json
├── tailwind.config.js    # Tailwind configuration
├── tsconfig.json         # TypeScript configuration
└── README.md
```

## ✅ Implementation Details

### Core Features Implemented
- ✅ Pixel-perfect layout matching Figma design
- ✅ Google Sheets/Excel-like spreadsheet interface
- ✅ Interactive buttons and tabs with state management
- ✅ TypeScript strict mode compliance
- ✅ Responsive design principles
- ✅ Clean component architecture

### Interactive Elements
- Tab navigation with active state management
- Clickable toolbar buttons with console logging
- Cell selection and hover states
- Functional dropdown menus and controls

## 🔧 Technical Trade-offs & Decisions

### Next.js vs Vite React
**Decision:** Used Next.js instead of the suggested Vite + React setup.

**Reasoning:**
- **Performance:** Next.js 15 with Turbopack provides faster development builds
- **Production Ready:** Built-in optimizations for production deployment
- **Developer Experience:** Superior TypeScript integration and error handling
- **Deployment:** Seamless deployment options (Vercel, Netlify, etc.)
- **Future Scalability:** Easier transition to full-stack if backend features are needed

**Trade-offs:**
- Slightly larger bundle size compared to pure Vite setup
- Framework-specific patterns vs vanilla React approach
- Additional Next.js concepts (though minimal for this static use case)

### Component Architecture
- Used Radix UI primitives for accessibility and consistency
- Implemented compound component patterns for complex UI elements
- Separated concerns between layout, data, and presentation components

### Styling Approach
- Leveraged Tailwind CSS 4 for rapid development
- Used CSS custom properties for theme consistency
- Implemented responsive design patterns

## 🎯 Acceptance Criteria Status

- ✅ **Pixel-close layout** - Matches Figma design specifications
- ✅ **Spreadsheet experience** - Interactive grid with cell selection
- ✅ **Interactive elements** - All buttons/tabs functional with state changes
- ✅ **Code quality** - Passes lint checks and type validation
- ✅ **Clean commits** - Meaningful commit history maintained

## 🚀 Deployment

The application is optimized for static deployment and can be deployed to:
- Vercel (recommended for Next.js)
- Netlify
- GitHub Pages
- Any static hosting service

For static export (if needed):
```bash
npm run build
```

## 📝 Notes

This implementation prioritizes code quality, maintainability, and user experience while staying true to the original design requirements. The choice of Next.js over Vite provides additional benefits for production deployment and developer experience without compromising the core assignment objectives.

---

**Built with ❤️ for the React Intern Assignment**