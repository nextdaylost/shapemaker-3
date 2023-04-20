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
