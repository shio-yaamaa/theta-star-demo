This website demonstrates how Theta* algorithm of my implementation (might have bugs) behaves.

# 1. Configure the grid size

The number of columns/rows must be from 1 to 50.

# 2. Configure individual cells

Click on the cell to configure. The configuration options include:

- Set as start: The path starts from the cell.

- Set as end: The cell becomes the destination of the path.

- Block this cell: Block the cell so that the path cannot pass through it.

- Weight: Defines how much cost/effort you need to pass through the cell. Must be positive and <= 1000.

# 3. Start pathfinding

Click on the start button. The path found by the algorithm will be displayed as a white line.

# 4. Check the metrics

Four metrics are provided:

- Cumulative cost: G of the last cell.

- Total distance

- Number of cells left in the open list

- Number of cells in the closed list