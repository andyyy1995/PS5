********
*README*
********

Project title: Network Motif Approach to Identifying Therapeutics Targets for Melanoma

Authors: Hyun Min Kim  and Harvey Yang



**Overview:**
This repository contains a graph (GRAPHML file) and a corresponding iPYNB script that can be run on Jupyter Notebook to produce a visual  representation of the graph.



*Data*
The data from Wang, et al. (2014) [1] was acquired in SBML file format from  the BioModels Database [2]. Cytoscape software was then used to  import the SBML file and export as a GRAPHML file, namely <Wang2014.graphml>.

The <Generate_Graph.ipynb> script was then run on Jupyter Notebook to generate a circular graph <Wang2014_Dataset_NetworkX_Graph.png> using Python's NetworkX, and the related edgelist text files <network_edgelist_66_dic.txt> and <network_edgelist_666.txt>.


[1] Wang, Pei, Jinhu L?, and Xinghuo Yu. "Identification of important nodes in directed biological networks: A network motif approach." PloS one 9.8 (2014).
[2] https://www.ebi.ac.uk/biomodels-main/BIOMD0000000666 



*Folder Structure*
Currently, there are three folders: 
(1) "Datasets" contains the original data used
(2) "NetworkX Graphs" contains the outputs of analyses
(3) "Scripts" contains the scripts used to conduct analyses 

Each folder contains a subolder  "Wang_2014." As the project proceeds, additional subfolders will be added in each main folder. Each subfolder will be named according to the origin of the dataset. This format separates data from code and analyses, while still enabling an easy way to locate and match each dataset with the analyses we perform.



*Installation*
Download Python 3.7 from <https://www.python.org/downloads/> and Anaconda from <https://www.anaconda.com/distribution/>. 
The <Generate_Graph.ipynb> can then be run on Jupyter Notebook. 
The Cytoscape software used to conver the original SBML data into GRAPHML form is available online at <https://cytoscape.org/>, but is not necessary as the graph has been provided in GRAPHML form in this repository.
