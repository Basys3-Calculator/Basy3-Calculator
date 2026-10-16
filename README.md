# Basy3-Calculator
FPGA Design Project for NUS EE2026 Digital Design


# Tracking the Project Files

What to track:
• Source Files: Your .v (Verilog), .sv (SystemVerilog), or .vhd (VHDL) files located inside the *.srcs/ directory.
• Constraints File: Your .xdc file (which defines pinouts and timing constraints).
• Project File: The .xpr file, which holds the project structure and references.
• IP Blocks (if used): Only the .xci configuration files for your IP, not the generated outputs.

What to ignore (Add to .gitignore):
You must exclude auto-generated directories like *.cache/, *.runs/, *.hw/, *.ip_user_files/, and massive binary output files like .bit or .mcs streams unless you are marking a final release.
