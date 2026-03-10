# Cloud-Native E-Commerce CI/CD Pipeline with AWS ECS Fargate

A cloud-native e-commerce application built with Node.js and Express, deployed using AWS ECS Fargate with CI/CD pipeline.

## Features

- RESTful API structure
- Express.js framework
- Docker support
- AWS ECS Fargate deployment
- CI/CD Pipeline integration

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
