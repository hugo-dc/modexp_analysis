# MODEXP Analysis

## Instructions

Due to GitHub limit of 100MB per file, the MODEXP dataset is split into 3 files, run the following command to merge them:

```bash
cat s_modexp_250105_* > s_modexp_250105.txt
```

Run the jupyter notebook:

```bash
# Create a virtual environment if required
virtualenv -v venv
source venv/bin/activate
# Install jupyterlab
pip install jupyterlab
# Install pandas
pip install pandas
# Run 
jupyter lab
```

## Results

The results are presented in the jupyter notebook [modexp.ipynb](./https://github.com/hugo-dc/modexp_analysis/blob/master/modexp.ipynb).
