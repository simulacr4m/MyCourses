Q: Show that if a graph's edges all have distinct weights, the MST is unique.

A: If the graph has distinct edges, then when the greedy algorithm is applied on the graph to obtain an MST, each cut without black crossing edges will contain a minimum edge that is not equal to the other crossing edges present. Therefore, is only one possible edge that can be chosen in each cut, meaning that there is only one possible MST.