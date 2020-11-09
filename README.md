# KiCad Schematic for IR Interactive Coffee Table
The following repository contains all the KiCad files that are used to create the circuit for the interactive coffee table

The circuit is made up of 2 sections, with each section made up of the same smaller circuit. The smaller circuit contains a shift register that pushes data to a darlington array. This part is used to control turning on the IR Emitters. The smaller circuit also contains a multiplexer that reduces the amount of photodiode lines. There are power in and out lines, and both the shift register and multiplexer parts are able to be daisy chained.
