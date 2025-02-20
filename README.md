# pycounts_yz110

[![codecov](https://codecov.io/github/JennyonOort/pycounts/graph/badge.svg?token=OM56MXFM74)](https://codecov.io/github/JennyonOort/pycounts)

Calculate word counts in a text file!

Author: Yuci Jenny Zhang

Year: 2025

## Installation

```bash
$ pip install pycounts_yz110
```

## Usage

`pycounts_yz110` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_yz110.pycounts import count_words
from pycounts_yz110.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_yz110` was created by Yuci Jenny Zhang. It is licensed under the terms of the MIT license.

## Credits

`pycounts_yz110` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
