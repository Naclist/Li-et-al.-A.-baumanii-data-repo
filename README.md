# Seven phylogeny trees saved in GrapeTree json format, as Supplementary Files for Li et al[^capy].
## Something you need to know before try to use these data
* File with '.json' subfix was generated by GrapeTree[^GrapeTree], which included a newick format phylogeny and a built-in metadata table.
* If you are an expert of EnteroBase or GrapeTree already, just try visulization on your PC directly; If not, please follow the following documentary or refer to the [GrapeTree tutorial](https://enterobase.readthedocs.io/en/latest/grapetree/grapetree-tutorial-1.html "GrapeTree tutorial").
* The advantages of GrapeTree comparing with other rectangular visulation tool (ITOL e.g.) are:
	* Classification for large structure within massive data at a glance(literally).
	* Fully interactive.

However, such characteristics have brought some problems, for example:
For some very close nodes, sometimes there will be inevitable and obvious overlap. Although I will describe some methods to avoid overlap below, for people who do not know GrapeTree or EnteroBase, it may cause some confusion in understanding the topological structure of the phylogeny. Anyway, please remember one thing, the results you see within GrapeTree are real.

## Loading data into GrapeTree
Currently, you have two ways to use GrapeTree: 
* Downloading the [Stand-alone version](https://github.com/achtman-lab/GrapeTree/releases) 
* Or using an [online demo](https://achtman-lab.github.io/GrapeTree/MSTree_holder.html). 
Both can load the json files we have prepared.

Open GrapeTree, click the "Load Files" button shown in the image below to select the json file, or simply drag the json file into the blank area of the web page. If everything runs OK, you will see the visualized phylogeny tree displayed by GrapeTree.

<img src=https://github.com/Naclist/Li-et-al.-A.-baumanii-data-repo/blob/main/img/loading.png width=30%>

## Basic usage documentation (from GrapeTree tutorial)
GrapeTree has a rich suite of tools to help you navigate and manipulate your tree. Try these out!

* If you get lost click Centre Tree under Tree Layout. Click Tree Layout to open or close the Layout panel.
* If you’ve messed up the tree Click Static Redraw under Tree Layout to reset the layout.
* Zoom in/out using the mousewheel or the Zoom buttons under Tree Layout. Click Tree Layout to open up the Layout panel and then click the magnifying glass (+) to zoom in or magnifying glass (-) to zoom out.
* Move the Tree by click & hold on any of the whitespace around the tree, and then drag.
* Move a node and its children by Click and holding the left mouse button down on a Node and then drag.
* Move the key/legend by Click and holding the legend and then drag to move it around.
* Rotate the entire tree by Click and holding the root node and then drag.
* Select some nodes by holding SHIFT key and dragging over some nodes in the tree. You can also select individual nodes by holding the SHIFT key and clicking on nodes one-by-one.
* Add more nodes to your selection by holding SHIFT key and dragging over other nodes in the tree.
* Deselect some nodes by holding SHIFT key and dragging over some already selected nodes. Try removing nodes from your current selection.
* Deselect all selected Nodes by double-clicking any whitespace around the tree, or by right-clicking and choosing Unselect all from the contextual menu.

For any users who explore this dataset, you may want to know the groups under ESL barcoding system. Right-click on the figure legends in the GrapeTree page. You should be able to switch the display of different groups to observe the topological differences of various hierarchical genotypes within the ESL barcoding system on the trees generated based on different sequences.

Specifically under Tree Layout > Branch Style:

* Scaling: will uniformly increase the scaling for all branches. For instance, setting it to 200% will double the length of all branches relative to the default setting (100%); whereas 50% would halve it.
* Collapse Branches: will collapse all branches under a certain length. The length value shown is the real branch length for the tree. To see the lengths for all branches, check the Branch Labels under Branch Style. The slider is scaled relatively, so moving it all the way to the right will collapse all the nodes giving you a pie graph (which I mentioned in the beginning).
* Log Scale: if this is checked (has a tick in the box), all branches will be Log-scaled. This is useful for trees with a wide variety of branch lengths.


[^capy]: https://www.researchsquare.com/article/rs-4224555/v1
[^GrapeTree]: https://genome.cshlp.org/content/28/9/1395
