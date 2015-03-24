# Using-Scipy-KDTree
This inquiry report provides an example of how to use the KDTree function from the spatial module of Scipy. 
#Background
Referring to my "Using the glob module", I found a way to extract desired data from files that exist in subfolders of folders within a directory. Having the data that is needed is a necessary step, but the information is useless without a structure that assumes the data and provides meaning to it. For my world map project I plan on placing nodes as pinpoints on the map based on the lat/long pairs that accompany each mp3 file. I need to find a way to create these nodes and place them into an ordered structure so that they can then be accessed and ultimately used with the map.
#Question
Now that I have the data I need in the form of a list of 4-element vectors, what structure can I use to produce an ordered sequence of nodes to represent lat/long pairs?
#About KDTree
KDTree is a function offered by the spatial module of Scipy. A KDTree is a hierarchical tree capable of computing binary space partitioning. KDTrees are very useful in several applications including range searches and nearest neighbor searches. The structure of the KDTree is similar to that of a binary search tree.
