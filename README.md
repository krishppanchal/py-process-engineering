# py-process-engineering

python models of separations, reactions, and chemical processes, linked to oil & gas and refinery operations.

all experimental data in this repo was collected by me in a UT Austin lab. each project pairs real lab measurements with a first-principles model (material balances, vle, thermodynamics) and compares the two.

## projects

| project | what it covers | status |
|---|---|---|
| [distillation + gc](separations/distillation) | simple distillation of acetone/toluene, gc composition analysis, raoult's law t-x-y model, rayleigh equation | ✅ complete |
| extraction | acid-base liquid-liquid extraction, partition coefficients, multi-stage efficiency | 🔜 in progress |
| recrystallization | solubility curves, recovery yield, melting-point purity | 🔜 in progress |
| isomerization | cis-trans equilibrium, thermodynamics | 🔜 in progress |

## tools
python · numpy · pandas · scipy · matplotlib · jupyter

## run it
pip install -r requirements.txt, then open any project's analysis.ipynb

---
© 2026 krish panchal. all rights reserved.