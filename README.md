# Project: Data Modeling with Cassandra

## Build

Pre-requisites:

- Python 3
- poetry
- pyenv (optional)
- Cassandra Database

To install project python dependencies, you should run:

``` sh
poetry install
```

## Database

The database can be installed locally or ran using Docker, which is the
preferred method.

To use docker to run Cassandra, you should run:

``` sh
docker run -d --network host --name cassandra -e CASSANDRA_LISTEN_ADDRESS=127.0.0.1 cassandra:latest
```

## Running

To run the project locally, use poetry to activate the virtual environment:

``` sh
poetry shell
```

And run the etl jupyter notebook with:

``` sh
jupyter notebook
```
