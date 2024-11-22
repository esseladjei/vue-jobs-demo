# Vue Jobs Demo

This project is a single-page application built with **Vue**, **Vite**, and **Tailwind CSS**. It includes a mock backend using **JSON Server** to serve data for development purposes. The app is styled with **Tailwind CSS** and follows best practices for a modern frontend development workflow.

## Features

- **Vue + Vite**: A fast development environment with hot module replacement (HMR).
- **Tailwind CSS**: Utility-first CSS for rapid UI development.
- **JSON Server**: A lightweight REST API to simulate a backend.
- **Dockerized**: Easily run the app and mock backend in isolated containers.

---

## Project Structure

- **Frontend**: Built with Vue and Vite, served on `http://localhost:3000`.
- **Mock Backend**: JSON Server serves the `jobs.json` file on `http://localhost:8000`.

---

## Prerequisites

### 1. For Local Setup

- **Node.js** (v18 or later) and npm installed.
- Optionally, install **JSON Server** globally for the backend:

- run local dev database server

```bash
npm run server 
```

- run application

```bash
npm run dev 
```

- optional: To install json-server

  ```bash
  npm install -g json-server

