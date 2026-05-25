# s224712709 — SIT215 Assignment 3 README
**Student:** Barbara Rein Calma | **ID:** s224712709

## Files Submitted
| File | Description |
|------|-------------|
| `s224712709_assign3integratedsystem_report.pdf` | Main report (all 4 tasks) |
| `s224712709.ipynb` | Jupyter Notebook — complete solution |
| `s224712709_README.md` | This file |
| `s224712709_demo_video.mp4` | 3-minute narrated video |

## Execution Instructions

### Requirements
```
Python 3.9+
numpy
matplotlib
scikit-fuzzy
```

### Install dependencies
```bash
pip install numpy matplotlib scikit-fuzzy
```

### Run the notebook
```bash
jupyter notebook s224712709.ipynb
```
Then run all cells top to bottom (Cell → Run All).

### Cell Structure
| Cell | Task | Content |
|------|------|---------|
| 1 | — | Markdown overview |
| 2 | 1.1 | Environment setup (nodes, edges, graph) |
| 3 | 1.2–1.3 | Cost functions and heuristics |
| 4 | 1.3–1.4 | A* baseline execution + visualisation |
| 5 | 2.1–2.2 | Fuzzy inference system design and implementation |
| 6 | 2.3 | FIS visualisation (MF plots, rule matrix, defuzzification) |
| 7 | 3.1 | Integrated A* with fuzzy speeds |
| 8 | 3.2 | Replanning under school-zone constraint |
| 9 | 3.3 | Comparison tables and summary plots |

### Notes
- Random seed = 42 is fixed throughout for reproducibility
- All figures render inline in the notebook
- The school-zone edge selection uses `random.seed(42)` before shuffling — the 60% constraint set is identical across all runs
- No external data files required — all graph data is embedded in Cell 2
