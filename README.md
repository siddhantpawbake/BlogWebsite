# 🚀 BlogWebsite

<div align="center">

![Logo](https://github.com/siddhantpawbake/BlogWebsite/blob/master/public/logo.png?raw=true)

**A modern, responsive blog platform built with Vite, React and Tailwind CSS.**

[Live Demo](https://blog-website-omega-fawn.vercel.app)

</div>

## 📖 Overview

This project is a sophisticated blog website designed to provide a seamless content publishing and consumption experience. Built with a modern frontend stack, it offers a robust foundation for creating, managing, and displaying blog posts. The application focuses on delivering a fast, responsive, and visually appealing user interface for both content creators and readers.

## ✨ Features

-   **Dynamic Blog Post Display**: Renders blog posts efficiently, likely supporting rich content.
-   **Responsive Design**: Adapts gracefully across various devices and screen sizes, ensuring a consistent user experience (inferred from Tailwind CSS usage).
-   **Fast Development Experience**: Leverages Vite for rapid development and optimized build processes.
-   **Modern UI Components**: Utilizes React for a component-based architecture, promoting reusability and maintainability.
-   **Configurable Environment**: Supports environment variables for flexible configuration.

## 🖼️ Screenshots

### 📸 Screenshot 1
<img src="https://github.com/siddhantpawbake/BlogWebsite/blob/master/public/Login.jpg?raw=true" alt="Screenshot 1" width="100%" style="margin-bottom: 20px;" />

### 📸 Screenshot 2
<img src="https://github.com/siddhantpawbake/BlogWebsite/blob/master/public/Home.jpg?raw=true" alt="Home Page" width="100%" />## 🛠️ Tech Stack

**Frontend:**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)

![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

**DevOps & Hosting:**

![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## 🚀 Quick Start

### Prerequisites
-   Node.js (LTS version recommended, e.g., 18.x or higher)
-   npm (Node Package Manager)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/siddhantpawbake/BlogWebsite.git
    cd BlogWebsite
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment setup**
    ```bash
    cp .env.sample .env
    # Configure your environment variables in the .env file.
    # While .env.sample is empty, typical Vite applications use
    # VITE_ prefixed variables for client-side exposure.
    # Example: VITE_API_BASE_URL=http://localhost:3000/api
    ```

4.  **Start development server**
    ```bash
    npm run dev
    ```

5.  **Open your browser**
    Visit `http://localhost:5173` (default Vite development port).

## 📁 Project Structure

```
BlogWebsite/
├── public/                 # Static assets (e.g., favicon.ico, logo.svg)
├── src/                    # Application source code
│   ├── assets/             # Static assets used by components
│   ├── components/         # Reusable React components
│   ├── App.jsx             # Main application component
│   ├── main.jsx            # Entry point for React application
│   └── index.css           # Global styles (inferred)
├── .env.sample             # Example environment variables
├── .gitignore              # Files/directories to ignore in Git
├── index.html              # Main HTML file
├── package.json            # Project metadata and dependencies
├── package-lock.json       # Records exact dependency versions
├── eslint.config.js        # ESLint configuration
└── vite.config.js          # Vite build configuration
```

## ⚙️ Configuration

### Environment Variables
The project uses `.env` files for environment-specific configurations. A `.env.sample` file is provided, though currently empty.

| Variable | Description | Default | Required |

|----------|-------------|---------|----------|

| `VITE_EXAMPLE_VAR` | An example variable (adjust as per actual usage) | `value` | No |

| `NODE_ENV` | Application environment (e.g., development, production) | `development` | Yes |

### Configuration Files
-   `vite.config.js`: Configures Vite for building and development, including React plugin and potentially CSS pre-processors.
-   `eslint.config.js`: Defines linting rules and configurations to maintain code quality.

## 🔧 Development

### Available Scripts
The following scripts are defined in `package.json`:

| Command | Description |

|---------|-------------|

| `npm run dev` | Starts the development server with Vite, enabling hot-module replacement. |

| `npm run build` | Compiles the application for production deployment into the `dist/` directory. |

| `npm run lint` | Runs ESLint to check for code style issues and potential errors. |

| `npm run preview` | Serves the production build locally to preview it before deployment. |

### Development Workflow
1.  Run `npm install` to set up the project.
2.  Start the development server using `npm run dev`.
3.  Develop in your preferred editor, making use of HMR for instant feedback.
4.  Before committing, run `npm run lint` to ensure code quality.

## 🚀 Deployment

This project is set up for easy deployment of a static site. The `homepage` URL provided in the repository metadata indicates it is deployed on Vercel.

### Production Build
To create a production-ready build of the application:
```bash
npm run build
```
This command will generate optimized static assets in the `dist/` directory, which can then be served by any static hosting provider.

### Deployment Options
-   **Vercel**: Given the `homepage` link, deployment to Vercel is straightforward. You can connect your GitHub repository to Vercel, and it will automatically build and deploy your application on pushes to the main branch.

### Development Setup for Contributors
Ensure you have Node.js and npm installed. Follow the "Quick Start" steps to get the development environment running.

## 🙏 Acknowledgments

-   **React**: For building powerful user interfaces.
-   **Vite**: For an incredibly fast development experience.
-   **Tailwind CSS**: For utility-first CSS styling.
-   **ESLint**: For maintaining code quality.

## 📞 Support & Contact

-   🐛 Issues: [GitHub Issues](https://github.com/siddhantpawbake/BlogWebsite/issues)
-   📧 Email: sidpawbake@gmail.com <!-- TODO: Add contact email -->

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

Made with ❤️ by Siddhant Pawbake

</div>

# Project Title

Brief description of your project.

