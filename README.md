# diffusion2d

## Description

This code solves the diffusion equation over a two dimensional square domain which is at a certain temperature, and a circular disc at its center which is at a higher temperature. The diffusion equation is solved using the finite-difference method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.


## Installing the package
```bash
pip install -i https://test.pypi.org/simple/ merklesn-diffusion2d
```

## Running this package
To include this package into your code use:

```python
from merklesn_diffusion2d import diffusion2d
diffusion2d.solve()
```

Or use:
```python
from merklesn_diffusion2d import solve
solve()
```

Parameters of solve(dx:float, dy:float, D:int):
- dx: Intervals in x directions (mm). Default value = 0.1
- dy: Intervals in y directions (mm). Default value = 0.1
- D: Thermal diffusivity of steel (mm^2/s). Default value = 4

## Citing
[Learning Scientific Programming with Python (2nd edition): Chapter 7](https://scipython.com/books/book2/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/)

