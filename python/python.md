# read text file as string
```python
with open("filepath") as file:
    data_as_list_of_str = file.readlines()
    data_as_one_str = file.read()
