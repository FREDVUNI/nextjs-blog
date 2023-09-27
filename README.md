# Next.js Blog with Dark/Light Theme

A simple Next.js blog with dark and light theme options, powered by Prisma for MongoDB database access.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
  - [Running Locally](#running-locally)
  - [Themes](#themes)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (running as a service or locally)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/FREDVUNI/nextjs-blog.git
   cd nextjs-blog
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure Prisma: Rename `.env.example` to `.env` and update the MongoDB connection string.

4. Generate Prisma Client:

   ```bash
   npx prisma generate
   ```

## Project Structure

- `pages/`: Next.js pages for routing.
- `components/`: Reusable React components.
- `styles/`: CSS styles and theme-specific styles.
- `api/`: API routes for CRUD operations.
- `prisma/`: Prisma schema and configuration.

## Usage

### Running Locally

To run the blog locally, use the following command:

```bash
npm run dev
```

The blog will be available at `http://localhost:3000`.

### Themes

This blog supports both dark and light themes. Users can switch between themes by clicking a theme switcher button. Styles and themes can be customized in the `styles/` directory.

## API Routes

API routes in the `api/` directory handle CRUD operations for blog posts. You can customize and extend these routes as needed.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the `main` branch of this repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
```
