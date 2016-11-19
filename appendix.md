# Appendix {#appendix}

**Glossary: Report Summary Metrics**

| **Term** | **Description** |
| --- | --- |
| Production | The total energy generated during the simulation, in AC MWh or GWh |
| Performance Ratio | Performance Ratio (PR) shows the percentage of total potential energy for the array that is converted to AC energy. |
| kWh/kWp | The specific energy – total simulation energy generation divided by the system DC nameplate power. |

**Glossary: Annual Production Metrics**

| **Term** | **Description** |
| --- | --- |
| Annual Global Horizontal Irradiance | The total irradiance that will fall on a flat plane at the location of the array. This is aggregated directly from the weather file. |
| POA Irradiance | The total irradiance in the Plane of Array (POA), accounting for tilt and azimuth angles. This is averaged across all modules in the array. |
| Shaded Irradiance | The total irradiance accounting for all shading (from horizon, row-to-row, and obstruction) |
| Irradiance after Reflection | The total irradiance after accounting for reflection off the surface of the module (also known as the Incident Angle Modifier, or “IAM” reflection). |
| Irradiance after Soiling | Irradiance after module soiling is accounted for. Note that soiling assumptions are made in the Condition Set. |
| Total Collector Irradiance | The total annual irradiance available to the modules in the array. This is averaged across all modules. |
| Nameplate | The maximum potential power of the array, defined as the total collector irradiance multiplied by the system nameplate power. |
| Output at Irradiance Levels | The total energy output by the modules, after accounting for low-light effects and module IV curve distortions. |
| Output at Cell Temperature Derate | The total output of the modules, factoring in the temperature effects on the IV curves. This is the sum of the modules at their maximum power points. |
| Output After Mismatch | The total energy output of the modules, factoring in all system constraints (e.g. series &amp; parallel mismatch, voltage drop, etc.). |
| Optimizer Output | If DC optimizers are present, this shows the total output of the optimizers, factoring in their efficiency curves and principles of operation. |
| System DC Output | The total energy output of the DC system, accounting for all wire resistive losses. |
| System AC Output | The total AC energy output from the inverters, taking into account inverter performance losses. |