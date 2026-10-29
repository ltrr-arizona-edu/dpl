# Dendrochronology Program Library (DPL)

> **A historical archive.** These programs are no longer maintained and will not
> run on modern operating systems. They are preserved here for the historical
> record, not as working software.

The Dendrochronology Program Library is a collection of DOS-era programs for
dendrochronology and dendroecology, written and maintained by the legendary 
**Richard L. Holmes** at the Laboratory of Tree-Ring Research (LTRR). This
repository preserves the final public distribution — **Update 150, 18 April 2001** —
for posterity.

The programs are 16-/32-bit DOS executables that depend on DOS memory managers
(`DOSXMSF` / `DOSXNT`) and the `PKUNZIP` utility, and they will not run on
present-day systems without a DOS emulator.

## Why preserve this software? 

In making these tools widely available, Richard Holmes revolutionized the field. 
DPL programs were pioneering pieces of software and several became standard tools 
in tree-ring laboratories worldwide and shaped how the field does quantitative dendrochronology.

- **COFECHA** — crossdating and measurement quality control. For decades the de
  facto standard for verifying the dating and measurement accuracy of tree-ring
  series.
- **ARSTAN** — chronology development with detrending and robust statistical
  analysis. The standard program for building standardized tree-ring chronologies.

The ideas and techniques these programs created continue today in modern, open-source tools
such as [dplR](https://opendendro.org/r/) (R) and [dplPy](https://opendendro.org/python/)
(Python).

## Contents

Each program is stored as a separate compressed (`.ZIP`) file, alongside the
original documentation:

- `A-INFO.HTM` — general information and the full program list (English & Spanish)
- `A-NEWS.txt` — notes on changes across versions
- `DOCUMENT.ZIP` — brief text descriptions of each program (one `.TXT` per program)

### Selected programs

| Program | Purpose |
|---|---|
| `AGECRV` | Fit a general site pith-age curve to measurements |
| `ARSTAN` / `ARSTANL` | Chronology development with statistical analysis (ARSTANL: larger capacity) |
| `CASE` | Convert casewise (column) data to compact format |
| `CHISQ` | Chi-square testing |
| `COFECHA` / `COF12K` | Dating & measurement quality control (COF12K: spans to 12,000 years) |
| `CRONOL` | Simple chronology production |
| `DOSXMSF` / `DOSXNT` | DOS memory managers required by the other programs |
| `EARLAT` | Detrend earlywood/latewood measurement series |
| `EDRM` | Edit ring-measurement files |
| `EVENT` | Superposed Epoch Analysis |
| `EXTRAP` | Fit a curve and extrapolate expected growth |
| `FHCONV` | Convert dBase files to Fire History format |
| `FMT` | Manipulate data and change formats |
| `JOLTS` | Detect surges and suppressions in tree growth |
| `OLDCORE` | Retain the earliest (innermost) ring measurements |
| `OUTBREAK` | Detect insect population outbreaks |
| `PCA` / `RECPC` | Principal components analysis / reconstruct variables from PCs |
| `RESPO` | Response and correlation functions with climate |
| `RMATSG` | Correlation matrix of series by segments |
| `SAMDEP` | Even out sample depth over time |
| `SSA` | Singular spectrum analysis |
| `SCATTER`, `SCRPLT`, `SCRSAV` | Plotting and screen utilities |

The complete list of programs and their descriptions is in `A-INFO.HTM` and
`DOCUMENT.ZIP`.

## Provenance

Written and maintained by **Richard L. Holmes**, Laboratory of Tree-Ring Research,
University of Arizona. The 2001 distribution preserved here was also mirrored
at the Laboratorio de Dendrocronología, CRICYT-CONICET, Mendoza, Argentina
by José A. Boninsegna, Silvia Delgado, and Eduardo Rubén Soria,


## License & use

See [`LICENSE`](LICENSE). This material is provided **as-is, for historical and
educational purposes, with no warranty** — consistent with the disclaimer that
accompanied the original distribution.
