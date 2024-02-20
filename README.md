# React + Vite

This project is an AI summarizer application built using OpenAI's API, React, Vite, and Tailwind CSS. The template provides a minimal setup to get React working in Vite with Hot Module Replacement (HMR) and includes some ESLint rules for code quality.

## Features
- Summarize text using OpenAI's powerful language model.
- Utilizes React for building the user interface.
- Vite for fast and efficient development with HMR support.
- Tailwind CSS for styling the application.

## Getting Started

To get started with this project, follow these steps:

### 1. Clone this repository to your local machine:

 Open your terminal and run the following command:

```bash
  https://github.com/abhishekmanhar/Cogito-AI-Summarizer.git
```

### 2. Install the required dependencies:
Run the following command to install all the required dependencies:
```bash
  npm install
```
### 3. Get your OpenAI API key and set it as an environment variable. You can obtain the API key by signing up on the OpenAI website.

### 4. Create a .env file in the root of your project and add your API key:


```bash
  VITE_RAPID_API_ARTICLE_KEY=
```

### 5. Start the development server:

```bash
  npm run dev
```

Open your browser and visit http://localhost:5173 to view the application.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
