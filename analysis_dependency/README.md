# Analysis for Restart-Incremental Dependency Parsing

# Requirements
* Install python3 requirements: `pip install -r requirements.txt`
* We use forks of [SuPar](https://github.com/yzhangcs/parser/tree/main) and [DiaParser](https://github.com/Unipisa/diaparser/tree/master) available under `parser` and `diaparser`, respectively. Please follow the corresponding instructions to install both libraries from the source.

# Setup
``` python
mkdir figures
mkdir outputs
```

# Data
We assume that the file `analysis_meaning/preprocessed_stimuli.csv` is already available. We can then build the data needed for analysis using `build_parse_obj.py`:

``` python
python build_parse_obj.py --model <model_name>
```

# Analysis
The code needed to reproduce the analyses is available in `analysis-dependency.ipynb` and `analysis-dep-variation.ipynb`.