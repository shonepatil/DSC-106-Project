# DSC-106-Project

## How to Run the Visualizations
First setup the dataset by running `data_cleaning.ipynb` to output a dataset called `data_master.csv` to be used by the various visualization notebooks. Make sure the dataset outputted is in the same root as all the other notebooks. From here, you can load individual graphs by opening their respective notebooks(i.e. `collab_popularity_network_pop.ipynb`) and running all cells. Another option is to open `All_Visualizations.ipynb` to view all the graphs in a single notebook.

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

