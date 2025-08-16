# Notebook rendeding and testing: short intro to the JupyterBook ecosystem

This is a very brief summary of the tools that I showed and mentioned during this session.

## MyST Markdown flavoured notebooks.

You will need `jupytext` as a dependency to make them work in Jupyter Lab; and `jupyterlab-myst` extension is also advised.
Both of them are easy to install Python dependencies.

## MySTmd and Jupyter Book:

    new version is MySTmd/TypeScript based; beta 2.0 came out relatively recently, and more features to come:
    https://mystmd.org/ and https://next.jupyterbook.org/

## Executable-tutorials

Repo and website as a config template. It's note ready yet for prime time, but we're actively working on it and you may already find useful bits and pieces: https://github.com/scientific-python/executable-tutorials and https://scientific-python.github.io/executable-tutorials/

## Example repos

Slides I showed:

    https://docs.google.com/presentation/d/1j6osl2_MVd_XzsXG6AvXDAJeE18lOtGSPo55k1hFC0A/edit?usp=sharing

Example repos that have testing and website rendering set up:

    https://github.com/Caltech-IPAC/irsa-tutorials/
    https://github.com/numpy/numpy-tutorials

And docs only repos, using the same jupyter book infrastructure (well, these are already using JupyerBook 2 as opposed to the notebook repos that we have not yet refactored)

    https://github.com/bsipocz/URSSI_2025Aug_first_PR
    or etc: https://nasa-fornax.github.io/fornax-documentation/
