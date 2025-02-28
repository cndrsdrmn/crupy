# Crupy - A FastAPI Skeleton RESTful API

**Crupy** is a simple and scalable FastAPI-based RESTful API. This skeleton provides a structured foundation for building production-ready APIs with FastAPI, SQLAlchemy, and Alembic.

## Features

- [FastAPI](https://fastapi.tiangolo.com/) for building high-performance APIs
- [SQLAlchemy](https://www.sqlalchemy.org/) for database ORM
- [Alembic](https://alembic.sqlalchemy.org/en/latest/) for database migrations
- [Uvicorn](https://www.uvicorn.org/) for ASGI server
- [Pre-commit](https://pre-commit.com/) hooks with pytest and ruff for linting & testing
- [Docker](https://www.docker.com/) support for easy deployment
- [UV](https://docs.astral.sh/uv/) for Python package and project manager

## Prerequisites

- **Python >= 3.13**
- **UV**
- **Docker** (Optional for containerization)
- **SQLite / PostgreSQL / MySQL** (Default: SQLite)

<!-- TODO:
## Directory Structure
-->

## Development Guidelines

> [!IMPORTANT]
> Before you start the development, you'll need to ensure you have already installed the required [Prerequisites](#prerequisites) on your local machine.

#### Fork the Repository:

Click the `Fork` button at the top right of the repository page to create your fork.

#### Clone the Repository:

```shell
git clone https://github.com/yourusername/crupy.git
cd crupy
```

#### Create a New Branch:

```shell
git checkout -b feature/branch-name
```

#### Synchronize an environment with [UV](https://docs.astral.sh/uv/reference/cli/#uv-pip-sync) package manager:

```shell
uv sync
#or
uv pip sync
```

<!-- TODO:
#### Running the Application:

##### Run locally using [Uvicorn](https://www.uvicorn.org/):

```shell
uvicorn app.main:app --reload
```

##### Run as container using [Docker](https://www.docker.com/):

```shell
docker compose up --build
```

#### Running Tests:

```shell
pytest
```
-->

#### Run [pre-commit](https://pre-commit.com/#3-install-the-git-hook-scripts) to set up the git hooks script:

```shell
pre-commit install
```

#### Make Changes & Commit:

> [!IMPORTANT]
> Ensure your changes follow project conventions, add necessary test and documentation.
> Follow the [semantic](https://www.conventionalcommits.org/en/v1.0.0/) commit message.

```shell
git add .
git commit -m "type: summary in present tense."
```

## API Documentation

After running the application, access the API docs at:
- **Swagger UI**: [http://localhost:8000/docs](http://localhost:8000/docs)
- **Redoc**: [http://localhost:8000/redoc](http://localhost:8000/redoc)

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
