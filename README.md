# Processing DrugCentral data

This repository processes the [DrugCentral](http://datascience.unm.edu/drugdb/ "DrugCentral database at UNM") data available at [`olegursu/drugtarget`](https://github.com/olegursu/drugtarget). Identifiers are converted to the vocabularies used in [rephetio](http://doi.org/10.15363/thinklab.4), our drug repurposing network.

# Execution

[`drugcentral-to-rephetio.ipynb`](drugcentral-to-rephetio.ipynb) processes DrugCentral datasets for inclusion into rephetio. Data is read from `drugtarget` (submodule linked to `olegursu/drugtarget`), processed, and then saved to [`rephetio`](rephetio).

## License

All original content is licensed as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). DrugCentral data is [released as CC BY 4.0](https://github.com/olegursu/drugtarget/blob/master/LICENSE). Reuse of any DrugCentral data or derivatives hosted in this repository requires attributing DrugCentral.
