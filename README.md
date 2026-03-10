# E-Commerce App

A simple e-commerce application built with Node.js and Express.

## Features

- RESTful API structure
- Express.js framework
- Docker support

## Installation

```bash
npm install
```

## Usage

### Development
```bash
npm run dev
```

### Production
```bash
npm start
```

## Docker

Build the image:
```bash
docker build -t ecommerce-app .
```

Run the container:
```bash
docker run -p 3000:3000 ecommerce-app
```

## API Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check

## License

ISC
