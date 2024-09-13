# TodoApp

TodoApp is a task management application built with React and TypeScript. It allows users to add tasks, mark them as completed, delete tasks, and bulk delete completed tasks. The UI is created using React, while TypeScript ensures type safety.

## Technologies Used

- **React**: For building the user interface.
- **TypeScript**: For type safety and improved developer experience.
- **Vite**: For fast and modern build tooling.

## Project Structure

- **`src`**: Contains the source code for the application.
  - **`src/assets`**: Static files, such as SVG icons.
  - **`src/components`**: Application components.
  - **`src/data`**: Data files for the project.
  - **`src/hooks`**: Custom React hooks.
  - **`src/types`**: TypeScript type definitions.
  - **`src/App.tsx`**: Main application component.
  - **`src/index.css`**: CSS for styling.
  - **`src/main.tsx`**: Entry point and rendering logic.
  - **`src/vite-env.d.ts`**: Type definitions for Vite.

## Screenshots

### Home Page

![Home Page](https://github.com/ahmetcann0/TodoApp/blob/main/TodoApp_UI.png)

## Setup

To get the project running locally:

1. **Install dependencies**:

    ```bash
    npm install
    ```

2. **Start the development server**:

    ```bash
    npm run dev
    ```

Visit `http://localhost:5173` in your browser to see the application in action. If the port is different, please check your `vite.config.ts` file for the correct port number.
