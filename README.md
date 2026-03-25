# KDMiLe Prediction


## Paper

> This repository is based on our paper:  
**Prediction of Infant Mortality in Brazil using Machine Learning and Entity Matching on Brazilian Unified Health System's Data**  
Authors: Morsoleto, R. et al.  
Presented and accepted at: [KDMiLe](https://sbbd.org.br/2025/kdmile/?lang=pt) 2025.


## Installation & Usage

> [!IMPORTANT]
> The input files weren't included in this repository due to their size. Both can be acquired from [etlSUS](https://github.com/GOPAD-Datasus/etlSUS) and be manually loaded on to the data/input folder.

Poetry was used for dependency management. To download it, visit: [python-poetry.org](python-poetry.org).

Activate a virtual environment and execute:

```bash
poetry install
# Or
pip install .
```

```bash
python main.py
```

## License
[LGNU](LICENSE) | © GOPAD 2025
