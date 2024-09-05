### Overview

This workflow uses `jupyter nbconvert` to convert Jupyter Notebook (`.ipynb`) files into Hugo-compatible Markdown (`.md`) files.

The `process_file.py` script wraps LaTeX code in `{{< rawhtml >}}` and `{{< /rawhtml >}}` tags to address [this issue](https://github.com/gohugoio/hugo/issues/10894). Additionally, it removes initial headings to maintain consistency with the Hugo post format.
