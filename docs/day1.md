# Day 1 - Getting Started with ReactJS

## I. Introduction

🚀 Welcome to the first day of our ReactJS learning journey!
😄 Today, we will cover the basics of ReactJS, including what it is, why it's popular, and how to set up your development environment.

## II. What is ReactJS?

📚 ReactJS is a JavaScript library for building user interfaces. It was developed by Facebook and is widely used for creating dynamic and interactive web applications. React allows developers to build reusable UI components, making it easier to manage and maintain complex applications.

## III. Why Choose ReactJS?

⚛️ ReactJS has become the go-to choice for many developers due to its unique features and advantages:

- **Component-Based**: Build reusable, maintainable UI components modularly
- **Virtual DOM**: Optimized rendering—updates only changed DOM parts efficiently
- **One-Way Data Flow**: Predictable data flow simplifies debugging and state management
- **Strong Community**: Extensive resources, libraries, and tools for development
- **Cross-Platform**: React Native allows for mobile app development using the same React principles

## IV. Setting Up Your Development Environment

🛠️ To get started with ReactJS, you need to set up your development environment. Here’s how you can do it:

1. **Install Node.js**: ReactJS requires Node.js to run. You can download it from [Node.js official website](https://nodejs.org/).
2. **Install a Code Editor**: A good code editor like Visual Studio Code will help you write and manage your code efficiently.
3. **Create a React App**: Previously, `create-react-app` was the popular way to get started with ReactJS. However, since `create-react-app` is now deprecated, Vite is a recommended alternative for newbies to set up a React project quickly. You can create a new React app using Vite with the following command:
   ```bash
   npm create vite@latest
   ```
   🎯 Follow the prompts to enter your project name, package name, and framework (Select **_React_**).
   📘 In this series, we will be using TypeScript, so make sure to select **_TypeScript + React Compiler_** when prompted.
   ❌ Then, select **_No_** for **_Use rolldown-vite?_**
   ✅ Next, select **_Yes_** for **_Install with npm and start now?_**
   📦 Now, Vite will set up your React project with TypeScript and install all the necessary dependencies for you.
4. **Start the Development Server**: Once your project is set up, navigate to your project directory and start the development server:
   ```bash
    cd your-project-name
    npm run dev
   ```
   This will start the development server, and you can view your React app in the browser at `http://localhost:5173`.

🎉 Phew! You have successfully set up your ReactJS development environment.
🚀 In the next session, we will dive into the core concepts of ReactJS and start building our first React component.
💪 Stay tuned! ✨
