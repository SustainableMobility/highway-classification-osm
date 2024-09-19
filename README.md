# highway-classification-osm
Python code to classify roads and paths based on highway tags present in OpenStreetMap.

## Classes
- **Arterial roads** included high-capacity roads built for faster motor vehicle travel with low accessibility. 
- **Collector roads** included roads that provide higher access than arterials while compromising on mobility, and connected arterial and local roads. 
- **Local roads** comprised the majority of the network, with the highest access and lowest mobility, mostly built around residential land-use. 
- **Paths and crossings** included all off-road paths (dedicated and shared bike paths) and road crossings.

## Technology
  * Python
  * OpenStreetMap
  * Python packages
    * [OSMnx](https://osmnx.readthedocs.io/en/stable/user-reference.html)
    * [NetworkX](https://networkx.org/)
    * [geojson](https://pypi.org/project/geojson/)
    * [Shapely](https://shapely.readthedocs.io/en/stable/manual.html)
    * [Pandas](https://pandas.pydata.org/docs/index.html)
    * [Geopandas](https://geopandas.org/en/stable/)
    * [Matplotlib](https://matplotlib.org/)
   
## How to implement in Python
  * Install the aforementioned Python packages in your environment as described in the links.
  * Run the Jupyter Notebook.

## Authors
The document has been prepared by **Dr Debjit Bhowmick** and **Assoc Prof Ben Beck** from the Sustainable Mobility and Safety Research (SMSR) Group at Monash University. 
For any queries, please contact Dr Debjit Bhowmick (Research Fellow, debjit.bhowmick@monash.edu) or Assoc Prof Ben Beck (Head of SMSR, ben.beck@monash.edu).

## Citation
If you are using this classification system for your work, we strongly recommend citing this repository using the 'Cite this repository' feature on GitHub (found on the right side when you open the repo). 
Alternatively, you may use the guidelines provided [here](https://www.ilovephd.com/how-do-you-cite-a-github-repository/).

### BibTeX
```
@misc{Sustainable_Mobility_and_Safety_Research_Group_Highway_Road_classification_using_2024,
author = {Sustainable Mobility and Safety Research Group, Monash University},
title = {{Highway/Road classification using OpenStreetMap}},
url = {https://github.com/SustainableMobility/highway-classification-osm},
doi = {https://doi.org/10.6084/m9.figshare.27059980.v1},
year = {2024}
}
```
>
### APA
```
Sustainable Mobility and Safety Research Group, Monash University. (2024). Highway/Road classification using OpenStreetMap. https://github.com/SustainableMobility/highway-classification-osm. doi: [https://doi.org/10.6084/m9.figshare.27059983.v1](https://doi.org/10.6084/m9.figshare.27059980.v1)
```
