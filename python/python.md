# read text file as string
```python
with open("filepath") as file:
    data_as_list_of_str = file.readlines()
    data_as_one_str = file.read()
```

# Install and run pre-commit hooks
https://pre-commit.com/
```
$ pip install pre-commit
$ pre-commit install
$ pre-commit run --all-files
```