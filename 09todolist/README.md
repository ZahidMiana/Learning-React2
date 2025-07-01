# Todo List App 📝

A modern, fully-featured Todo List application built with React, featuring local storage persistence and a beautiful UI.

## Features ✨

- ✅ Add new todos
- ✏️ Edit existing todos
- 🗑️ Delete todos
- ☑️ Mark todos as complete/incomplete
- 📊 Todo statistics (Total, Completed, Pending)
- 💾 Local storage persistence
- 🎨 Modern, responsive design with Tailwind CSS
- 🌙 Dark theme UI

## Technologies Used 🛠️

- **React** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Context API** - State management
- **Local Storage** - Data persistence

## Getting Started 🚀

1. Clone the repository:
   ```bash
   git clone https://github.com/ZahidMiana/Learning-React2.git
   cd Learning-React2/09todolist
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure 📁

```
src/
├── components/
│   ├── TodoForm.jsx    # Form component for adding todos
│   ├── TodoItem.jsx    # Individual todo item component
│   └── index.js        # Component exports
├── contexts/
│   ├── TodoContext.js  # Context for todo state management
│   └── index.js        # Context exports
├── App.jsx             # Main application component
├── App.css             # Application styles
├── main.jsx            # Application entry point
└── index.css           # Global styles
```

## Features in Detail 📋

### Add Todos
- Clean, intuitive form to add new todos
- Input validation to prevent empty todos
- Auto-focus on input after adding

### Edit Todos
- Double-click or click edit button to modify todos
- Save changes with Enter key or save button
- Cancel editing with Escape key

### Delete Todos
- Remove todos with a single click
- Confirmation built into the UI

### Toggle Completion
- Mark todos as complete/incomplete
- Visual feedback with strikethrough text
- Separate counting of completed vs pending

### Statistics
- Real-time count of total todos
- Track completed and pending items
- Visual progress indication

### Data Persistence
- Automatic saving to browser's local storage
- Data persists between browser sessions
- No server required

## Deployment 🌐

This project can be easily deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

Build for production:
```bash
npm run build
```

## Contributing 🤝

Feel free to fork this project and submit pull requests for any improvements!

## License 📄

This project is open source and available under the [MIT License](LICENSE).+ Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
