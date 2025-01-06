# Uncommon VHDL Bug: Missing 'else' in Conditional Assignment

This repository demonstrates a subtle but potentially problematic bug in VHDL code.  The bug is a missing 'else' statement within a conditional assignment inside a process. While seemingly minor, this omission leads to unexpected behavior in the counter.

The `buggy_counter.vhdl` file contains the erroneous code. The `buggy_counter_solution.vhdl` file provides the corrected version.  This showcases how a seemingly small oversight can lead to significant problems, underscoring the importance of thorough code review and testing, especially in hardware description languages like VHDL.