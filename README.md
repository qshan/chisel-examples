
This is a collection of small Chisel example circuits.

Author: Martin Schoeberl (martin@jopdesign.com)

HOWTO:

make alu
	Generates the Verilog files for the small ALU.
	Synthesize it for the DE0 board with Quartus and the alu project file.

make test-alu
	Generats the C++ based simulation and runs the tests.

See the Makefile for further examples, or simply run `sbt run` to see all objects with a main.
