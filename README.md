# NDC_landscape

Explore ~140,000 prescription and over the counter medications by their NDC drug descriptions

1) Load existing drug lists from csv file (downloaded from FDA)
2) Query descriptions for each ndc drug code using FDA's RESTful API (https://open.fda.gov/drug/label/)
3) Write results into a mySQL database
4) Visualize drug description landscape by calculating tf/rdf of each description and by collapsing the multidimensional vector onto 2D. 
