# DisSModel

**A Python ecosystem for reproducible discrete spatial simulation and land-change modelling.** An independent alternative to INPE's TerraME/LuccME, which remain the reference: every package is checked against their outputs.

```bash
pip install dissmodel
```

📖 **[Documentation](https://dissmodel.github.io/)** · 🗺️ **[Repository map](https://dissmodel.github.io/repository-map.html)** · 📦 [PyPI](https://pypi.org/project/dissmodel/) · 📝 Under review at JOSS · [DOI 10.5281/zenodo.23246106](https://doi.org/10.5281/zenodo.23246106)

> *From open data to a verified model, in code anyone can run.*

---

## Packages

| Package | What it does |
|---|---|
| [**dissmodel**](https://github.com/DisSModel/dissmodel) | Core: models, raster and vector backends, a declarative executor, and experiment records with checksums, specs and Git provenance. |
| [**disscube**](https://github.com/DisSModel/disscube) | Declarative pipelines that turn open geospatial data into model-ready grids. |
| [**disslucc**](https://github.com/DisSModel/disslucc) | Land use and cover change: continuous and discrete allocation. |
| [dissmodel-ca](https://github.com/DisSModel/dissmodel-ca) · [dissmodel-sysdyn](https://github.com/DisSModel/dissmodel-sysdyn) · [dissmodel-abm](https://github.com/DisSModel/dissmodel-abm) | Extensions: cellular automata, system dynamics and agent-based models. |
| [haloexec](https://github.com/DisSModel/haloexec) | Out-of-core execution of cellular automata on rasters larger than memory. |
| [dissmodel-configs](https://github.com/DisSModel/dissmodel-configs) | Registry of external executors (TOML, reviewed by pull request). |

**Case study:** [brmangue-dissmodel](https://github.com/DisSModel/brmangue-dissmodel) (sea-level rise and mangroves) and its [QGIS interface](https://github.com/DisSModel/brmangue-qgis).  
**Experimental:** [dissmodel-platform](https://github.com/DisSModel/dissmodel-platform), a prototype execution platform (JupyterLab, FastAPI, workers, S3-compatible storage).

## How it is checked

The reference outputs of TerraME and LuccME, and the benchmarks that compare each package against them, live in the [LambdaGeo](https://github.com/LambdaGeo) organization: [terrame-goldens](https://github.com/LambdaGeo/terrame-goldens), [luccme-goldens](https://github.com/LambdaGeo/luccme-goldens), [disscube-benchmark](https://github.com/LambdaGeo/disscube-benchmark) and [disslucc-benchmark](https://github.com/LambdaGeo/disslucc-benchmark). The [open-lucc-workflow](https://github.com/LambdaGeo/open-lucc-workflow) shows a complete traceable experiment from open data.

---

Developed by the [LambdaGeo](https://lambdageo.ufma.br) research group at the Federal University of Maranhão (UFMA). Led by [Sérgio Souza Costa](https://lambdageo.ufma.br/people/sergio-costa/).
