# API Tester

A browser-based RESTful API testing tool built with React — a lightweight alternative to Postman that runs directly in the browser.

## Features

- Send **GET, POST, PUT, DELETE, PATCH** requests to any endpoint
- Set custom **headers** and **request body**
- View formatted **JSON responses** with status codes
- **React Context** for global state management across components
- **Higher-Order Components (HOCs)** for reusable request logic
- **Axios** for HTTP communication

## Tech Stack

| Layer | Technology |
|---|---|
| UI | React 16, Reactstrap |
| State | React Context API |
| HTTP | Axios |
| Patterns | HOCs (Higher-Order Components) |
| Build | Create React App, Service Worker |

## Getting Started

```bash
# Install dependencies
npm install

# Run in development mode
npm start

# Build for production
npm run build
```

## Usage

1. Enter the target API URL
2. Select the HTTP method
3. Add headers or a request body if needed
4. Hit **Send** and inspect the response
