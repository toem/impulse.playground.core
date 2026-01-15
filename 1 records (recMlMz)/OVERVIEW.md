# recMl/recMz Overview

This overview lists signal data files from RTL and SystemC simulations. The files are either:
- **recMl**: XML-based files containing packed signal data.
- **recMz**: Compressed binary files (smaller, faster to load).

**Column explanations:**
- **Target File**: Name of the data file.
- **File Size**: Actual file size on disk.
- **Compression**: Whether the file is compressed (recMz).
- **Scopes**: Number of hierarchical scopes in the simulation.
- **Signals**: Number of signals recorded.
- **Signal Types**: Types of signals (e.g., reg, wire, integer).
- **Domain Base**: Time base unit (e.g., ps, ns).
- **Vector Groups**: Whether vector grouping is used.
- **Time Start/End**: Start and end time of the simulation data.

| Target File | File Size | Compression | Scopes | Signals | Signal Types | Domain Base | Vector Groups | Time Start | Time End |
|----------------|-----------|-------------|--------|---------|--------------|-------------|---------------|------------|----------|
| 1_simple.recMl | 3.3 KB    | No  | 2 | 7 | reg | ps | No | 0 | 3980 |
| 2_modplu.recMl | 198 KB    | No  | 68 | 960 | parameter, reg, wire | ps | Yes | 0 | 4392000 |
| 3_scanio.recMl | 200 KB    | No  | 24 | 779 | real, wire | ps | Yes | 40000 | 38573898016 |
| 4_vortec.recMz | 117 KB    | Yes | 4426 | 27143 | integer, reg, wire | ps | Yes | 0 | 249600000000000 |

