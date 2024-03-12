# VARSGP
Numerics on variational learning of sparse gaussian processes [(Titsias, 2009)](https://proceedings.mlr.press/v5/titsias09a.html).

The `/data` folder contains the [SARCOS dataset](https://gaussianprocess.org/gpml/data/) used in the original paper. 

Additional to the usual libraries (numpy, pandas, sklearn, pytorch, matplotlib), the notebook uses `gpytorch`[(Gardner et al., 2018)](https://proceedings.neurips.cc/paper_files/paper/2018/hash/27e8e17134dd7083b050476733207ea1-Abstract.html) and `ucimlrepo`[(Kelly et al.)](https://archive.ics.uci.edu) which can be installed as follows:
```
pip install gpytorch
pip install ucimlrepo
```
Alternatively, all requirements can be installed using the following:
```
pip install -r requirements.txt
```