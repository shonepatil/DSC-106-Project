# DSC-106-Project: Spotify Songs Collaboration Analysis/Visualizations

## Contributors
Shone Patil, Harsha Jagarlamudi

## Overview
In this project, we took a deep look at how song collaborations among artists changed over the years and across many genres. Through the use of various graph designs including line charts, scatterplots, bar charts, and network graphs, we compared song genres, attributes, and release years to a number of custom collaboration metrics. Each visualization unpacks a different aspect of song collaboration that adds to the story of how it has evolved to where it is now. The data we used to carry out this exploration was sourced from the Spotify music streaming service and pulls directly from their API. 

## How to Run the Visualizations
First, setup the dataset by running `data_cleaning.ipynb` to output a dataset called `data_master.csv` which will be used by the various visualization notebooks. Make sure the dataset outputted is in the same root directory as all the other notebooks. From here, you can load individual graphs by opening their respective notebooks (i.e. `collab_popularity_network_pop.ipynb`) and running all cells. Another option is to open `All_Visualizations.ipynb` to view all the graphs in a single notebook.

## Libraries Used
```
altair
ast
nest_asyncio
networkx
numpy
pandas
pyvis
```

## Files

### Information
```
README.md
powerpoint TODO
```

### CSVs
```
archive/data.csv
archive/data_by_artist.csv
archive/data_by_genres.csv
archive/data_by_year.csv
archive/data_w_genres.csv
```

### Final Dataset
```
data_cleaning.ipynb
data_master.csv
```

### Individual Graphs
```
attribute_line.ipynb
collab_line.ipynb
collab_popularity_network_pop.ipynb
collab_popularity_network_rap.ipynb
genre_line.ipynb
genre_popularity_scatter.ipynb
timescaled_top_collaborators.ipynb

```
 
### Final Graphs
```
All_Visualizations.ipynb
```
