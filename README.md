
# Web App Components

This package contains all the UI components and pages from the web application.

## Setup Instructions

1. Create a new React project:
```bash
npm create vite@latest my-web-app -- --template react-ts
cd my-web-app
```

2. Install dependencies:
```bash
npm install @radix-ui/react-dropdown-menu @radix-ui/react-label @radix-ui/react-radio-group @radix-ui/react-tabs @radix-ui/react-collapsible @tanstack/react-query framer-motion lucide-react class-variance-authority clsx tailwind-merge
```

3. Install dev dependencies:
```bash
npm install -D tailwindcss autoprefixer postcss
```

4. Setup Tailwind CSS:
```bash
npx tailwindcss init -p
```

5. Copy the components to your `src/components/ui/` directory
6. Copy the pages to your `src/pages/` directory
7. Copy the utils.ts file to your `src/lib/` directory

## File Structure

```
src/
├── components/
│   └── ui/
│       ├── dropdown-menu.tsx
│       ├── input.tsx
│       ├── label.tsx
│       ├── radio-group.tsx
│       ├── tabs.tsx
│       └── collapsible.tsx
├── pages/
│   └── home.tsx
└── lib/
    └── utils.ts
```

## Usage

Import and use the components in your React application:

```tsx
import { Button } from "@/components/ui/button"
import { Input } from "@/components/ui/input"
import Home from "@/pages/home"
```

## Dependencies

- React 18+
- TypeScript
- Tailwind CSS
- Radix UI components
- Framer Motion for animations
- TanStack Query for API management
- Lucide React for icons
