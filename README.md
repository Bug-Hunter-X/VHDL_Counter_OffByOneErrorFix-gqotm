# Off-by-One Error in VHDL Counter

This repository demonstrates a common, subtle error in VHDL code: an off-by-one error in a counter.  The counter is designed to count from 0 to 15, but a minor mistake in the reset condition could lead to unexpected behavior.

The `bug.vhdl` file contains the code with the error. The `bugSolution.vhdl` file provides the corrected version.

This example highlights the importance of carefully considering edge cases and potential unintended consequences in digital design.