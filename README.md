# My Svelte TypeScript Project

This project is a modern web application built with Svelte and TypeScript. It leverages several tools and libraries to provide a seamless development experience and high performance.

## Features

- **Svelte**: A powerful framework for building reactive user interfaces with minimal effort.
- **TypeScript**: Ensures strong typing for better code maintainability and reduced runtime errors.
- **Database**: Features integration with SQLite using **Drizzle ORM** for database management.
- **Authentication**: Secure user authentication powered by **Lucia**.
- **CSS**: Styled using **Tailwind CSS**, providing utility-first classes for fast and scalable design.
- **Bundling and Dev Server**: Utilizes **Vite** for fast builds and a smooth development experience.

## Installation

To set up the project locally, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (compatible with Bun)
- [Bun](https://bun.sh/) (Package Manager)

### Steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install dependencies with Bun:
   ```bash
   bun install
   ```

3. Start the development server:
   ```bash
   bun run dev
   ```

4. Open your browser at `http://localhost:3000` to see the app in action.

## Scripts

Here are some useful scripts provided by the project:

- **Start Development**: `bun run dev`
- **Build Production**: `bun run build`
- **Lint Code**: `bun run lint`
- **Format Code**: `bun run format`

## Configuration

The project configuration is managed through environment variables and configuration files. Ensure all required environment variables are set in a `.env` file before starting the application.

## Folder Structure