# Processing DrugCentral data

This repository processes the [DrugCentral](http://datascience.unm.edu/drugdb/ "DrugCentral database at UNM") data available at [`olegursu/drugtarget`](https://github.com/olegursu/drugtarget). Identifiers are converted to the vocabularies used in [rephetio](http://doi.org/10.15363/thinklab.4), our drug repurposing network.

# Execution

[`drugcentral.ipynb`](drugcentral.ipynb) performs the analysis. Data is read from `drugtarget` (submodule containing `olegursu/drugtarget`), processed, and then saved to [`rephetio`](rephetio).

## License

All original content is licensed as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). DrugCentral data is used with permission. Please contact DrugCentral for reuse of their data or any derivatives.
