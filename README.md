# gpu_spatial_graph_pipeline

[![Tests][badge-tests]][link-tests]
[![Documentation][badge-docs]][link-docs]

[badge-tests]: https://img.shields.io/github/actions/workflow/status/tothmarcella/gpu_spatial_graph_pipeline/test.yaml?branch=main
[link-tests]: https://github.com/theislab/gpu_spatial_graph_pipeline/actions/workflows/test.yml
[badge-docs]: https://img.shields.io/readthedocs/gpu_spatial_graph_pipeline

The repo provides a set of tools for creating PyTorch Geometric (PyG) data objects from AnnData objects, which are commonly used for storing and manipulating single-cell genomics data. In addition, the repo includes functionality for creating PyTorch Lightning (PyTorch-Lightning) DataModule objects from the PyG data objects, which can be used to create graph neural network (GNN) data pipelines. The PyG data objects represent graphs, where the nodes represent cells and the edges represent relationships between the cells, and can be used to perform GNN tasks such as node classification, graph classification, and link prediction. The repo is written in Python and utilizes the PyTorch, PyTorch Geometric, and PyTorch-Lightning libraries.

## Getting started

Please refer to the [documentation][link-docs]. In particular, the

-   [API documentation][link-api].

## Installation

You need to have Python 3.8 or newer installed on your system. If you don't have
Python installed, we recommend installing [Mambaforge](https://github.com/conda-forge/miniforge#mambaforge).

There are several alternative options to install gpu_spatial_graph_pipeline:

<!--
1) Install the latest release of `gpu_spatial_graph_pipeline` from `PyPI <https://pypi.org/project/gpu_spatial_graph_pipeline/>`_:

```bash
pip install gpu_spatial_graph_pipeline
```
-->

1. Install the latest development version:

```bash
pip install git+https://github.com/tothmarcella/gpu_spatial_graph_pipeline.git@main
```

## Release notes

See the [changelog][changelog].

## Contact

For questions and help requests, you can reach out in the [scverse discourse][scverse-discourse].
If you found a bug, please use the [issue tracker][issue-tracker].


## Credits

Some of the data for `DatasetHartmann` is distributed in this package.
It was originally retrieved from: https://zenodo.org/record/3951613#.Y9flQS-B1qv

This project was generated from [@cjolowicz]'s [Hypermodern Python Cookiecutter] template.

[@cjolowicz]: https://github.com/cjolowicz
[pypi]: https://pypi.org/
[hypermodern python cookiecutter]: https://github.com/cjolowicz/cookiecutter-hypermodern-python
[file an issue]: https://github.com/syelman/gpu_spatial_graph_pipeline/issues
[pip]: https://pip.pypa.io/

## Citation

> t.b.a

[scverse-discourse]: https://discourse.scverse.org/
[issue-tracker]: https://github.com/tothmarcella/gpu_spatial_graph_pipeline/issues
[changelog]: https://gpu_spatial_graph_pipeline.readthedocs.io/latest/changelog.html
[link-docs]: https://gpu_spatial_graph_pipeline.readthedocs.io
[link-api]: https://gpu_spatial_graph_pipeline.readthedocs.io/latest/api.html
