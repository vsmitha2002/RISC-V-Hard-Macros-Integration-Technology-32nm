
🚀 RISC-V IP with Hard Macro Creation and Integration
📌 Objective
Design and implementation of RISC-V IP with hard macro creation and integration, focusing on area, power, and performance constraints.

🔥 Key Focus Areas
✅ Designed and implemented two hard macros for RISC-V sub-modules, meeting area, power, and performance constraints.

✅ Integrated the hard macros into the top-level design with optimized floor planning, placement, and routing.

✅ Optimized the design to achieve timing closure and meet power constraints using Static Timing Analysis (STA).

🛠️ Inputs to Physical Design
Netlist (.v): Verilog files representing the logical connectivity of the design.

Liberty File (.lib): Specifies the timing, power, and functional characteristics of standard cells.

Design Constraints (.sdc): Defines timing, area, and power constraints.

Technology File (.tf): Includes manufacturing process details such as metal layers and design rules.

LEF File (.lef): Abstract physical views and design rules of standard cells and macros.

DEF File (.def): Contains the layout description, including floorplan, cell placement, and routing.

Power Intent File (.upf): Defines power domains and low-power strategies.

TLUPlus File (.tluplus): Used for parasitic extraction and delay calculation.

🔨 Creating Macros
Converted ALU and Machine Counter blocks into hard macros using:

Design Compiler for synthesis.

ICC2 for physical design.

LM Shell (Library Manager) for GDS II to NDM conversion.

⚙️ Synthesis and Physical Design Flow
Synthesis:

Converted RTL to gate-level netlist using Synopsys Design Compiler.

Physical Design:

Transformed the gate-level netlist into a physical layout (GDS II) using Synopsys ICC2.

Hard Macro Creation:

Imported GDS II files into Library Manager (LM) and converted them into NDM format.

📏 Design Specifications
Role: Synthesis, P&R, and Timing Analysis

Technology Node: 32nm

Layers: 8 Metal layers

Hard Macros: 2 (ALU and Machine Counter)

Instance Count: ~25k

Number of Clocks: 1

🔧 Tools Utilized
Synthesis: Design Compiler (Synopsys)

Place & Route: IC Compiler II (Synopsys)

Timing Analysis: PrimeTime (Synopsys)

Physical Verification: Calibre (Siemens)

🚀 Responsibilities
🛠️ Creating a design library and importing NDM, Technology files, Parasitic Models, and RTL.

⏱️ Writing MCMM timing constraints and loading them into the tool.

🔧 Performing synthesis and exporting Netlist, SDC, and DEF files.

📐 Floorplanning, shaping blocks, and placing Pins, I/Os, and Macros.

⚡ Creating a Power Plan with rings, straps, rails, and power mesh.

🔍 CCD Optimization and inserting ICGs.

🕒 Performing Clock Tree Synthesis (CTS).

🔗 Global and detailed routing, followed by DRC checks.

✅ Running signoff checks and exporting Netlist, GDS II, SDC, SPEF, and DEF files.

📊 Timing Analysis using PrimeTime, including:

Generating timing reports.

Fixing violations by resizing cells, inserting/deleting buffers, cell swapping, and net improvements.

📬 Contact
👤 Velagacharla Sai Chandrika Smitha Venkat
📧 Email: your-email@example.com
🔗 GitHub Profile

