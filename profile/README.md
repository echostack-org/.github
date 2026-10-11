# echostack

[![SciPy Proceedings](https://img.shields.io/badge/SciPy_2025-Paper-blue)](https://proceedings.scipy.org/articles/WXRH8633)
[![GitHub Organization](https://img.shields.io/badge/GitHub-echostack--org-black?logo=github)](https://github.com/echostack-org)
[![SPEC 0](https://img.shields.io/badge/SPEC-0-green?labelColor=%23004811&color=%235CA038)](https://scientific-python.org/specs/spec-0000/)

**echostack** is an open-source ecosystem of interoperable Python packages for processing, analyzing, visualizing, and managing scientific echosounder data. The ecosystem provides modular and scalable software components for working with water-column sonar data, from raw instrument files to calibrated, analysis-ready data products and downstream ecological interpretation.

<p align="center">
  <img src="figures/echostack_packages.png" alt="Overview of the Echostack ecosystem" width="950">
</p>

Built on the Scientific Python ecosystem, Echostack leverages libraries such as **xarray**, **Dask**, **Zarr**, **NetCDF**, **fsspec**, and **pandas**, while integrating with community projects including **regionmask**, **HoloViz**, **Prefect**, and **Pydantic**. Echostack is adopting [Scientific Python SPEC 0](https://scientific-python.org/specs/spec-0000/) across its Python packages to follow a consistent policy for minimum supported versions of Python and core dependencies.

The Echostack ecosystem builds upon the development of **echopype**:

> **Lee, W.J., Setiawan, L., Tuguinay, C., Mayorga, E. and Staneva, V. (2024).**
> *Interoperable and scalable echosounder data processing with Echopype.*
> *ICES Journal of Marine Science*, **81**(10), 1941–1951.
> https://doi.org/10.1093/icesjms/fsae133

Echostack is presented in:

> **Lee, W.J., Staneva, V., Setiawan, L., Mayorga, E., Tuguinay, C., Butala, S., Lucca, B. and Lei, D. (2024).**
> *Echostack: A flexible and scalable open-source software suite for echosounder data processing.*
> *Proceedings of the 23rd Python in Science Conference (SciPy 2024).*
> https://doi.org/10.25080/WXRH8633

## Core repositories

| Repository | Description | Activity |
| --- | --- | --- |
| [**echopype**](https://github.com/echostack-org/echopype) | Data conversion, calibration, aggregation, and computation for echosounder data. | ![Stars](https://img.shields.io/github/stars/echostack-org/echopype?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echopype) |
| [**echopype-examples**](https://github.com/echostack-org/echopype-examples) | Example notebooks and tutorials demonstrating the Echostack ecosystem. | ![Stars](https://img.shields.io/github/stars/echostack-org/echopype-examples?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echopype-examples) |
| [**echoregions**](https://github.com/echostack-org/echoregions) | Interfaces echosounder data with annotations, lines, regions, and masks. | ![Stars](https://img.shields.io/github/stars/echostack-org/echoregions?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echoregions) |
| [**echopop**](https://github.com/echostack-org/echopop) | Combines acoustic and biological data for population and biomass estimates. | ![Stars](https://img.shields.io/github/stars/echostack-org/echopop?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echopop) |
| [**echoshader**](https://github.com/echostack-org/echoshader) | Interactive visualization of large echosounder datasets. | ![Stars](https://img.shields.io/github/stars/echostack-org/echoshader?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echoshader) |
| [**echodataflow**](https://github.com/echostack-org/echodataflow) | Workflow orchestration for local and cloud-based echosounder processing pipelines. | ![Stars](https://img.shields.io/github/stars/echostack-org/echodataflow?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echodataflow) |
| [**echodataflow-recipes**](https://github.com/echostack-org/echodataflow-recipes) | Example recipes and configurations for Echodataflow workflows. | ![Stars](https://img.shields.io/github/stars/echostack-org/echodataflow-recipes?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echodataflow-recipes) |
| [**echolevels**](https://github.com/echostack-org/echolevels) | Proposed processing-level specifications for standardized echosounder data products. | ![Stars](https://img.shields.io/github/stars/echostack-org/echolevels?style=social) ![Last commit](https://img.shields.io/github/last-commit/echostack-org/echolevels) |

## Design principles

The Echostack ecosystem is designed to be:

- **Modular**: repositories can be used independently or combined into larger workflows.
- **Interoperable**: built upon the Scientific Python ecosystem and common open data formats.
- **Scalable**: from personal laptops to HPC clusters and cloud platforms.
- **Open**: community-driven, reproducible, and open-source.

## Community

We welcome contributions from researchers, developers, and users of ocean acoustic data.

- For package-specific bugs, feature requests, or documentation improvements, please open an issue or pull request in the relevant repository.
- For cross-repository discussions, shared standards, or organization-wide initiatives, use the **`.github`** repository.
