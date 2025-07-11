# NodeMantra

An Introduction to NodeMantra (Part I) offers a comprehensive overview of the NodeMantra framework, highlighting its powerful features.

NodeMantra is a powerful and versatile framework designed for building robust web applications using Node.js and TypeScript. It provides a solid foundation and a collection of essential tools and features to streamline the development process and enhance code quality.

One of the standout features of NodeMantra is its seamless integration with TypeScript. TypeScript brings static typing and advanced language features to Node.js, enabling developers to write cleaner and more maintainable code. By leveraging TypeScript's type checking capabilities, NodeMantra helps catch errors early in the development process and provides enhanced code navigation and refactoring support.

NodeMantra follows a modular and component-based architecture, allowing developers to organize their code into reusable and independent modules. This promotes code reusability, scalability, and maintainability. The framework provides a well-defined structure and guidelines for organizing files and folders, making it easy to navigate and understand the project's codebase.

With NodeMantra, developers can easily handle HTTP requests and responses using the built-in routing system. The framework provides a flexible and intuitive routing mechanism that enables the creation of RESTful APIs and handling of various HTTP methods, such as GET, POST, PUT, and DELETE.

In addition, NodeMantra offers a robust middleware system. Middlewares allow developers to add custom logic to the request-response cycle, such as authentication, logging, error handling, and more. The framework comes with several pre-built middleware functions and allows developers to create their own, providing a high degree of customization and control over the application's behavior.

NodeMantra integrates well with databases and offers support for popular database systems like MongoDB, MySQL, and PostgreSQL. It provides an ORM (Object-Relational Mapping) layer that simplifies database interactions and helps developers manage database models, relationships, and queries efficiently.

To enhance productivity, NodeMantra comes bundled with a range of useful utilities and features, such as logging, validation, caching, task scheduling, and more. These utilities eliminate the need for developers to reinvent the wheel and enable them to focus on building core application logic.

NodeMantra not only offers a comprehensive framework for web applications but also includes Meilisearch as its built-in search engine, enabling efficient and accurate search functionality.

## Quick Start

### Create a New Project

The easiest way to create a new NodeMantra project is using our CLI tool:

```bash
npx create-nodemantra my-app
cd my-app
npm install
npm run dev
```

### Manual Installation

```bash
npm install nodemantra-core
```

```typescript
import NodeMantra from 'nodemantra-core';

const app = new NodeMantra(3000, 'localhost');
app.initialize().then(() => {
  app.start();
});
```

### Using Artisan Commands

NodeMantra includes a powerful command-line interface inspired by Laravel's Artisan:

```bash
# List all available commands
npm run artisan list

# Create a complete resource (controller, model, service, validator, route)
npm run artisan make:resource User

# Create individual components
npm run artisan make:controller Post
npm run artisan make:model Category
npm run artisan make:middleware Auth

# Database operations
npm run artisan db:migrate
npm run artisan db:seed

# Start development server
npm run artisan serve
```

For a complete list of commands, see the [Artisan Commands documentation](ARTISAN.md).

## Documentation

- 📖 [Complete Usage Guide](USAGE.md) - Detailed guide with examples
- 🛠️ [Artisan Commands](ARTISAN.md) - Command-line interface documentation
- 🚀 [NPM Package](https://www.npmjs.com/package/nodemantra-core)
- 📚 [GitHub Repository](https://github.com/developerprakashjoshi/nodemantra-core)

## Features

- ✅ **TypeScript Support** - Built with TypeScript for type safety
- ✅ **Modular Architecture** - MVC pattern with controllers, services, and models
- ✅ **Database Integration** - TypeORM support for multiple databases
- ✅ **Middleware System** - Built-in and custom middleware support
- ✅ **Error Handling** - Centralized error management
- ✅ **File Upload** - Built-in file upload middleware
- ✅ **Search Integration** - MeiliSearch integration
- ✅ **CLI Tool** - Quick project scaffolding
- ✅ **Artisan Commands** - Laravel-inspired command-line interface

Overall, NodeMantra is a feature-rich and developer-friendly framework that combines the power of Node.js with the benefits of TypeScript. It empowers developers to build scalable, maintainable, and high-performance web applications with ease. Whether you're building a small REST API or a complex web application, NodeMantra provides the tools and structure needed to deliver reliable and efficient solutions.# Updated Git configuration
