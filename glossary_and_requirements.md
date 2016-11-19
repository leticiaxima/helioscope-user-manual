# Glossary and Requirements {#glossary-and-requirements}

**Glossary of Terms**

| **Term** | **Definition** |
| --- | --- |
| Project | 

*   A Project represents a specific location where an array (or set of arrays) will be designed and installed.
*   The Project is the highest-level structure in HelioScope; all Designs and Condition Sets are created under a Project.

 |
| Design | 

*   A Design describes the physical layout of a solar array.
*   A Design includes the modules used, the quantity and location of the modules, and how the modules are oriented. It also includes the electrical stringing design, the conductors used, the inverters used, and the location of the inverters.

 |
| Field Segment | 

*   A Field Segment is an area of the design used to define module layouts.
*   A user defines a shape, which is populated with modules based on a set of layout rules.
*   A Design can contain multiple Field Segments.

 |
| Keepout | 

*   A Keepout is an area of the design used to define shading objects and keepout zones where modules cannot be placed.
*   A user defines a shape, which can be given a height and a setback.
*   A Design can contain multiple keepouts.

 |
| Wiring Zone | 

*   A Wiring Zone defines the electrical rules for the modules that have been laid out in the Field Segment.
*   A Wiring zone consists of one or more Field Segments, an inverter SKU and quantity, and a set of rules for how to connect the modules electrically (including the string size, conductor size, and combiner box size).
*   A Design can contain multiple Wiring Zones, but a single Field Segment may not be split across multiple Wiring Zones.

 |
| Condition Set | 

*   A Condition Set describes the environment around the solar array.
*   A Condition Set includes a weather file, shading assumptions, soiling assumptions, temperature assumptions, and other potential loss factors and simulation settings.

 |
| Simulation | 

*   A Simulation is an estimate for how much energy a Design will produce over a full year, based on the environment defined in the Condition Set.
*   Simulations are based on hourly time intervals (8,760 per year).

 |
| Report | 

*   The results of each Simulation can be viewed as a report, which summarizes the production of the corresponding Design under the given Conditions.
*   Reports will also show the calculation of system losses at each step in the process.

 |
|  |  |

**System Requirements**

HelioScope is a web-based product that can be accessed from any standard modern browser. Recommended browsers include Chrome and Firefox. Safari, Edge, and Internet Explorer 10 are also supported but not recommended. Internet Explorer 8 (or earlier) is not supported.