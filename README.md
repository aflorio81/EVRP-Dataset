# EVRP-Dataset
Instance set for "Routing Electric Vehicles on Congested Street Networks"

Filenames are in the format \`LL-nodes-series-*', where \`nodes' is the number of nodes, and \`series' is the series of the instance (1 to 5).

Files with extensions .xy contain nodes coordinates (one node per line).

Files with extensions .d contain arc distances. The first line of each file indicates the number of arcs. Each subsequent line indicates the origin node, destination node, and arc length.

Files with extensions .demands are in the format \`LL-nodes-series-customers.demands', where \`customer' indicate the number of customers. The first line starts with \`0' and indicates the coordinates of the depot (identical to the first line in the corresponding .xy file). From the second line on, the coordinates of the customers are given (also identical to the corresponding .xy file), and the demand of each customer is as indicated in the fourth field. The remaining fields can be ignored.
