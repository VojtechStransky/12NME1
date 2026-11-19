# 12NME1

> **Coursework.** Homework written in 2024 for the course 12NME1 *Numerical
> Methods 1* at the Faculty of Nuclear Sciences and Physical Engineering,
> CTU in Prague.

Seven short Python scripts, one per homework. Each method is written by hand;
NumPy is used for arrays and, where noted, to compare.

| Script | Topic | What it does |
|---|---|---|
| `nme11.py` | numerical integration | area under 1/x by a rectangle sum, with a plot |
| `nme12.py` | errors and stability | finds the step where a forward difference reaches 10 % error; shows how the recurrence yₙ = 1/n − 10·yₙ₋₁ blows up |
| `nme13.py` | linear systems | inverse of a 3×3 matrix by Gauss–Jordan elimination with row swaps |
| `nme14.py` | determinants | determinant by elimination and by cofactor expansion, compared with `numpy.linalg.det` |
| `nme15.py` | interpolation | value of the interpolating polynomial at one point by Neville's algorithm |
| `nme16.py` | least squares | cubic fit of 11 points through the normal equations |
| `nme17.py` | root finding | Halley's method with derivatives taken numerically |

## Run

Needs Python 3 with NumPy and Matplotlib (`nme11.py` also needs a LaTeX
installation for the plot labels).

```bash
python nme15.py
```

The inputs are written at the top of each script.
