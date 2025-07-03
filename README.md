# Dummy API for Development and Testing

This repository serves as a simple **Dummy API** for development and testing purposes. It leverages the open-source project [ruanbekker/fake-api](https://github.com/ruanbekker/fake-api), a lightweight REST API that returns mock JSON data.

## 📦 Features

- Plug-and-play fake REST API
- Predefined endpoints with sample data (users, products, etc.)
- Easy to customize with your own `data.json`
- Ideal for frontend development, testing, and prototyping

## 🚀 Getting Started

### 1. Clone the Fake API Base

This repository is based on:  
👉 [`ruanbekker/fake-api`](https://github.com/ruanbekker/fake-api)

If you're using this repository directly, make sure Docker is installed.

```bash
git clone https://github.com/idrissiddiq/dummyAPI.git
cd dummyAPI

### 2. Example Endpoints

Depending on your `db.json`, some example endpoints might be:

- `GET /users`
- `GET /products`
- `GET /orders/1`
- `POST /feedback`

All responses are served from the static `db.json` file.

### 🛠️ Customize Your API

To change the response data, simply edit `db.json`. For example:

{
  "users": [
    { "id": 1, "name": "Alice" },
    { "id": 2, "name": "Bob" }
  ]
}

### 💡 Use Cases

- Frontend development without backend readiness
- Mock integration testing
- API prototyping
- Teaching / tutorials

### 📄 License

This repo uses the [ruanbekker/fake-api](https://github.com/ruanbekker/fake-api) under its original license.  
You are free to modify and use `db.json` for any development or educational purposes.

---

Made with ❤️ for mock data needs.


