# Waseet - Fintech Platform

Waseet is a comprehensive fintech project designed to streamline payment processing and banking integrations. It consists of multiple parts to cater to different user needs:

- **Waseet Pay**: A payment processor for merchants and businesses.
- **Waseet Link**: A platform that links users from different banks for seamless money exchange.

This project is structured as a monorepo, containing the following apps and packages:

## Monorepo Structure

### Apps and Packages

- `api`: A RESTful API supporting multiple projects with real-time updates and Server-Sent Events (SSE).
- `web`: A [Next.js](https://nextjs.org/) application that includes a landing page and dashboard for the payment processor.
- `link`: A platform enabling users to exchange money between banks seamlessly.
- `sdk`: A lightweight JavaScript/TypeScript SDK for integrating Waseet Pay into business systems.
- `docs`: Comprehensive documentation for all Waseet apps and packages.
- `blog`: A blog platform for updates, how-to guides, and tutorials.

Each package/app is built with [TypeScript](https://www.typescriptlang.org/) for consistency, type safety, and maintainability.

## Utilities

This project comes pre-configured with:

- [TypeScript](https://www.typescriptlang.org/) for static type checking.
- [ESLint](https://eslint.org/) for code linting.
- [Prettier](https://prettier.io) for code formatting.

## Build

To build all apps and packages, run the following command:

```sh
pnpm build
```

## Develop

To develop all apps and packages, run the following command:

```sh
pnpm dev
```

This command starts the development servers for all applications, enabling seamless development across the monorepo.

## Features

- **Waseet Pay**: A robust payment processor for merchants and businesses.
- **Waseet Link**: A platform connecting users across different banks for money exchange.
- **SDK**: Simplifies integration for businesses.
- **Documentation**: Guides and resources for all applications.
- **Blog**: Updates, tutorials, and how-to guides.
- **High Performance**: Built using Turborepo for optimized development and deployment.

## Useful Links

Learn more about the tools and concepts used in Waseet:

- [Turborepo](https://turbo.build/repo/docs)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

---

For questions or support, feel free to reach out!
