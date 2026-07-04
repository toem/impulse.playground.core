# Values (CSV) Overview

This directory contains example CSV data files with various signal types and test data. Each `.csv` file demonstrates different data acquisition scenarios and formats.

**Column explanations:**
- **CSV File**: Name of the data file.
- **Data Type**: Type of data contained (sensor data, mathematical values, signals, logs).
- **Main Columns**: Key column names and descriptions.
- **Description**: Purpose and content of the file.

| CSV File | Data Type | Main Columns | Description |
|----------|-----------|--------------|-------------|
| 1_cantrace.csv | CAN Bus Trace | timeInMillies, delay, received, axisA, axisB | CAN bus trace data with timestamps (milliseconds), communication delay, received flag, and two axis measurements (axisA, axisB) with floating-point values. Demonstrates real-time sensor data acquisition. |
| 2_fsequen.csv | Mathematical Functions | t, cos, sin, tan, sqr | Trigonometric function sequences from t=1 to t=19 with computed cosine, sine, tangent, and square values. Simple mathematical signal generation. |
| 3_signals.csv | Analog Signals | time, osc_out, lvdt_outp, lvdt_outn, probe_position, U_topDesign.* | High-precision analog signal data with oscillator output, LVDT (Linear Variable Differential Transformer) measurements, probe position, and multiple derived signals (soutput_fx, detect_p, detect_n, pga_out_p, pga_out_n, adc_out_p, adc_out_n). Represents signal conditioning and conversion pipeline. |
| 4_syslog.csv | System Log | timestamp, level, thread, message | System log entries with millisecond precision timestamps, log levels (TRACE, DEBUG, INFO, WARN, ERROR, FATAL), thread identifiers (ThreadA, ThreadB, main), and log messages. Demonstrates mixed multi-threaded system logging. |
