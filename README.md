# RatingAwareSOM
Source codes and results for MMM 2022 paper **Rating-aware Self-Organizing Maps** 
Ladislav Peska and Jakub Lokoc
[ladislav.peska|jakub.lokoc]@matfyz.cuni.cz


### Abstract 

Self-organizing maps (SOM) are one of the prominent paradigms for 2D data visualization. While aiming at preserving topological relations of high-dimensional data, they provide sufficiently organized view of objects and thus improve capability of users to explore displayed information. SOMs were also extensively utilized in visualizing results of multimedia information retrieval systems. However, for this task, SOM lacks the ability to adapt to the relevance scores induced by the underlying retrieval algorithm. Therefore, although exploration capability is enhanced, the capability to exploit the (best) results is severely limited. In order to cope with this problem, we propose a rating-aware modification of SOM algorithm that jointly optimizes for the preservation of both topological as well as relevance-based ordering of results.

### Repository content

- /SOM_img: visualizations of the generated SOMs. This folder contains figures for both color-sorting and VBS tasks
- /Figures: high-resolution figures utilized in the paper
- /Results: pickles of the raw results. For space reasons, only the color sorting is provided; for VBS raw results please contact the authors. For loading and usage please see the Python notebooks
- .ipython notebooks implementing Rating-aware SOM, evaluation metrics and visualization procedures
