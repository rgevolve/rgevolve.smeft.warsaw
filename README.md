# rgevolve.smeft.warsaw

Package providing Renormalization Group Evolution matrices for the
**SMEFT** in the **Warsaw** basis, following the
[wcxf](https://wcxf.github.io/) conventions for Wilson coefficient
bases.

It is a sub-package of the **rgevolve** ecosystem — a set of Python
namespace packages for fast renormalization group evolution of Wilson
coefficients in the SMEFT and the WET using the evolution matrix
formalism. See the [rgevolve organization](https://github.com/rgevolve)
for the full ecosystem and the
[`rgevolve` meta-package](https://github.com/rgevolve/rgevolve) for
installation in lockstep with the core and all companions.

<!-- BEGIN: auto-generated from data.h5 by .github/scripts/generate-readme.py — do not edit by hand -->

## Contents

This distribution bundles RG evolution matrices precomputed at
**10 scales** between **91.1876** and
**1000000** GeV:

| scale (GeV) |
| ----------- |
| 91.1876 |
| 125 |
| 326 |
| 500 |
| 1000 |
| 2000 |
| 5000 |
| 10000 |
| 100000 |
| 1000000 |

Matrices are organised into **11 sectors** covering a total
of **2511 Wilson coefficients** (counting the real and imaginary
parts of complex coefficients separately):

| sector | # Wilson coefficients |
| ------ | --------------------- |
| `dB=de=dmu=dtau=0` | 1611 |
| `dL=2` | 12 |
| `etauemu` | 8 |
| `mue` | 282 |
| `muemue` | 6 |
| `muemutau` | 8 |
| `mutau` | 282 |
| `taue` | 282 |
| `tauetaue` | 6 |
| `tauetaumu` | 8 |
| `taumutaumu` | 6 |

<!-- END: auto-generated -->

## Installation

```bash
pip install rgevolve.smeft.warsaw
```

To install the core package together with all available EFT/basis
companion packages at once, use the meta-package:

```bash
pip install rgevolve
```

## License

`rgevolve.smeft.warsaw` is licensed under the MIT License — see [`LICENSE`](LICENSE).
