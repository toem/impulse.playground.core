
# Expressions (recJx) Overview

This directory contains example record producer scripts using the impulse expression language and API. Each `.recJx` file demonstrates different signal types, data generation techniques, and advanced features for creating test records.

**Column explanations:**
- **Expression File**: Name of the script file.
- **Time Base**: Time unit used (ns/ms).
- **Main Signals**: Key signal types and structures.
- **Features**: Main features and demonstration focus.

| Expression File    | Time Base | Main Signals                | Features/Description |
|--------------------|-----------|-----------------------------|---------------------|
| expression01.recJx | ns        | Integer, Struct, FloatArray | Sine wave, multiple struct signals, 2D float array, member/label usage |
| expression02.recJx | ns        | Logic (bus, control)        | Clock, address/data bus, enable/RW, signal relations (Settle, Delay) |
| expression03.recJx | ns        | Integer, IntegerArray, Enum, Struct | Sine/cosine data, enum events, struct with enum/integer, event relations |
| expression04.recJx | ns        | Integer, Enum (tasks/ISR)   | Multi-core task/ISR events, hierarchical scopes, event relations |
| expression05.recJx | ns        | Integer, Struct             | Sine wave, two struct signals, multiple members, sample kinds (GO_INITIAL/INTER/FINAL) |
| expression06.recJx | ms        | Float (a0-a7)               | 8 float signals, random waveform generation, trigonometric expressions |
| expression07.recJx | ns        | Integer, Enum (tasks/colors), Float | Color/label/event demonstration, Gantt/event color areas, user formats, associations |
| expression08.recJx | ns        | Enum (state machine), Integer, Struct | State machine, buffer/send events, struct logs, event relations, repeated sequence |
| expression09.recJx | ms        | Integer, Enum (event)       | Sine wave, event signal with label format, event writing |
| expression10.recJx | ns        | Struct                      | Two struct signals, enum/text/integer members, log message simulation |

