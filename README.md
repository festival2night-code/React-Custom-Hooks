# React Custom Hooks

A React app that demonstrates reusable custom hooks alongside a compound menu built from composable components.

---

##  Features

- **Compound Menu** – Compose a menu from separate button, dropdown, and item components.
- **Reusable Toggle Hook** – Share toggle state and optional change callbacks with `useToggle`.
- **Update-Only Effect Hook** – Run an effect after dependency changes, skipping the initial render.
- **Star Component** – Toggle a star icon using `react-icons`.
- **Reusable Button** – Apply optional size and variant classes with `classnames`.

---

##  Tech Stack

- React 18
- JavaScript (JSX)
- Vite 8
- `@vitejs/plugin-react` (JSX transform + Fast Refresh)
- `react-icons` for star icons
- `classnames` for conditional button styles
- React Context and custom hooks
- CSS

---

##  Getting Started

Requires Node.js 20.19+ or 22.12+.

### 1. Install Dependencies

```bash
npm install
```

### 2. Start Development Server

```bash
npm run dev
```

### 3. Open Browser

Visit http://localhost:5173

---

##  Build for Production

```bash
npm run build     # outputs to dist/
npm run preview   # preview the production build locally
```

---

##  Project Structure

```text
.
├── components/
│   ├── Button/
│   │   └── Button.jsx         # Reusable button with style variants
│   ├── Menu/
│   │   ├── Menu.jsx           # Compound menu state and context
│   │   ├── MenuButton.jsx     # Menu toggle button
│   │   ├── MenuDropdown.jsx   # Conditionally rendered menu
│   │   ├── MenuItem.jsx       # Menu item
│   │   └── index.js           # Compound menu exports
│   └── Star.jsx               # Toggleable star icon
├── hooks/
│   ├── useEffectOnUpdate.js   # Effect that skips the initial render
│   └── useToggle.js           # Reusable boolean toggle hook
├── index.html                 # HTML entry point and page metadata
├── index.jsx                  # React entry point
├── package.json               # Scripts and dependencies
├── package-lock.json          # Locked dependency versions
├── style.css                  # Component and page styles
└── vite.config.js             # Vite and React plugin configuration
```

---

##  What I Learned

- Creating reusable custom hooks for shared state and effects
- Composing React components with context and compound components
- Passing callbacks between components
- Applying conditional classes with `classnames`
- Using `react-icons` for interface icons

---

##   Author

Leung

##   License

No license is currently specified for this project.
