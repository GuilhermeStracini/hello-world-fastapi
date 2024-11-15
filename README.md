# Hello World FastAPI (Python)

📚 A repository to learn and explore the basics of [FastAPI](https://fastapi.tiangolo.com/), a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.

---

## Overview

This repository serves as an educational resource to:

- Understand the foundational structure of a **FastAPI** application.
- Experiment with creating routes, handling requests, and managing responses.
- Learn how FastAPI leverages Python's type hints for auto-generated documentation and validation.

---

## Features

- **Hello World Application**:
  - Demonstrates the basic setup of a FastAPI project.
  - Includes a simple endpoint to get started.

- **Beginner-Friendly**:
  - Aimed at developers new to FastAPI and modern Python web development.
  - Provides a solid starting point for more advanced FastAPI projects.

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.7 or higher.
- [Pipenv](https://pipenv.pypa.io/en/latest/) or a similar virtual environment tool is recommended.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-fastapi.git
   cd hello-world-fastapi
   ```

2. **Set Up the Environment**:
   - Create a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Application**:
   ```bash
   uvicorn main:app --reload
   ```

4. **Access the API**:
   - Visit `http://127.0.0.1:8000` to see the Hello World response.
   - Explore the interactive API documentation at:
     - [Swagger UI](http://127.0.0.1:8000/docs)
     - [ReDoc](http://127.0.0.1:8000/redoc)

---

## Helpful Links

Here are some additional resources to enhance your understanding of FastAPI and its ecosystem:

- [FastAPI: From App.py to a Modular Architecture](https://towardsdev.com/fastapi-from-app-py-to-a-modular-architecture-54ca9e0044eb)
- [Async Architecture with FastAPI, Celery, and RabbitMQ](https://medium.com/cuddle-ai/async-architecture-with-fastapi-celery-and-rabbitmq-c7d029030377)
- [Building End-to-End Microservices with FastAPI and RabbitMQ: A Comprehensive Guide](https://snimkar1905.medium.com/building-microservices-with-fastapi-and-rabbitmq-part1-1104dbd4ad96)

---

## Contribution

Contributions are welcome!  
Feel free to fork the repository, open issues, or submit pull requests to improve this project or add new features.

---

## License

This project is licensed under the [MIT License](LICENSE).
