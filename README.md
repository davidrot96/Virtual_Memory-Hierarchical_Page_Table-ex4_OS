# Virtual_Memory-Hierarchical_Page_Table-ex4_OS
Hierarchical page tables use a tree of smaller tables to save memory. This effectively separates the
translation into multiple steps. These tables reside in frames of the RAM just like any other page.
Each row of a table either contains the number of frames containing the next table in the layer
below it or, if it is in the lowest layer, the number of frames containing the relevant page.
