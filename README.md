# houses_prices

This project aims to predict houses prices using machine learning techniques. It includes implementations in both Python and R.

## Project structure

```

houses_prices/
├──── .gitignore
├──── LICENSE
├──── README.md
└──── PYTHON/
       ├──── requirements.txt
       ├──── data/
       │       ├──── train/
       │       │       └──── train.csv
       │       └──── test/
       │               └──── test.csv
       └──── scripts/
               └──── main.ipynb


```

## Getting Started

### Clone the repository

You can clone the repository with:
```
git clone https://github.com/foliacouetey/houses_prices.git
```

### Data

The data is split into training and test sets, located in the respective `data/train` and `data/test` directories for both Python and R implementations.

### Scripts

The `main.ipynb` file is a jupyter notebook which contains the main analysis and model training.

It focuses on implementing `linear regression`, `random forest` and `gradient boosting` models. At the end, we noticed that using a simple linear model can give interesting results than advanced models such as random forest or gradient boosting method on trees.

### Python

1. Make sure to install `python version 3.12.4` on your machine.
2. Make sure to install the IDE `Visual Studio Code (VSCode)` on your machine (any version that can support `python version 3.12.4` is okay).
3. Open the folder `PYTHON` with your VSCode IDE.
4. In your VSCode terminal, make sure to create a virtual environment named `.venv` in the folder `PYTHON` with:

      ```python -m venv .venv```

5. In your VSCode terminal, activate your `.venv` environment, and install required packages with: 

      ```
      .venv\Scripts\activate
      pip install -r requirements.txt
      ```

6. Open and run (cell by cell or all cells) the `main.ipynb` notebook using your created virtual environment `.venv` to visualize results.
7. At the end of running all the notebook cells, your local folder `PYTHON\data\test` is populated by a .csv file named `test_pred.csv`.

## License
This project is licensed under the terms of the LICENSE file included in this repository.

## Acknowledgments
- Kaggle for providing the Titanic dataset.
- Any other acknowledgments or credits are for people who developed packages and programming languages used to realize this project.
