# pycounts_lyj

Calculate word counts in a text file!

## Installation

The package is only pushed to testpypl, install using command
```bash
pip install --index-url https://test.pypi.org/simple/ \
  --extra-index-url https://pypi.org/simple \
  pycounts_lyj
```

## Usage

`pycounts_lyj` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_lyj.pycounts_lyj import count_words
from pycounts_lyj.plotting_lyj import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```
## Documents:

Doc is live in ReadTheDocs page. [link](https://pycounts-lyj.readthedocs.io/en/stable/).

## Contributing

Interested in contributing? Check out the contributing guidelines. 
Please note that this project is released with a Code of Conduct. 
By contributing to this project, you agree to abide by its terms.

## License

`pycounts_lyj` was created by Yajing Liu. It is licensed under the terms
of the MIT license.

## Credits

`pycounts_lyj` was created with 
[`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and 
the `py-pkgs-cookiecutter` 
[template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
