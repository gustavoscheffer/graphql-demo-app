# GraphQL Demo Application

A production-ready GraphQL API demonstration built with Node.js, Express, and MySQL.

## Overview

This project showcases a modern GraphQL implementation with a robust backend architecture. It serves as a reference implementation for building scalable GraphQL APIs using industry-standard technologies.

## Features

- **GraphQL API**: Full-featured GraphQL endpoint for efficient data querying
- **RESTful Integration**: RESTful endpoints for legacy system compatibility
- **Database**: MySQL backend with query optimization
- **Query Builder**: Knex.js for intuitive and safe database operations
- **Express Server**: Lightweight and flexible HTTP server framework

## Technology Stack

| Technology | Purpose |
|-----------|---------|
| **Node.js** | JavaScript runtime environment |
| **Express** | Web application framework |
| **GraphQL** | Query language and API runtime |
| **MySQL** | Relational database |
| **Knex.js** | Database query builder and migration tool |

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MySQL (v5.7 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/gustavoscheffer/graphql-demo-app.git

# Navigate to project directory
cd graphql-demo-app

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
```

### Configuration

Update your `.env` file with the following variables:

```env
NODE_ENV=development
DB_HOST=localhost
DB_PORT=3306
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=your_database
SERVER_PORT=4000
```

### Running the Application

```bash
# Development mode
npm run dev

# Production mode
npm start
```

The GraphQL API will be available at `http://localhost:4000/graphql`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api` | Main API entry point |
| POST | `/graphql` | GraphQL query endpoint |

## Project Structure

```
graphql-demo-app/
├── src/
│   ├── resolvers/
│   ├── schema/
│   ├── database/
│   └── server.js
├── config/
├── migrations/
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Author

**Gustavo Scheffer**
- GitHub: [@gustavoscheffer](https://github.com/gustavoscheffer)

---

*For questions or support, please open an issue on the repository.*
