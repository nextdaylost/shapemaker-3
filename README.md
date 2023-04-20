# ShapeMaker

Geospatial vector geometry storage and retrieval

## Development

### Prerequisites

- Python 3.10
- [Poetry](https://python-poetry.org/docs/)

### Setup

Install the project in edit mode:

```shell
poetry install --with dev
```

Activate a project shell:

```shell
poetry shell
```

Install Git hooks:

```shell
pre-commit install
```

### Testing

Run the test suite:

```shell
pytest
```

Check code coverage:

```shell
pytest --cov
```

Generate a browsable coverage report:

```shell
pytest --cov --cov-report html
```

### Linting

Run the linter:

```shell
flake8
```

> Code formatting errors can usually be fixed by running `black`:
>
> ```shell
> black src/
> ```
