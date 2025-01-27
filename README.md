# microbe_metabolite_network
IITM_DTU technical task: Mapping the metabolite production (C1/C2 metabolism) profile of the microbe

%%%--Readme for microbe-metabolite network script--%%%

This script can be use for constructing a metabolite production network of microbial species using the information provided in the network_input.csv file. The script can also be use to visualize the directed network.


%%%--Prerequisites--%
 
Python 3 will be required to run the script. Use the Jupyter notebook for better readability.

Required Python Libraries:

1. networkx
2. matplotlib

Install the libraries using pip if they are not already installed:
"pip install networkx matplotlib"

%%--How to run--%%

--> First, load the provided "network_input.csv" file and make a list of unique Microbes and metabolites.

--> Prepare a directed NetworkX graph (microbe_met_network) with the following structure:
Nodes must have a type attribute, either "Microbe" or "Metabolite".
Edges represent relationships between nodes.

Run the script.

The network visualization will be displayed as a plot.

%%--Customization--%%
Change the layout of the network "strc = nx.spiral_layout(microbe_met_network)" for different visualization.
The node/edges color and size an be customized for better visualization.


