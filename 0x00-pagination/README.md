# 0x00. Pagination

## Description
This project focuses on implementing pagination for datasets in Python. The tasks involve creating helper functions and classes to handle pagination, ensuring the correct subset of data is returned based on the provided pagination parameters.

## Learning Objectives
By the end of this project, you should be able to explain:
- How to paginate a dataset with simple page and page_size parameters.
- How to paginate a dataset with hypermedia metadata.
- How to paginate in a deletion-resilient manner.

## Requirements
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Python 3 (version 3.7).
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/env python3`.
- A README.md file, at the root of the folder of the project, is mandatory.
- Your code should use the pycodestyle style (version 2.5.*).
- The length of your files will be tested using `wc`.
- All modules should have a documentation.
- All functions should have a documentation.
- All functions and coroutines must be type-annotated.

## Setup
Use the provided `Popular_Baby_Names.csv` data file for your project.

## Tasks

### 0. Simple helper function
Create a function named `index_range` that takes two integer arguments `page` and `page_size`.

**File:** `0-simple_helper_function.py`

#### Example:
```python
index_range = __import__('0-simple_helper_function').index_range

res = index_range(1, 7)
print(type(res))
print(res)

res = index_range(page=3, page_size=15)
print(type(res))
print(res)

