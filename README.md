# zakupek-front

An AI-powered web application designed to streamline the creation of shopping lists. By analyzing user registration data, shopping history, and seasonal product availability, zakupek-front generates tailored shopping lists that save time and improve shopping efficiency.

> **Note:** This repository contains only the frontend part of the Zakupek application. For the backend services, please refer to the [zakupek-api](https://github.com/ddnowicki/zakupek-api) repository.

## Table of Contents

- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Tech Stack

- **Frontend:**
    - **Angular 19:** A comprehensive framework with a robust ecosystem for building reactive and highly interactive UIs.
    - **TypeScript 5:** Provides static typing, improving code quality and development speed.
    - **Tailwind CSS 4:** Utility-first CSS framework for rapid UI design and responsive layouts.
- **Backend:**
    - A .NET-based REST API that provides backend services via RESTful endpoints.
- **AI Integration:**
    - **Openrouter.ai:** Provides unified access to multiple AI models for generating shopping list recommendations.
- **CI/CD & Hosting:**
    - **GitHub Actions:** Automates testing and deployment.
    - **Self-hosted server:** Offers full control over infrastructure.

## Getting Started Locally

1. **Clone the Repository:**

    ```shell
    git clone https://github.com/ddnowicki/zakupek-front.git
    cd zakupek-front
    ```

2. **Install Node Dependencies:**
   Ensure you have Node.js version specified in the `.nvmrc` file **v22.14.0**.

    ```shell
    nvm use
    npm install
    ```

3. **Run the Application:**
   Start the Angular development server:
    ```shell
    npm start
    ```
    The application will be available at [http://localhost:4200](http://localhost:4200).

## Available Scripts

- **ng:** Alias to run Angular CLI commands.
- **start:** Runs `ng serve` to start the development server.
- **build:** Builds the Angular application for production.
- **watch:** Builds the application in watch mode for development.
- **test:** Executes unit tests using Angular’s testing framework.
- **lint:** Runs ESLint to analyze code style and quality.
- **format:** Formats code using Prettier.
- **prepare:** Installs Husky hooks for pre-commit checks.

## Project Scope

- **Functionalities Included in MVP:**

    - User registration and login with demographic and dietary preferences.
    - AI-driven generation of shopping lists based on historical data, seasonal products, and user profile.
    - Manual creation, editing, and deletion of shopping list items.
    - Automatic categorization of items (e.g., beverages, bakery, dairy).
    - Search functionality for products during list editing.
    - Viewing past shopping lists in a user history section.
    - Notifications regarding the seasonality of products.

- **Out-of-Scope for MVP:**
    - Multi-store list segmentation.
    - Receipt or advanced report validations.
    - Mobile version support.
    - Brand-specific product recommendations.
    - Advanced filtering and reporting capabilities.

## Project Status

The project is currently in the **MVP** stage and under active development.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
