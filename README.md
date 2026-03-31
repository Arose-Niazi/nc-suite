# Numerical Computing Suite

A collection of step-by-step numerical computing calculators.

**Live:** [nc.arose-niazi.me](https://nc.arose-niazi.me)

## Tools

| Tool | Path | Methods |
|------|------|---------|
| [LU Decomposition](https://nc.arose-niazi.me/decomposition/) | `/decomposition/` | Doolittle, Crout, Cholesky, PLU |
| [Root Finding](https://nc.arose-niazi.me/roots/) | `/roots/` | Bisection, Regula Falsi, Newton-Raphson, Secant |
| [ODE Solvers](https://nc.arose-niazi.me/euler/) | `/euler/` | Euler, Improved Euler, RK4 |

## Architecture

Git submodules — each tool has its own repo with full history:
- [nc-decomposition](https://github.com/Arose-Niazi/nc-decomposition)
- [nc-roots-finder](https://github.com/Arose-Niazi/nc-roots-finder)
- [nc-improved-euler](https://github.com/Arose-Niazi/nc-improved-euler)

## Development

```bash
git clone --recursive https://github.com/Arose-Niazi/nc-suite.git
# Open index.html in browser
```

## Deployment

```bash
docker compose up -d --build
```

## Author

[Arose Niazi](https://arose-niazi.me)
