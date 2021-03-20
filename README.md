# GViz
Graph Visualization Application.
GViz is written in Python Programming Language and developed as a Command Line interface to generate and store visualizations of directed and undirected graphs.

## Install
### Supported OS
Linux  
FreeBSD  
OSX  

### Installation Instructions
git clone https://github.com/kahanikaar/GViz.git
cd GViz
pip install -r requirements
./GViz --help

### Running the CLI Application
1. Data about the nodes and vertices is to be stored in .csv or any files with comma separated values without any labels where each row or entry of the file is a vertex of the graph in the format given below  
For Undirected Graph: node1, node2
For Directed Graph: source, destination
Check out the sample of data source file here https://github.com/kahanikaar/GViz/blob/main/file.csv
2. Launch the terminal and move to the directory were GViz was cloned
3. ./GViz -p [source file path] 
4. Visualization for the graph is plotted.
