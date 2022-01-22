<img src="https://raw.githubusercontent.com/euroargodev/argopy/master/docs/_static/argopy_logo_long.png" alt="argopy logo" width="400"/>
<h1>Argo data access and manipulation made easy</h1>

Argopy is a python library that aims to ease Argo data access from any source, and visualisation/manipulation of data for regular users as well as Argo experts and operators

Open source code: https://github.com/euroargodev/argopy

Documentation: https://argopy.readthedocs.io

Example:
```python
from argopy import DataFetcher as ArgoDataFetcher
argo_loader = ArgoDataFetcher(mode='standard').region([-85,-45,10.,20.,0,10.])
ds = argo_loader.to_xarray()
```

#### Tool Citation

```
Maze Guillaume, Balem Kevin (2020). argopy: A Python library for Argo ocean data analysis. 
Journal of Open Source Software, 5(33), 2425 (4p.). https://doi.org/10.21105/joss.02425
```
