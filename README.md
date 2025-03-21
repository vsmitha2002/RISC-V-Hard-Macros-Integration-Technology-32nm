"# RISC-V-Hard-Macros-Integration-Technology-32nm" 
Objective: Design and Implemented RISC -V IP with Hard Macro Creation and Integration
Key Focus Areas:
1.	Designed and implemented two hard macros for RISC-V sub modules, for meeting area, power, and performance constraints.
2.	Integrated the two hard macros into the top-level design with optimized floor planning, placement, Clock Tree Synthesis and routing.
3.	Optimized design to meet timing constraints using static timing analysis.
    Creation of Macros:
Alu and Machine Counter undergoes synthesis and pnr flow and then with help of library manager (lm_shell) macros are created.

Synthesis:
Synthesis is the process of transforming technology-independent high-level RTL (Register Transfer Level) code, written in languages like Verilog or VHDL, into a technology-dependent gate-level netlist. This netlist consists of interconnected logic gates and flip-flops, mapped to standard cells from a specific technology library.
INPUTS 
RTL Code (VHDL or Verilog) 
Library File (.lib) 
Technology File (.tf) 
Library Exchange Format File Netlist File 
 synthesis constraints (.sdc) 
Unified Power Format (.upf)
OUTPUTS 
Gate-level netlist 
SDF Description  
Netlist File
Power Report
 Area Report
Timing Constraints Report

1. Translation: Converting RTL code into an intermediate representation.
 2. Optimization: Improving the design for area, power, and timing – striking the perfect balance between performance and efficiency. 
3. Mapping: Associating the optimized design with actual logic gates from the technology library.
Why is Synthesis Important? 
• Bridges the Gap: It translates abstract RTL into real hardware components. 
• Ensures Efficiency: Through optimization, synthesis ensures designs meet power, performance, and area (PPA) targets. 
• Facilitates Validation: Post-synthesis verification ensures functional and timing correctness.

