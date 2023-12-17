**MAIN: Source.cpp**

# VLSI CAD ANALYTIC PLACER: QUADRATIC WIRELENGTH MODEL
A C++ program for an analytical-style placer that takes in a NETLIST as INPUT (in the form of .txt file). It uses Quadratic Wirelength definition and large matrix solves (representing system of linear equations) to calculate the optimal placement of very large number of gates on a chip surface, so that the wires/nets that would later be connecting these gates will be short. This placer will also use a single round of recursive partitioning strategy to deal with the fact that the gates will be clustered in overlapping, nonphysical ways, after the first quadratic placement solution. The output is given in the form a .txt file.
