# MSADv2: Extending Model Selection for Anomaly Detection in Time Series with Weighted Averages

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

MSADv2 is a research-focused repository dedicated to improving model selection strategies for anomaly detection in time series data. By introducing and experimenting with weighted average approaches, MSADv2 aims to enhance the robustness and accuracy of anomaly detection, especially in real-world, noisy, and diverse temporal datasets.

**This repository extends [`boniolp/MSAD`](https://github.com/boniolp/MSAD), which accompanies the following paper:**

- [Choose wisely: An extensive evaluation of model selection for anomaly detection in time series](https://dl.acm.org/doi/abs/10.14778/3611479.3611536?casa_token=slg1fJWKqEUAAAAA%3Ag2i7WClNjs8utE5hsFagD8Nh4kGB3Fu3mE3ms1psY8PQE78MO38TPgOus-60cvlaYLjHhmgXK4yUSg)  
   _Proceedings of the VLDB Endowment_, 2023
  ```
  @article{sylligardos2023choose,
    title={Choose wisely: An extensive evaluation of model selection for anomaly detection in time series},
    author={Sylligardos, Emmanouil and Boniol, Paul and Paparrizos, John and Trahanias, Panos and Palpanas, Themis},
    journal={Proceedings of the VLDB Endowment},
    volume={16},
    number={11},
    pages={3418--3432},
    year={2023},
    publisher={VLDB Endowment}
  }
  ```
  **MSADv2 pushes further with weighted averaging techniques and new comparative experiments.**

This work also extends ideas introduced in ["MSAD: A deep dive into model selection for time series anomaly detection"](https://arxiv.org/pdf/2510.26643), published in _The VLDB Journal_ (2025).

## Authors

- **Emmanouil Sylligardos**
- **John Paparrizos**
- **Themis Palpanas**
- **Pierre Senellart**
- **Paul Boniol**

## Key Features

- **Weighted Model Selection:** Implements advanced strategies for selecting the best anomaly detection models using weighted averages.
- **Comparative Experiments:** Facilitates comparison between weighted average selection and traditional model selection methods.
- **Jupyter Notebooks:** Interactive notebooks allow for easy experimentation, visualization, and reproducibility of results.
- **Time Series Focus:** Algorithms and utilities are tailored for time series anomaly detection across various domains.
- **Extensible Framework:** Designed to be easily extended for additional models, datasets, and evaluation metrics.

## Repository Structure

- `notebooks/` — Main Jupyter Notebooks for experiments, analysis, and visualization.
- `src/` — Source code implementing model selection, anomaly detection logic, and supporting utilities.
- `data/` — Example datasets (or scripts to download datasets) for experiments.
- `docs/` — Documentation and TeX files for academic writing, reports, or papers.
- `results/` — Saved experiment outputs and metrics.

## Installation

MSADv2 relies primarily on Python and Jupyter Notebook. To get started:

```bash
git clone https://github.com/sylligardos/MSADv2.git
cd MSADv2
pip install -r requirements.txt
```

> **Note:** Ensure you have [Jupyter Notebook](https://jupyter.org/install) installed (`pip install notebook`). For time series analysis, the repository may use libraries such as `numpy`, `pandas`, `scikit-learn`, and visualization tools.

## Usage

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
2. **Open a Notebook:**
   Navigate to the `notebooks/` directory and open any available notebook to run experiments or visualize results.

3. **Experiment with Weighted Model Selection:**
   Follow the instructions in the notebooks to explore different anomaly detection models and use weighted selection strategies.

## Paper and Citation

This repository accompanies the following publication:

- [MSAD: A deep dive into model selection for time series anomaly detection](https://arxiv.org/pdf/2510.26643)  
  _The VLDB Journal_, 2025

If you use MSADv2 for academic work, please cite the paper:

```
@article{sylligardos2025msad,
  title={MSAD: A deep dive into model selection for time series anomaly detection},
  author={Sylligardos, Emmanouil and Paparrizos, John and Palpanas, Themis and Senellart, Pierre and Boniol, Paul},
  journal={The VLDB Journal},
  volume={34},
  number={6},
  pages={1--25},
  year={2025},
  publisher={Springer}
}
```

## Contributing

Contributions of new models, notebooks, or improvements to the weighted averaging methodology are welcome!

- Fork the repository
- Create your feature branch (`git checkout -b feature/MyFeature`)
- Commit your changes
- Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Supports and builds on prior work in anomaly detection, time series analysis, and model selection. Special thanks to the open-source community for providing foundational libraries and resources.

---
