# pytest-exemplar

pytest examples

## activate virtual env
```sh
source venv/bin/activate
```

## How to run infrastructure tests:

```sh
pytest ./
```

[test_local_infra_example.py](test_local_infra_example.py)

[test_dockerinfra.py](test_dockerinfra.py)


## How to run unit tests:

```sh
pytest lib/*
```

[lib/example_unit_test_same_file.py](lib/example_unit_test_same_file.py)

[lib/example_test_with_api_response_fixture.py](lib/example_test_with_api_response_fixture.py)

