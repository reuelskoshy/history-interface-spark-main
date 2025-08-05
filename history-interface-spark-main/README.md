# History Interface Spark

A web application showcasing the evolution of Human-Computer Interaction (HCI) interfaces across different eras.

## Features

- Timeline of HCI history
- Interactive demos
- Future trends section
- Responsive design
- Modern UI with shadcn-ui and Tailwind CSS

## Technologies Used

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [shadcn-ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
- [React Router](https://reactrouter.com/)
- [TanStack React Query](https://tanstack.com/query/latest)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)

### Installation

```sh
git clone <YOUR_GIT_URL>
cd history-interface-spark-main
npm install
```

### Development

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal) to view the app.

### Build

```sh
npm run build
```

### Preview Production Build

```sh
npm run preview
```

## Project Structure

```
src/
  components/
    ui/                # UI components (Sheet, Toaster, etc.)
    HeroSection.tsx
    TimelineSection.tsx
    InteractiveDemo.tsx
    FutureSection.tsx
    Footer.tsx
  pages/
    Index.tsx          # Main landing page
    NotFound.tsx       # 404 page
  assets/              # Images and static assets
  main.tsx             # App entry point
  App.tsx              # App root component
  index.css            # Global styles
```

## Customization

- Update content in `src/pages/Index.tsx` and components in `src/components/` to fit your needs.
- Change styles in `src/index.css` and Tailwind config.

## Authors

- Saranya Ray 
- Reuel Sajeev Koshy

## License

MIT

