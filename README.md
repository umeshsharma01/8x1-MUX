# 8x1-MUX
An 8×1 Multiplexer using 4×1 Multiplexers is a hierarchical design that demonstrates how larger multiplexers can be constructed from smaller building blocks
An 8×1 multiplexer selects one of eight input signals and forwards it to a single output using three select lines.
Two 4×1 multiplexers are used in the first stage to select one input from each group of four and a 2×1 multiplexer is used in the second stage to choose between the outputs of the two 4×1 multiplexers.
The lower two select lines are applied to both 4×1 multiplexers while the most significant select line controls the final selection between them.
