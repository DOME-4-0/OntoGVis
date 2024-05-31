# JSON-LD Network Visualization

visualize JSON-LD files as a network graph in your web browser.
made by Roberto Bendinelli for any issues write at : roberto.bendinelli@epfl.ch

## How to Use

1. **Upload a JSON-LD File:**
   - Click the "Choose File" button to select a JSON-LD file from your computer.

2. **Pick a Layout:**
   - Use the dropdown menu to select either "Network Layout" or "Hierarchical Layout".

3. **See the Graph:**
   - The graph will show up with your JSON-LD data. You can zoom in, zoom out, and move around.
    - Nodes: Represent entities or values. They are styled based on their type:
    - General nodes: Light blue.
    - Nodes linked by @id: Sky blue.
    - @type nodes: Light pink, diamond-shaped with thicker borders.
    - Value nodes: Gold, diamond-shaped.
    - Specifically identified @id nodes: Dark sea green.
    - Edges: Represent relationships between nodes. They are styled with different colors and line styles.