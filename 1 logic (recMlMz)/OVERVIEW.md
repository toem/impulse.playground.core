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
|-------------|-----------|-------------|--------|---------|--------------|-------------|---------------|------------|----------|
| logic01.recMl | 3.3 KB    | No  | 2 | 7 | reg | ps | No | 0 | 3980 |
| logic02.recMl | 198 KB    | No  | 68 | 960 | parameter, reg, wire | ps | Yes | 0 | 4392000 |
| logic03.recMl | 8.9 KB    | No  | 1 | 1 | real | us | No | 0 | 2396 |
| logic04.recMl | 15.8 KB   | No  | 3 | 14 | wire | ps | Yes | 40000 | 40000000 |
| logic05.recMl | 200 KB    | No  | 24 | 779 | real, wire | ps | Yes | 40000 | 38573898016 |
| logic06.recMl | 42.3 KB   | No  | 1 | 1 | real | ms | No | 0 | 35160 |
| logic07.recMl | 7.2 KB    | No  | 3 | 13 | reg | fs | No | 0 | 20400000000 |
| logic08.recMl | 498 KB    | No  | 11 | 482 | integer, parameter, reg, tri, tri0, tri1, wand, wire | ps | Yes | 0 | 4504000000 |
| logic09.recMl | 752 KB    | No  | 2 | 468 | parameter, reg | ns | No | 0 | 319980 |
| logic10.recMl | 1.5 KB    | No  | 3 | 5 | integer, reg, trireg | N/A | No | 2000 | 8040 |
| logic19.recMl | 6.1 MB    | No  | 1 | 64 | wire | ps | Yes | 91451512556 | 144851415092 |
| logic19.recMz | 755 KB    | Yes | 1 | 64 | wire | ps | Yes | 91451512556 | 144851415092 |
| logic29.recMl | 5.1 MB    | No  | 4426 | 27143 | integer, reg, wire | ps | Yes | 0 | 249600000000000 |
| logic29.recMz | 117 KB    | Yes | 4426 | 27143 | integer, reg, wire | ps | Yes | 0 | 249600000000000 |

