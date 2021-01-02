# Search functions
## Python implementations of common list-search algorithms

### Algorithms implemented
* **Unsorted lists:**
  * Linear search
* **Sorted lists:**
  * Binary search
  * Jump search
  * Exponential search
* **Uniformly-distributed sorted lists:**
  * Interpolation search
  
### Repository structure
* **search_functions**: Search algorithm implementation files
  * *search_functions.py*: Search algorithm implementation code
* **tests**: Test files
  * *test_search_functions.py*: Unittests for search_functions.py
* **tools**: Files to assist with algorithm analysis and use
  * *check_array_format.py*: Functions for testing whether an object can be searched
  * *compare_runtimes.py*: Script comparing algorithm runtime over various length lists

### Setup & Requirements
* Have Python 3.8.2+ installed, as well as pip
* Clone the repository using `git clone https://github.com/WoolleySheep/search-functions.git`
* To use just the search functions, no additional modules need to be installed
* To use the tools, install the relevant packages using `pip install -r requirements.txt`
* To run tests and utilise code styling, install the relevant packages using `pip install -r requirements-dev.txt`
