# Network-Analysis
Creating and analysing networks to understand impact of network shapes and information flow on total information creation capacity, and creation potential
	
	1. Set up a network with a bunch of nodes and edges between them
	2. The edges are connected to nodes in a power law distribution
	3. Each node has a particular "processing" capacity, distributed in a normal distribution
	4. Each node can also create information within its "processing" capacity; the creation ability is distributed in a normal distribution
	5. The "information" is created by a node in response to a) function of how much information has come into the node, b) the free "processing" capacity of that node
		a. Processing capacity reduces as more information comes into the node, in a linear fashion
		b. As each piece of information reaches another node, it gets read & processed, which takes "effort" until processing is done. Processing here mostly either (in increasing order of effort) accepts the information or changes it slightly or creates a variant information* which is similar or different according to a normal distribution
	6. Once created, this information propagates through the network like a cascade/ contagion
