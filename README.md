<div align="center">
  <h1>ARTIC</h1>
  <h3>a quick demo of the ARTIC pipeline</h3>
  <hr>
  <a href="https://travis-ci.org/will-rowe/artic-pipeline-example"><img src="https://travis-ci.org/will-rowe/artic-pipeline-example.svg?branch=main" alt="travis"></a>
  <a href="https://mybinder.org/v2/gh/will-rowe/artic-pipeline-example/master?filepath=notebooks"><img src="https://mybinder.org/badge_logo.svg" alt="binder"></a>
</div>

***

## Running the workbooks

To run the workbooks interactively from your browser, use Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/will-rowe/artic-pipeline-example/main?filepath=notebooks)


## Running the workbooks locally

If you want to run the workbooks locally, you'll need `conda` and `jupyter`.

Once you have these, follow these steps:

1. clone the repo
```
git clone https://github.com/will-rowe/artic-pipeline-example

cd artic-pipeline-example
```

2. create the environment
```
conda env create --file=binder/environment.yml

conda activate artic-pipeline-example
```

3. run the notebook
```
jupyter notebook --notebook-dir=./notebooks
```
