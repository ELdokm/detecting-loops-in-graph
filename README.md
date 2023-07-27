# Graph Loop Detection
This Python code reads a graph from a CSV file and detects loops in it.

## How to Use

1. Replace `"path"` with the actual path to your CSV file containing the graph edges.

2. Ensure that the CSV file contains two columns: 'source' and 'target', representing the edges of the graph.

3. Run the code. It will read the CSV file, create a directed graph, find loops, and display the graph.

## Dependencies

- pandas
- networkx
- matplotlib

## Example CSV Format

The CSV file should have two columns: 'source' and 'target', representing the edges of the graph.

## Output

If there are loops in the graph, the code will print the loops found. Otherwise, it will display "No loops found."

## Author

Mohamed Eldokm 
