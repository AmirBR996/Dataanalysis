# Data Analysis & Feature Engineering

A collection of Jupyter notebooks covering essential data preprocessing, feature engineering, and exploratory data analysis techniques using Python, pandas, and scikit-learn.

## Contents

### 📊 Exploratory Data Analysis
| Notebook | Description |
|---|---|
| [`Univariate_pynb.ipynb`](Univariate_pynb.ipynb) | Univariate analysis of categorical and numerical features using count plots, pie charts, and histograms |
| [`bivariate.ipynb`](bivariate.ipynb) | Bivariate analysis — numerical-numerical scatter plots, numerical-categorical relationships |
| [`global_disaster.ipynb`](global_disaster.ipynb) | EDA on a global disaster response dataset (2018–2024): trends by year, month, and disaster type |
| [`DATE&TIME.ipynb`](DATE&TIME.ipynb) | Extracting and working with date/time features (year, month, etc.) in pandas |
| [`working_on_titanic.py`](working_on_titanic.py) | Basic Titanic dataset analysis: missing value handling, correlation with survival |

### 🔧 Feature Engineering & Preprocessing
| Notebook | Description |
|---|---|
| [`BINNING.ipynb`](BINNING.ipynb) | Numerical feature binning with `KBinsDiscretizer` (uniform & quantile strategies) |
| [`MIXED_VARIABLES.ipynb`](MIXED_VARIABLES.ipynb) | Splitting mixed-type columns into numerical and categorical components |
| [`HANDLING_MISSING_CATEGORICAL.ipynb`](HANDLING_MISSING_CATEGORICAL.ipynb) | Imputing missing categorical values using mode and custom strategies |

### ⚖️ Feature Scaling
| Notebook | Description |
|---|---|
| [`Standardization.ipynb`](Standardization.ipynb) | Z-score standardization with `StandardScaler` and why scaling matters |
| [`min_max_scaling.ipynb`](min_max_scaling.ipynb) | Min-max normalization with `MinMaxScaler` |
| [`Power_Transformer.ipynb`](Power_Transformer.ipynb) | Non-linear transformations (Box-Cox, Yeo-Johnson) to make distributions more Gaussian |
| [`function_transformer.ipynb`](function_transformer.ipynb) | Applying custom transformations with `FunctionTransformer` |

### 🏷️ Encoding
| Notebook | Description |
|---|---|
| [`Encoding.ipynb`](Encoding.ipynb) | Ordinal encoding, label encoding, and one-hot encoding with scikit-learn |
| [`Column_Transformer.ipynb`](Column_Transformer.ipynb) | Applying different preprocessing pipelines to different column types using `ColumnTransformer` |

## Datasets

| File | Used In |
|---|---|
| `titanic.csv` | `MIXED_VARIABLES.ipynb`, `working_on_titanic.py` |
| `Social_Network_Ads.csv` | `Standardization.ipynb`, `min_max_scaling.ipynb` |
| `covid_toy.csv` | `Column_Transformer.ipynb` |
| `customer.csv` | `Encoding.ipynb` |
| `housing.csv` | `HANDLING_MISSING_CATEGORICAL.ipynb` |
| `placement.csv` | Various notebooks |

## Technologies

- **Python 3**
- **pandas** — data manipulation and date/time handling
- **NumPy** — numerical operations
- **scikit-learn** — preprocessing, encoding, scaling, and transformation
- **Matplotlib / Seaborn** — data visualization
- **SciPy** — statistical transformations

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/AmirBR996/Dataanalysis.git
   cd Dataanalysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn scipy jupyter
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

4. Open any notebook from the list above and run the cells.
