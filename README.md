### Overview

This workflow uses `jupyter nbconvert` to convert Jupyter Notebook (`.ipynb`) files into Hugo-compatible Markdown (`.md`) files.

The `process_latex.py` script wraps LaTeX code in Hugo's `{{< rawhtml >}}` and `{{< /rawhtml >}}` tags to address [this issue](https://github.com/gohugoio/hugo/issues/10894).
