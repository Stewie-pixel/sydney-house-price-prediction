# Sydney Housing Price Analysis

This project analyses recently sold residential properties in Newtown, Burwood,
and Waterloo. The Jupyter notebook loads the supplied housing data, explores
price and property characteristics, visualises patterns, and compares machine
learning models for sale-price prediction.

## Project files

- `report.ipynb` - data analysis, visualisations, and predictive modelling.
- `sydney_housing_price_data.xlsx` - input housing dataset.
- `requirements.txt` - Python dependencies required by the notebook.
- `report.pdf` - exported report.

## Setup

Use Python 3.10 or newer and create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run the notebook

Start Jupyter:

```bash
jupyter notebook
```

Open `report.ipynb` and run the cells in order. Keep
`sydney_housing_price_data.xlsx` in the project directory so that the notebook
can load it with its relative path.

## Notes

The notebook uses pandas, NumPy, Matplotlib, Seaborn, and scikit-learn. The
`openpyxl` dependency is required by pandas to read the Excel workbook.
