# ToDoApp

A modern, responsive Todo List application built with React and Tailwind CSS. Features a clean interface with dark mode support and the ability to save/load your todos to/from JSON files.

## Features

- Clean and modern user interface
- Dark mode support
- Save todos to JSON file
- Load todos from JSON file
- Mark todos as complete/incomplete
- Delete todos
- Responsive design

## Technologies Used

- React 19
- Vite
- Tailwind CSS
- ESLint

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd ToDoApp
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be available in the `dist` directory.

## Usage

- Add new todos by typing in the input field and clicking "Add" or pressing Enter
- Toggle dark mode using the sun/moon button in the top right
- Mark todos as complete by clicking the checkbox
- Delete todos using the trash icon
- Save your todos to a JSON file using the "Save to File" button
- Load previously saved todos using the "Load from File" button

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint